# JavaScript-100-objective-based-questions


**1. Can we connect JavaScript Directly with Actual Database. can you give reason of it ?**
```js
a) Yes;
b) No;
c) Sometime;
d) Some Database
```
<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: b) No
</ul>
</details>


**2. Which of the following is NOT a JavaScript data type?**
```js
a) String
b) Boolean
c) Float
d) Undefined
```

<details>
	<summary><b>View Answer</b></summary>
<ul>
Answer: c) Float
</ul>
</details>


**3. Which symbol is used for single-line comments in JavaScript?**
```js
a) //
b) /*
c) #
d) <!--
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) //
</ul>
</details>


** 4. What will typeof null return?**
```js
a) "null"
b) "object"
c) "undefined"
d) "string"
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) "object"
</ul>
</details>



**5. How to make immutable object in JavaScript**
```js
a) final var ={name:'Anil'}
b) const user={name:'Anil'}
c) var  user={name:'Anil'}; Object.freeze(user);
c) There is no way to make immutable object
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) var  user={name:'Anil'}; Object.freeze(obj);
</ul>
</details>



**6. Operators & Expressions
What will 2 + "2" evaluate to? **
```js
a) 4
b) "22"
c) NaN
d) Error
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) "22"
</ul>
</details>


*** 7.Which operator is used for strict equality in JavaScript?***
```js
a) ==
b) !==
c) =
d) !=
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) !==
</ul>
</details>



**8. What does !!"false" evaluate to?**
```js
a) true
b) false
c) undefined
d) Error
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) true
</ul>
</details>



**9. What is the result of 5 == "5"?**
```js
a) true
b) false
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) true
</ul>
</details>



** 10. What is the result of type of  "5 " === " 5"? **
```js
a) true
b) false
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) false
</ul>
</details>



** 11. Which loop is guaranteed to execute at least once? **
```
a) for loop
b) while loop
c) do-while loop
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) do-while loop
</ul>
</details>



**12. Output of this for loop loop**
```js 
for(;;) {
console.log("Loop")
}
```
```js
a) Infinit Loop 
b) Loop will not execute
c) Error
d) Only Run once 
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) Infinit Loop
</ul>
</details>


** 13. What will console.log(typeof NaN); print? **
```js
a) "number"
b) "NaN"
c) "undefined"
d) "object"
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) "number"
</ul>
</details>


**14. Output of below statment**
```js
let x=null;
let y=null;
console.log(x+y) 
```
```js
a) null
b) object
c) 0
d) undefined
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) 0
</ul>
</details>


*** 15. What will console.log(typeof function(){}); return? ***
```js
a) "function"
b) "object"
c) "undefined"
d) "null"
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) "function"
</ul>
</details>


*** 16. What will console.log(typeof function(){}(); return? ***
```js
a) "function"
b) "object"
c) "undefined"
d) "null"
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) "undefined"
</ul>
</details>

*** 17. What is the default return value of a function in JavaScript if no return statement is used? ***
```js
a) null
b) undefined
c) false
d) 0
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) undefined
</ul>
</details>


** 18. Which type of function executes immediately after its definition? **
```js
a) Anonymous function
b) Named function
c) IIFE (Immediately Invoked Function Expression)
d) Arrow function
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) IIFE
</ul>
</details>


**19 Outpout of below statment ** 
```js
 console.log(x);
 let x = 5; 
```
```js 
a) 5
b) undefined
c) ReferenceError
d) NaN
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) ReferenceError
</ul>
</details>


**20. How do you create an object in JavaScript? **
```js
a) let obj = {};
b) let obj = new Object();
c) Both a and b
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) Both a and b
</ul>
</details>


**21 How do you access a property in an object?**
```js
a) obj[property]
b) obj.property
c) Both a and b
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) Both a and b
</ul>
</details>

**22. Which method is used to add a new element at the end of an array?**
```js
a) push()
b) pop()
c) shift()
d) unshift()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) push()
</ul>
</details>


