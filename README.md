this is my practice repo
JS is a dynamic language<br> you can change the type of variable as you go
primitive/value types include string, bool, number, undefined and null. <br>
undefined is when you dont assign any type to a variable null is for empty <br>
reference types are arrays, objects and functions <br> arrays and functions are also objects so infact only reference type is only object!

execution context <br>
1. memory phase- variable environment 
2. code phase- thread of execution
<br>
hoisting-we can access variable and function before iniatilisation because of memory phase
console.log(a) is same as console.log(this.a) or window.a window and this is both referring to the global object <br>
you can declare variables using let var and const
<br>
const and let are more strict than var, const is for constant and avoid using var, before code phase var assigns memory with undefined, let and const are also memory allocated but not initailised with undefined and you cant access it. its the temporal dead zone. (avoid this by iniatlise at start)<br>
const and let are block scoped...if value of variable is not mentioned in function then outside is taken otheriwse inner-> lexical scope but vice versa isnt allowed <br>
fucntions are called first class citizens <br>
they can be assigned as variable, can be passed as arguments in other functions. called higher order function(take function as argumnets or return functions) <br>

How to handle asynchronous behaviour in javascript -> like data is being fetched will the whole code wait? no we have callbacks <br>
call backs are functions executed after a specific operation is done-> event queue and event loop
<br> Problems with Callbacks- callback hell and pyramid of doom<br>
promises-object 
<br> 3 states
-> pending,fulfilled,rejected-> can implement async operation succesfully