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

Create a new loader object and call the `activate();` method to activate the loader.

```javascript
var loader=new Loader("red",5,"white");
loader.activate();
//Activating the loader
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
//This will automatically close the loader when page loads
```
To close the loader automatically use `closeWhenDone();` method.

## Stoping Manually

```javascript
var loader=new Loader("red",5,"white");
laoder.activate();
loader.closeCountDown(5000);
//It will stop the loader after 5 seconds
```
`closeCountDown();` method takes a number as a parameter and Stops the loader after that time.

***Note:*** Time is in milliseconds.
# More Controls
```javascript
var loader=new Loader("red",5,"white");

loader.color="dodgerblue";
//The default value for color is "dodgerblue"
loader.thickness=10;
//The default value for thickness is 10
loader.bgcolor="white";
//The default value for bgcolor is "white"
loader.time=1;
//The default value for time is 1
loader.size=70;
//The default value for size is 70
loader.animation="linear";
//The default value for animation is "linear"
```