**23 What will console.log([1,2,3].length); return? **
```js
a) 2
b) 3
c) 4
d) undefined
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) 3
</ul>
</details>


**24 How do you remove first 2 element of an array?**
```js
a) pop()
b) shift()
c) unshift()
d) splice()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) splice()
</ul>
</details>


**25 Which keyword allows block-scoped variable declarations? **
```js
a) var
b) let
c) const
d) Both b and c

```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) Both b and c
</ul>
</details>

**26 Which of the following is true about const variables?**
```js
a) Their values cannot be changed
b) They cannot be reassigned
c) They are always immutable
d) All of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) They cannot be reassigned
</ul>
</details>


**27. What is the output of console.log(typeof([]));? **
```js
a) "object"
b) "array"
c) "undefined"
d) "null"
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) "object"
</ul>
</details>


**28 What is a template literal in JavaScript? **
```js
a) A type of array
b) A string enclosed in backticks (` `)
c) A special function
d) A new ES6 data type
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) A string enclosed in backticks (` `)
</ul>
</details>


**29. What will console.log(..."Hello"); output? **
```js
a) "H e l l o"
b) ["H", "e", "l", "l", "o"]
c) Syntax Error
d) undefined
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) "H e l l o"
</ul>
</details>


** 30. How do you define an arrow function? **
```
a) const add = (a, b) => a + b;
b) const add = function(a, b) { return a + b; };
c) Both a and b
d) None of the above
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) const add = (a, b) => a + b;
</ul>
</details>



**31 What does the spread operator ... do in JavaScript?**
```js
a) Combines arrays
b) Expands iterable elements
C) All of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: C) All of the above
</ul>
</details>


** 32. What will console.log([...new Set([1, 2, 2, 3])]); return? **
```js
a) [1, 2, 3]
b) [1, 2, 2, 3]
c) Set {1, 2, 3}
d) {1, 2, 3}
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) [1, 2, 3]
</ul>
</details>


**33. Which statement about arrow functions is true? **
```js
a) They do not bind this
b) They can be used as constructors
c) They have a prototype property
d) They support arguments keyword
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) They do not bind this
</ul>
</details>


**34 Output of follow code? **
```js
function tryFruits(...fruits)
{
console.log(...fruits)
}

tryFruits('apple','banana','grapes')
```
```js
a) ['apple', 'banana', 'grapes']
b) {'apple', 'banana', 'grapes'}
c) 'apple 'banana grapes'
d) 'apple'
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a)  ['apple', 'banana', 'grapes']
</ul>
</details>


**35. What is the purpose of JavaScript Promises?**
```js
a) Handle synchronous code
b) Handle asynchronous operations
c) Block execution until resolved
d) Replace all callbacks
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Handle asynchronous operations
</ul>
</details>


**36. Which state is NOT valid for a Promise?**
```js
a) Pending
b) Fulfilled
c) Rejected
d) Running
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) Running
</ul>
</details>


**37. Use of Await keyword ?**
```js
a) wait for an asynchronous operation to finish before continuing the execution
b) make promise
c) atop execution  
d) all of above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) wait for an asynchronous operation to finish before continuing the execution
</ul>
</details>


**38. Which method selects an element by ID?**
```
a) document.getElementofId()
b) document.getElementById()
c) document.selectElementById()
d) document.selectById()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) document.getElementById()
</ul>
</details>



**39 Which event is triggered when an input field loses focus?**
```js
a) click
b) blur
c) focus
d) change
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) blur
</ul>
</details>


**40. Which method adds an event listener to an element?**
```js
a) element.addEventListener()
b) element.attachEvent()
c) element.onEvent()
d) element.setEventListener()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) element.addEventListener()
</ul>
</details>


**41. What does event.preventDefault() do?**
```js
a) Stops the default action of an event
b) Stops event propagation
c) Prevents event from being attached
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) Stops the default action of an event
</ul>
</details>

