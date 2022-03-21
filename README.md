# what3words

## setup project

Create react app with vite
```bash
npm create vite@latest
```

Install Tailwind CSS
```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

Configure template paths (tailwind.config.js)
```js
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

Add the Tailwind directives to your CSS (src/index.css)
```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
