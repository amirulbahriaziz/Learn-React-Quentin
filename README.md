# Learn-React-Quentin

## Topic

- [React](https://reactjs.org/)
- [TailwindCSS](https://tailwindcss.com/)

## References

- [Quentin Watt Tutorials](https://youtu.be/HDEVMozZhv8)
- [LogRocket](https://youtu.be/pnDsP3BbXPg)
- [Smashing Megazine](https://www.smashingmagazine.com/2020/02/tailwindcss-react-project/)

## Installation

Create a new project.

```bash
npx create-react-app learnreactquentin
cd learnreactquentin
npm start
```

Install Tailwind via npm

```bash
npm install tailwindcss postcss-cli autoprefixer -D
```

Initialize Tailwind CSS configuration file by renaming it to **_tailwind.js_**

```bash
npx tailwindcss init tailwind.js --full
```

Create a PostCSS configuration file

```
touch postcss.config.js
```

Navigate to **_postcss.config.js_**, then add the following lines of code.

```
const tailwindcss = require('tailwindcss');
module.exports = {
    plugins: [
        tailwindcss('./tailwind.js'),
        require('autoprefixer')
    ],
};
```
