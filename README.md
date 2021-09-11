# Tailwind CSS

# Installation steps

1. npm init -y
2. npm install tailwindcss
3. Create public and src directories, styles.css file inside the src folder.
4. Add the script in package.json file:
   "build-css": "tailwindcss build -i src/styles.css -o public/styles.css"
5. Initialize the tailwind.config.js file (--full is for adding all the default configs):
    npx tailwindcss init --full 
6. npm run build-css