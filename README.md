# Table of Contents
## Arrays
## Array Methods

### What is a Array in JavaScript?

An **Array** in JavaScript is a type of global object used to store data.
Arrays can store multiple values in a single variable,
which can condense and organize our code
~~~
const cars = ["Saab", "Volvo", "BMW"];
~~~

There are many **Array Methods** in JS but here are some of them
+ pop()
+ shift()
+ push()
+ unshift()
+ concat()
+  slice()
+ join()
+ includes()
+ indexOf()
+ splice()
+ toString()
+ toReversed()
~~~
const fruits = ["Banana", "Orange", "Apple", "Mango"];
let fruit = fruits.at(2);

~~~

~~~
let numbers = Math.pow(2,3)
console.log(numbers)

~~~
~~~
const fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.push("Kiwi");
~~~

~~~ 
const fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.unshift("Lemon")
~~~
~~~ 
const myGirls = ["Cecilie", "Lone"];
const myBoys = ["Emil", "Tobias", "Linus"];

const myChildren = myGirls.concat(myBoys);
~~~
~~~ 
const fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.splice(2, 0, "Lemon", "Kiwi");
~~~
~~~ 
const fruits = ["Banana", "Orange", "Lemon", "Apple", "Mango"];
const citrus = fruits.slice(1);
~~~

## Array Method Callbacks

The functions that can contain functions in it are called **Callbacks**
There are Many Callbacks in JS but here are some

JS array Method **Map**
We use map to change and return elements in Array
However we can not change the length of array
~~~
let arr = [1,2,3,4,5]
let res = arr.map((element, index, array) => {"The condition"})
~~~

JS array Method **forEach**
Foreach works as **map** but it does not return
~~~
let arr = [1,2,3,4,5]
let res = arr.forEach((element, index, array) => {"The condition"})

~~~
JS array Method **find**
**Find** is used to find some exact elements we need
~~~
let arr = [1,2,3,4,5]
let res = arr.find((element, index, array) => {"The condition"})
~~~

JS array Method **filter**
**Filter** is used to clear our array and return the elements we need
~~~
let arr = [1,2,3,4,5]
let res = arr.filter((element, index, array) => {"The condition"})
~~~

JS array Method **reduce**
**reduce** is usually used for calculation
It accepts accumulator which is the previous value and current value
~~~
let arr = [1,2,3,4,5]
let res = arr.reduce((accumulator, element, index, array) => {"The condition"})
~~~

JS array Method **toSorted**
**toSorted** is used for sorting our array in order
~~~
let arr = [1,2,3,4,5]
let res = arr.toSorted((element, index, array) => {"The condition"})
~~~

## There are Mechanisms in JS
Here are some:

**Destructurisation**
It is used to add our array's values to variables

**Spread**
It is used to get our values in function in one array for us when we dont know exactly how many values should it contain

**rest**
It allows a function to accept an indefinite arguments. It must be the only and last parameter in function



