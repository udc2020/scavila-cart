# Scavila Dashboard cart 🔥 
---
## By **UltrasDzCoder** You can See Full course [here]([https://link](https://www.youtube.com/c/UltrasDzCoder?sub_confirmation=1))


---
![ultrasdzcoder scavila](screenshootscavila.gif)

---
### We Use:
- HTML
- CSS 
- Tailwind CSS 

### Get Started :
1. install tailwind:

      npm install -D tailwindcss
      npx tailwindcss init

2. add configuration file:

      module.exports = {
      content: ["./src/**/*.{html,js}"],
      theme: {
         extend: {},
      },
      plugins: [],
      }

3. add directives:

      @tailwind base;
      @tailwind components;
      @tailwind utilities;


4. build css file :

      npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch

5. create index.html :

         <!doctype html>
         <html>
         <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <link href="/dist/output.css" rel="stylesheet">
         </head>
         <body>
         <h1 class="text-3xl font-bold underline">
            Hello world!
         </h1>
         </body>
         </html>