**43. What is localStorage used for?**
```js
a) Storing session data
b) Storing data persistently in the browser
c) Making API requests
d) Caching images
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Storing data persistently in the browser
</ul>
</details>


**44 Which method converts a JavaScript object into a JSON string?**
```js
a) JSON.stringify()
b) JSON.parse()
c) toJSON()
d) parseJSON()
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) JSON.stringify()
</ul>
</details>


**45 What will console.log(parseInt("10px")) return?**
```js
a) 10
b) NaN
c) "10px"
d) Error
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) 10
</ul>
</details>


**46. Which method executes a function repeatedly with a time interval? **
```js
a) setInterval()
b) setTimeout()
c) repeat()
d) setLoop()
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) setInterval()
</ul>
</details>



** 47. How do you check if a variable is an array?**
```js
a) typeof x === "array"
b) x.isArray()
c) Array.isArray(x)
d) x instanceof Object
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) Array.isArray(x)
</ul>
</details>




** 48. What is a closure in JavaScript?**
```js
a) A function inside another function that has access to its parent’s scope
b) A block of code that runs automatically
c) A way to define private variables
d) Both a and c
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) Both a and c
</ul>
</details>



**49. Which of the following is true about closures?**
```js
a) Closures have access to their own scope
b) Closures have access to their parent function's scope
c) Closures have access to global scope
d) All of the above
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) All of the above
</ul>
</details>

**50.What will this code output?**
```js
function outer() {
    let count = 0;
    return function inner() {
        count++;
        console.log(count);
    };
}
const counter = outer();
counter();
counter();
```

```js
a) 1 2
b) 0 1
c) 1 1
d) Error
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) 1 2
</ul>
</details>


**51. Which statement about var and let is true?**
```js
a) Both are function-scoped
b) var is function-scoped, let is block-scoped
c) Both are block-scoped
d) var allows redeclaration, let doesn’t
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) var is function-scoped, let is block-scoped
</ul>
</details>


**52. What will console.log(x); var x = 10; output?**
```js
a) 10
b) undefined
c) ReferenceError
d) NaN
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) undefined
</ul>
</details>


** 53. Which statement is used for error handling in JavaScript?**
```js
a) try...catch
b) throw
c) finally
d) All of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) All of the above
</ul>
</details>


**54 What happens if an error occurs inside the try block?**
```js
a) The script stops execution
b) The error is caught in the catch block
c) The script crashes
d) The error is ignored
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) The error is caught in the catch block
</ul>
</details>


**55. What will console.log(x); inside a try block with no catch or finally do?**
```js
a) Print undefined
b) Print null
c) Throw a ReferenceError
d) Nothing
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) Throw a ReferenceError
</ul>
</details>


**56. Which method is used to generate a custom error?**
```js
a) throw new Error()
b) console.error()
c) generateError()
d) raiseError()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) throw new Error()
</ul>
</details>


**57. What will finally do in a try-catch-finally block?**
```js
a) Execute only if no error occurs
b) Execute only if an error occurs
c) Always execute
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) Always execute
</ul>
</details>


**58. OOP (Object-Oriented Programming) in JavaScript
Which keyword is used to create a class in JavaScript?**
```js
a) class
b) function
c) Class
d) new Class

```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) class
</ul>
</details>

**59. What is the purpose of the constructor method in a class?**
```js
a) To create private variables
b) To initialize object properties
c) To call another class
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) To initialize object properties
</ul>
</details>



**60. Which keyword is used for inheritance in JavaScript?**
```js
a) implements
b) extends
c) inherits
d) prototype
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) extends
</ul>
</details>



**61. Which method in a class is used to call the parent class constructor?**
```js
a) parent()
b) super()
c) this()
d) constructor()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) super()
</ul>
</details>


**62 Which statement about JavaScript classes is true?**
```js
a) They support multiple inheritance
b) They are syntactic sugar over prototypes
c) They can be redeclared
d) They do not support inheritance
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) They are syntactic sugar over prototypes
</ul>
</details>


**63 Web APIs & Asynchronous JavaScript**
```js
Which API is used for making HTTP requests in JavaScript?
a) XMLHttpRequest
b) Fetch API
c) Axios
d) All of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) All of the above
</ul>
</details>


