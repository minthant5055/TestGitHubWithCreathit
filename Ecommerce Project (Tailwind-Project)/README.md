# Hello Project

## Project setup
```
npm install -D tailwindcss@latest postcss@latest autoprefixer@latest
```
## Tailwind config setup
```
npx tailwindcss init
```
### Copy to CSS
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
### Add to package.json
```
"scripts": {
      "build-css": "tailwindcss build src/style.css -o public/style.css"
    },
```
### Build and minifies for production
```
npm run build-css
```
### Start Live-Server
```
control + command + space ( place of )
⌘ + L
⌘ + O
```
### To Do List
```
to use docs <!--comments-->


### References
https://tailwindcss.com/docs/installation
https://undraw.co/illustrations ( svg )
<img src="https://picsum.photos/200/300?random=1">

### Reference Website
https://glamour-ishi.myshopify.com/ 

### hover effftct 
https://ciar4n.com/izmir/index.html
https://varin6.github.io/Hover-Buttons/
http://imagehover.io/#download

### for accordion
https://www.w3schools.com/howto/howto_js_accordion.asp

### for tab
https://www.w3schools.com/w3css/w3css_tabulators.asp

### button bg-color after click button
https://www.w3schools.com/howto/howto_js_active_element.asp