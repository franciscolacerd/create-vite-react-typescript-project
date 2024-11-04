# Create Vite React Typescript Project
How to create Vite React typescript Project

https://vite.dev/guide/

## Create project
```powershell
npm create vite@latest NewProject -- --template react-ts
cd NewProject 

npm i
```

## Run project
```powershell
npm run dev
```

## Install Tailwind CSS with Vite

```powershell
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

## Configure your template paths

```typescript
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

## Add the Tailwind directives to your CSS

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

## Install react-router

```powershell
npm i react-router-dom
```