**64. Which method sends a GET request using Fetch API?** 
```js
a) fetch(url)
b) fetch(url, { method: 'GET' })
c) Both a and b
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) Both a and b
</ul>
</details>


**65. What does navigator.geolocation.getCurrentPosition() do?**
```js
a) Gets user’s IP address
b) Gets user’s location
c) Opens a Google Maps page
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Gets user’s location
</ul>
</details>


**66. Which storage API stores data persistently?**
```js
a) localStorage
b) sessionStorage
c) cookies
d) All of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) localStorage
</ul>
</details>


**67. How can you set an interval in JavaScript?**
```js
a) setTimeout()
b) setInterval()
c) setRepeat()
d) Interval()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) setInterval()
</ul>
</details>



**68 Which method removes an element from an array?**
```js
a) splice()
b) slice()
c) remove()
d) delete()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) splice()
</ul>
</details>


**69. Which JavaScript engine is used in Google Chrome?**
```js
a) SpiderMonkey
b) V8
c) Chakra
d) Nitro
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) V8
</ul>
</details>

**70. Which method converts a string into a number?**
```js
a) parseInt()
b) Number()
c) + (unary plus)
d) All of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) All of the above
</ul>
</details>


** 71. Which function generates a random number between 0 and 1?**
```js
a) Math.random()
b) random()
c) generateRandom()
d) Math.rand()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) Math.random()
</ul>
</details>



** 72. Which of the following is a falsy value in JavaScript?**
```js
a) "false"
b) "0"
c) undefined
d) "undefined"
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) undefined
</ul>
</details>


**73 What will console.log([] == false); return?**
```js
a) true
b) false
c) undefined
d) Error
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) true
</ul>
</details>



**74. Which of the following is NOT a primitive data type in JavaScript?**
```js
a) Number
b) String
c) Object
d) Symbol
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) Object
</ul>
</details>

**75 How do you deep clone an object in JavaScript?**
```js
a) Object.assign({}, obj)
b) JSON.parse(JSON.stringify(obj))
c) obj.clone()
d) obj.copy()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) JSON.parse(JSON.stringify(obj))
</ul>
</details>


**76. What is the output of console.log(2 + "2" - 1);?**
```js
a) "21"
b) 21
c) "22"
d) 1
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) 21
</ul>
</details>



**77. Which method is used to filter elements from an array?**
```js
a) map()
b) filter()
c) reduce()
d) slice()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) filter()
</ul>
</details>



**78 Which function combines array elements into a single value?**
```js
a) reduce()
b) map()
c) join()
d) concat()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) reduce()
</ul>
</details>



**79. What does the following code return?**
```js
console.log([1, 2, 3].map(num => num * 2));
```
```js
a) [2, 4, 6]
b) [1, 4, 9]
c) [1, 2, 3]
d) [2, 3, 4]
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) [2, 4, 6]
</ul>
</details>


**80. Which of the following is NOT an immutable operation?***
```js
a) map()
b) filter()
c) splice()
d) concat()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) splice()
</ul>
</details>


**81. What is the event loop in JavaScript?**
```js
a) A process that handles function calls
b) A mechanism that allows async operations
c) A feature that prevents infinite loops
d) A method to execute code
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) A mechanism that allows async operations
</ul>
</details>


**82. Which of the following executes first in the event loop?**
```js
a) setTimeout()
b) setInterval()
c) Promise.resolve().then()
d) console.log()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) console.log()
</ul>
</details>



**83. Which queue does setTimeout() use in JavaScript?**
```js
a) Microtask queue
b) Callback queue
c) Event loop queue
d) Execution stack
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Callback queue
</ul>
</details>


