1. Install Node: https://nodejs.org/en/download
2. Check node version: node -v
3. Setup Project: npm init -y
4. npm install -D tailwindcss
5. npx tailwindcss init
6. Change tailwind.config.js: content: ["*.html"],
7. Create index.html file
8. Create index.css
Add below lines:
@tailwind base;
@tailwind components;
@tailwind utilities;
9. Add css link in your index.html
<link href="./styles.css" rel="stylesheet" />
10. Generate styles.css from index.css, by executing below command in terminal
npx tailwindcss -i index.css -o ./styles.css --watch


