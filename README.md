# MERNERA
Project Cloud Link : https://mernera.vercel.app/
###  Use Firefox Browser for better experience 
### Setup instruction

1. Clone the project

```
   https://github.com/shrivarshapoojari/MERNERA--Empowering-Students.git
```

2. Move into the directory

```
    cd Frontend/lms
```

3. install dependencies

```
    npm i
```

4. run the server

```
    npm run dev
```
5. Move to directory
    ````
      cd Backend
    ````
7. Install Dependencies
     ```
     npm i
     ````
8. Run Backend Server
   ```
     node server.js
       OR
   nodemon server.js
   `````
   


### Setup instructions for tailwind

[Tail wind official instruction doc](https://tailwindcss.com/docs/installation)

1. Install tailwindcss

```
    npm install -D tailwindcss postcss autoprefixer
```

2. Create tailwind config file 

```
    npx tailwindcss init
```

3. Add file extensions to tailwind config file in the contents property
```
    "./src/**/*.{html,js,jsx,ts,tsx}", "./index.html",

```

4. Add the tailwind directives at the top of the `index.css` file

```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
```

5. Add the following details in the plugin property of tainwind config

```
    [require("daisyui"), require("@tailwindcss/line-clamp")]
```

### Adding plugins and dependencies 

```
npm install @reduxjs/toolkit react-redux react-router-dom react-icons react-chartjs-2 chart.js daisyui axi
os react-hot-toast @tailwindcss/line-clamp
```


 
   
