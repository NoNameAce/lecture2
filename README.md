# Scope
## Explanation

Scope a territory, area or a zone where you write your code
There are 2 types of scopes
+ Global Scope
+ Local Scope

### What is a **global Scope**?
There is an invisible scope {} in JS. And everithing we write in it is a part of a GS An area where we write our code

### What is a **local scope**?
The scope which is created in global scope is called LS. Our local scope has access to elements from the global scope however GS can does not have access LS codes or variables
Moreover LS is devided in two subtypes
+ Functional Scope
+ Block Scope

### What is **FS**?
FS is a code written in a function
### What is **BS**?
BS is a written in conditions and loops

## Variables 
Variables **const** and **let** are **block scope** 
However **var** is a **functional scope** since loops and conditions are weaker than **var** but function is strong enough to hold it


# Hoisting
### What is it?
**Hosting** is calling our variable or function before creating it
For Instance
~~~ JS
console.log(a)
var a = 10
~~~

### There are only two cases in which we can use **Hoisting**
+ With **Function Decloration**
+ With variable **var**
In other cases it gives an error. **Temporary Dead Zone**