**84. What will be the output of this code?**
```js
console.log("A");
setTimeout(() => console.log("B"), 0);
console.log("C");
```
```js
a) A B C
b) A C B
c) B A C
d) C A B
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) A C B
</ul>
</details>

**85. Which of the following is a best practice in JavaScript?**
```js
a) Using == instead of ===
b) Avoiding global variables
c) Using var instead of let
d) Nesting loops as deep as possible
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Avoiding global variables
</ul>
</details>


**86. What does "debouncing" do in JavaScript?**
```js
a) Delays function execution until a pause in events
b) Executes a function immediately
c) Runs a function continuously
d) None of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) Delays function execution until a pause in events
</ul>
</details>


**87. What does "throttling" do?**
```js
a) Executes a function only at fixed intervals
b) Prevents a function from running
c) Removes unnecessary function calls
d) Stops event propagation
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) Executes a function only at fixed intervals
</ul>
</details>


**88. Which of the following improves JavaScript performance?**
```js
a) Minifying JavaScript files
b) Using lazy loading
c) Avoiding unnecessary DOM manipulations
d) All of the above
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) All of the above
</ul>
</details>


**89. What is the best way to check if a variable is null or undefined?**
```js
a) if (x == null)
b) if (typeof x === "null")
c) if (x === null || x === undefined)
d) if (x == undefined)
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) if (x === null || x === undefined)
</ul>
</details>


**90. What does document.createElement('div') do?**
```js
a) Creates and appends a div
b) Creates a div but does not append it
c) Selects an existing div
d) Deletes all div elements
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Creates a div but does not append it
</ul>
</details>


**91. Which API is used to create animations in JavaScript?**
```js
a) WebGL
b) requestAnimationFrame()
c) animateCSS()
d) window.setInterval()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) requestAnimationFrame()
</ul>
</details>



**92. Which function removes whitespace from both ends of a string?**
```js
a) trim()
b) slice()
c) removeSpace()
d) strip()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) trim()
</ul>
</details>


**93. Which method removes the last element from an array?**
```js
a) pop()
b) shift()
c) splice()
d) removeLast()
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) pop()
</ul>
</details>

**94. What is the output of the following code?**
```js
console.log(myFunc);
function myFunc() {
    return "Hello";
}
```
```
A) undefined
B) ReferenceError: myFunc is not defined
C) [Function: myFunc]
D) TypeError: myFunc is not a function

```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: c) ƒ myFunc() { return "Hello"; }
</ul>
</details>

**95. Which of the following is an example of a higher-order function?**
```js
a) A function that returns another function
b) A function with a return type of void
c) A function that has a loop inside
d) A function that only contains if-else statements
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) A function that returns another function
</ul>
</details>

**96. Which method is used to handle asynchronous functions in JavaScript?**
```js
a) setTimeout()
b) Promise.then()
c) async/await
d) All of the above
```

<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) All of the above
</ul>
</details>

 **97. Which of the following is NOT true about closures?**
 ```js
 a) A closure allows a function to retain access to variables from its outer scope.
b) Closures are created every time a function is invoked.
c) Closures help in data encapsulation.
d) Closures cannot access global variables.
 ```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: d) Closures cannot access global variables.

</ul>
</details>

**98. What will be the output of the following code?**
```js
const obj = {
    value: 42,
    getValue: () => {
        return this.value;
    }
};
console.log(obj.getValue());
```
```js
a) 42
b) undefined
c) ReferenceError
d) null
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) undefined
</ul>
</details>

**99 What will be the output of the following asynchronous function?**
```js
async function foo() {
    return "Hello";
}
console.log(foo());
```
```js
a) "Hello"
b) Promise { "Hello" }
c) undefined
d) Error
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: b) Promise { "Hello" }
</ul>
</details>

**100. What is currying in JavaScript?**
```js
a) A technique where a function is transformed into a sequence of unary (one-argument) functions.
b) A method to execute functions asynchronously.
c) A way to cache function results for optimization.
d) A technique to convert a function into a class.
```
<details>
	<summary><b>View Answer</b></summary><ul>
Answer: a) A technique where a function is transformed into a sequence of unary functions.	
</ul>
</details>

