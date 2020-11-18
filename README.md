# loader.js
## Loading made easy

loader.js is a simple js library that can let you make your own loading screen and implement it easily

# Getting The Library

you can Use these Scripts to include `loader.js` or `loader.min.js` in your html.

```html
<script src="https://rawcdn.githack.com/atoms19/loader.js/main/dist/loader.js"></script>
<script src="https://rawcdn.githack.com/atoms19/loader.js/main/dist/loader.min.js"></script>
```

# How To Use

Create a new loader object and call the activate method to activate the loader

```javascript
var loader=new Loader("red",5,"white");
loder.activate(); 
```
Loader object takes ***3*** parameters 
```javascript
new Loader(String, Number, String);
```
The first argument is the `Color` of the loader.

The second argument is the `Thickness` of the loader.(Its value is determined in PXs)

The third argument is the `Backdrop Color` of the loader.

# Stopping The Loader

## Auto Close the Loader When page Loads
```javascript
var loader=new Loader("red",5,"white");
laoder.activate();
loader.closeWhenDone();
```
To close the loader automatically use `closeWhenDone();` method.

## Stoping Manually

```javascript
var loader=new Loader("red",5,"white");
laoder.activate();
loader.closeCountDown(5000);
```
`closeCountDown();` method takes a number as a parameter and Stops the loader after that time.

***Note:*** Time is in milliseconds.
