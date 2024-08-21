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



