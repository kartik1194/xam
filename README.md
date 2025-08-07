# STEPS to install tailwindcss@3

1. dist src folder. (dist>index.html)
2. npx tailwindcss@3 init
3. src > input.css ( @tailwind base , components , utilities )
4. tailwind.config content
5. npx tailwindcss@3 -i ./src/input.css -o ./dist/output.css --watch

# steps

1. npm init -y
2. npm install tailwindcss @tailwindcss/cli
3. create ./src/input.css (@import "tailwindcss";)
4. npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch

# steps
1. npm create vite@latest my-project
   cd my-project
2. npm install tailwindcss @tailwindcss/vite
3. config: import tailwindcss from '@tailwindcss/vite'
           plugins: [
    tailwindcss(),
                ],
4. @import "tailwindcss";
5. npm run dev

or
1. npm create vite@latest my-project -- --template react
    cd my-project

2. npm install -D tailwindcss@3 postcss autoprefixer
   npx tailwindcss init -p

3. content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],

4. @tailwind base;
   @tailwind components;
   @tailwind utilities;

# letter spacing : tracking-tight/normal/wide
# line height : leading-none/normal/relaxed
# shadow-sm/md
# flex flex-row/column items/justify-start/center/end/between  gap flexwrap

# grid grid-cols-3 gap-4
 

