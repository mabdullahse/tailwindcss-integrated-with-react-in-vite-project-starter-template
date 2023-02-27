# tailwindcss-integrated-with-react-in-vite-project-starter-template

This is starter template of react application created via vite. Then integrate tailwindcss with it

## Step: 1: Create new project using vite for reactjs

```
yarn create vite
```
Write a project name afterwards.

Select React > Javascript



##Step: 2: Install the Tailwindcss along with its relevent dependencies

```
npm install -D tailwindcss postcss autoprefixer
```

##step 3: Generate the configuration files

```
npx tailwindcss init -p
```

update the tailwind.config

```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ['./index.html', './src/**/*.{js,ts,jsx,tsx}'],
  theme: {
    extend: {},
  },
  plugins: [],
};

```

##step: 4 add imports to ./src/index.css file

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

##Step: 5: Start the project

```
yarn dev
```






