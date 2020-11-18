# loader.js
## Loading made easy

#### loader.js is a simple js library that can let you make your own loading screen and implement it easily

# Getting The Library

you can get the library by copying and pasting the CDN link inside the script tag as the source(src)

```html
<script src="https://rawcdn.githack.com/atoms19/loader.js/main/dist/loader.js"></script>
<script src="https://rawcdn.githack.com/atoms19/loader.js/main/dist/loader.min.js"></script>
  
```

# How To Use

Create a new loader object and call the activate method to activate the loader

```javascript
var loder=new Loader("red",5,"white");

loder.activate(); 
```
Loader object takes ***3*** parameters
`new Loader(loaderColor, LoaderThickness, Background Color);`
