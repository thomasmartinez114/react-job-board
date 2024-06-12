### Install Dependencies....

```
npm install
```

#### Tailwinds

```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

tailwind.config.js

```
/** @type {import('tailwindcss').Config} */
export default {
  content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"],
  theme: {
    extend: {
      fontFamily: {
        sans: ["Roboto", "sans-serif"],
      },
    },
  },
  plugins: [],
}

```

index.css

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

### Run JSON Server

```
npm run server
```

### Run Vite Frontend (Dev)

```
npm run dev
```

### Build for Production

```
npm run build
```

### Preview Production Build

```
npm run preview
```
