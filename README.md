### Start New Project
<hr>


Initial the Project
```
npm init -y
```

```
npm install tailwindcss
```
- create public & src folder

- create public/styles.css and add code below to styles.css

```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
- running script below to script part in package.json

```
"build-css": "tailwindcss build src/styles.css -o public/styles.css"
``` 

- run in terminal mode

```
npm run build-css
```


### Resource & Refference
- [Tailwind The Net Ninja Tuts](https://www.youtube.com/watch?v=bxmDnn7lrnk&list=PL4cUxeGkcC9gpXORlEHjc5bgnIi5HEGhw)
- [Tailwind docs](https://tailwindcss.com/docs/installation/using-postcss)