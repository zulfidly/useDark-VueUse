# v

npm init vue@latest
cd v
npm install
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

add to css file :
@tailwind base;
@tailwind components;
@tailwind utilities;

update tailwind.config.js
module.exports = {
  darkMode: 'class',  
  content: [
    "./src/**/*.{vue,js}",
    "./src/components/**/*.{vue,js}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

