# Table of Contents
## Object
## Destructurisation
## Spread

### What is Object in JavaScript?

**Objects** in JavaScript offer you tremendous flexibility and code re usability,
you are able to create self contained units to store data, characteristics and methods,
as opposed to long scripts of procedural code.

## So what is an object?

Well, step away from code for the time being and think of a real world object, take a car for example.

A car as itself is an object, the car has properties:

+ Doors
+ Colour
+ Wheels
+ Manual Transmission
Now these are only a few properties of a car but start to think of what values these properties could have.

+ Doors = 4
+ Colour = Black
+ Wheels = 4
+ Manual Transmission = True
Notice the 3 different data types used here, string, number and Boolean, this should give you a basic grasp on what an object is, now lets apply it in the realm of JavaScript and create our first object.
~~~
function myCar(){
  doors = 4;
  colour = "black";
  wheels = 4:
  manualTransmission = true;
}
console.log(myCar.colour);
~~~

## Object Methods in JS

Objects in JavaScript are collections of key/value pairs. The values can consist of properties and methods,
and may contain all other JavaScript data types, such as strings, numbers, and Booleans

**Object.entries()**
Gets our Object with its properties in arrays

~~~
const obj = {
  a: 'somestring',
  b: 42,
};

let res = Object.entries(obj))

~~~

**Object.keys()**
It creates an array containing the keys of an object.
~~~
let obj = {
  boss: "Kamol",
  secretary: "Anush",
  sales: "Shodob"
};

let res = Object.keys(obj);

console.log(res);

~~~

**Object.values()**
It creates an array containing the values of an object
~~~
let obj = {
  id: 1,
  time: `26-July-2018`,
  device: "mobile",
  browser: "Chrome"
};

let res = Object.values(obj);

console.log(res);
~~~

## What is Destructuring, Rest and Spread operator in JavaScript?

+ Destructuring is a functional programming concept
+ It will unpack values from array or properties from object to individual variables
+ Array De-structuring:

~~~
let person = {"fName":"Chandu", "lName":"Pasumarthi"}
let {lName, fName} = person
~~~

## Spread Mechanism
Spread operator syntax is similar to Rest property in array de-structuring,
But Spread will split into individual elements whereas rest collects into an array
~~~ 
let numbers = {"1":"One", "2":"Two"}

let moreNums = {...numbers}
console.log(moreNums)
~~~

