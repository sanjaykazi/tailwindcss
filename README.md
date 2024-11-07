# tailwindcss
tailwind css 

installation guide:
1. install node
2. https://tailwindcss.com/docs/installation/using-postcss (using postcss)
    npm install -D tailwindcss postcss autoprefixer vite
    npx tailwindcss init -p
3. vs code extention install: Tailwind CSS IntelliSense
4. Add * in content (tailwind.config.js > content: ["*"])
5. add scripts in package.json ("scripts": {
                                  "start": "vite"
                                 }
                                )
6. Create main.css and insert and link
        @tailwind base;
        @tailwind components;
        @tailwind utilities;
7. run `npm run start`