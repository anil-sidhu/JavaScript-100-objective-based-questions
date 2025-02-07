# JavaScript-100-objective-based-questions


**1. Can we connect JavaScript Directly with Actual Database with reason ?**
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
c) var  user={name:'Anil'}; Object.freeze(obj);
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


Control Flow & Loops
Which loop is guaranteed to execute at least once?
a) for loop
b) while loop
c) do-while loop
d) None of the above
Answer: c) do-while loop

What will break statement do in a loop?
a) Exit the loop
b) Skip the current iteration
c) Stop the script execution
d) Throw an error
Answer: a) Exit the loop

Which keyword is used to skip an iteration in a loop?
a) break
b) continue
c) skip
d) pass
Answer: b) continue

What will console.log(typeof NaN); print?
a) "number"
b) "NaN"
c) "undefined"
d) "object"
Answer: a) "number"

Which statement will correctly check if x is null?
a) if (x = null)
b) if (x === null)
c) if (x == undefined)
d) if (x === undefined)
Answer: b) if (x === null)

Functions & Scope
What will console.log(typeof function(){}); return?
a) "function"
b) "object"
c) "undefined"
d) "null"
Answer: a) "function"

Which keyword is used to define a function?
a) function
b) define
c) def
d) method
Answer: a) function

What is the default return value of a function in JavaScript if no return statement is used?
a) null
b) undefined
c) false
d) 0
Answer: b) undefined

Which type of function executes immediately after its definition?
a) Anonymous function
b) Named function
c) IIFE (Immediately Invoked Function Expression)
d) Arrow function
Answer: c) IIFE

What will console.log(x); let x = 5; output?
a) 5
b) undefined
c) ReferenceError
d) NaN
Answer: c) ReferenceError

Objects & Arrays
How do you create an object in JavaScript?
a) let obj = {};
b) let obj = new Object();
c) Both a and b
d) None of the above
Answer: c) Both a and b

How do you access a property in an object?
a) obj[property]
b) obj.property
c) Both a and b
d) None of the above
Answer: c) Both a and b

Which method is used to add a new element at the end of an array?
a) push()
b) pop()
c) shift()
d) unshift()
Answer: a) push()

What will console.log([1,2,3].length); return?
a) 2
b) 3
c) 4
d) undefined
Answer: b) 3

How do you remove the last element from an array?
a) pop()
b) shift()
c) unshift()
d) slice()
Answer: a) pop()



ES6 Features

Which keyword allows block-scoped variable declarations?
a) var
b) let
c) const
d) Both b and c
Answer: d) Both b and c

Which of the following is true about const variables?
a) Their values cannot be changed
b) They cannot be reassigned
c) They are always immutable
d) All of the above
Answer: b) They cannot be reassigned

What is the output of console.log(typeof([]));?
a) "object"
b) "array"
c) "undefined"
d) "null"
Answer: a) "object"

What is a template literal in JavaScript?
a) A type of array
b) A string enclosed in backticks (` `)
c) A special function
d) A new ES6 data type
Answer: b) A string enclosed in backticks (` `)

What will console.log(..."Hello"); output?
a) "H e l l o"
b) ["H", "e", "l", "l", "o"]
c) Syntax Error
d) undefined
Answer: a) "H e l l o"

Arrow Functions & Spread/Rest Operators
How do you define an arrow function?
a) const add = (a, b) => a + b;
b) const add = function(a, b) { return a + b; };
c) Both a and b
d) None of the above
Answer: a) const add = (a, b) => a + b;

What does the spread operator ... do in JavaScript?
a) Combines arrays
b) Expands iterable elements
c) Copies objects
d) All of the above
Answer: d) All of the above

What will console.log([...new Set([1, 2, 2, 3])]); return?
a) [1, 2, 3]
b) [1, 2, 2, 3]
c) Set {1, 2, 3}
d) {1, 2, 3}
Answer: a) [1, 2, 3]

Which statement about arrow functions is true?
a) They do not bind this
b) They can be used as constructors
c) They have a prototype property
d) They support arguments keyword
Answer: a) They do not bind this

Which of the following correctly uses the rest operator?
a) function sum(...nums) { return nums.reduce((a, b) => a + b, 0); }
b) function sum(nums...) { return nums.reduce((a, b) => a + b, 0); }
c) function sum([...nums]) { return nums.reduce((a, b) => a + b, 0); }
d) None of the above
Answer: a) function sum(...nums) { return nums.reduce((a, b) => a + b, 0); }

Promises & Async/Await
What is the purpose of JavaScript Promises?
a) Handle synchronous code
b) Handle asynchronous operations
c) Block execution until resolved
d) Replace all callbacks
Answer: b) Handle asynchronous operations

Which state is NOT valid for a Promise?
a) Pending
b) Fulfilled
c) Rejected
d) Running
Answer: d) Running

How do you handle a rejected Promise?
a) .catch()
b) .then()
c) try...catch
d) Both a and c
Answer: d) Both a and c

What is the output of Promise.resolve(5).then(console.log);?
a) 5
b) Promise { 5 }
c) undefined
d) Error
Answer: a) 5

Which keyword is used to pause an async function execution?
a) async
b) await
c) defer
d) then
Answer: b) await

DOM Manipulation & Events
Which method selects an element by ID?
a) document.getElementByClass()
b) document.getElementById()
c) document.querySelectorAll()
d) document.selectById()
Answer: b) document.getElementById()

What does document.querySelectorAll(".class") return?
a) A NodeList
b) An array
c) A single element
d) Undefined
Answer: a) A NodeList

Which event is triggered when an input field loses focus?
a) click
b) blur
c) focus
d) change
Answer: b) blur

Which method adds an event listener to an element?
a) element.addEventListener()
b) element.attachEvent()
c) element.onEvent()
d) element.setEventListener()
Answer: a) element.addEventListener()

What does event.preventDefault() do?
a) Stops the default action of an event
b) Stops event propagation
c) Prevents event from being attached
d) None of the above
Answer: a) Stops the default action of an event

Miscellaneous
What is localStorage used for?
a) Storing session data
b) Storing data persistently in the browser
c) Making API requests
d) Caching images
Answer: b) Storing data persistently in the browser

Which method converts a JavaScript object into a JSON string?
a) JSON.stringify()
b) JSON.parse()
c) toJSON()
d) parseJSON()
Answer: a) JSON.stringify()

What will console.log(parseInt("10px")) return?
a) 10
b) NaN
c) "10px"
d) Error
Answer: a) 10

Which method executes a function repeatedly with a time interval?
a) setInterval()
b) setTimeout()
c) repeat()
d) setLoop()
Answer: a) setInterval()

How do you check if a variable is an array?
a) typeof x === "array"
b) x.isArray()
c) Array.isArray(x)
d) x instanceof Object
Answer: c) Array.isArray(x)



Closures & Hoisting
What is a closure in JavaScript?
a) A function inside another function that has access to its parent’s scope
b) A block of code that runs automatically
c) A way to define private variables
d) Both a and c
Answer: d) Both a and c

Which of the following is true about closures?
a) Closures have access to their own scope
b) Closures have access to their parent function's scope
c) Closures have access to global scope
d) All of the above
Answer: d) All of the above

What will this code output?

js
Copy
Edit
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
a) 1 2
b) 0 1
c) 1 1
d) Error
Answer: a) 1 2

Which statement about var and let is true?
a) Both are function-scoped
b) var is function-scoped, let is block-scoped
c) Both are block-scoped
d) var allows redeclaration, let doesn’t
Answer: b) var is function-scoped, let is block-scoped

What will console.log(x); var x = 10; output?
a) 10
b) undefined
c) ReferenceError
d) NaN
Answer: b) undefined

Error Handling
Which statement is used for error handling in JavaScript?
a) try...catch
b) throw
c) finally
d) All of the above
Answer: d) All of the above

What happens if an error occurs inside the try block?
a) The script stops execution
b) The error is caught in the catch block
c) The script crashes
d) The error is ignored
Answer: b) The error is caught in the catch block

What will console.log(x); inside a try block with no catch or finally do?
a) Print undefined
b) Print null
c) Throw a ReferenceError
d) Nothing
Answer: c) Throw a ReferenceError

Which method is used to generate a custom error?
a) throw new Error()
b) console.error()
c) generateError()
d) raiseError()
Answer: a) throw new Error()

What will finally do in a try-catch-finally block?
a) Execute only if no error occurs
b) Execute only if an error occurs
c) Always execute
d) None of the above
Answer: c) Always execute

OOP (Object-Oriented Programming) in JavaScript
Which keyword is used to create a class in JavaScript?
a) class
b) function
c) prototype
d) object
Answer: a) class

What is the purpose of the constructor method in a class?
a) To create private variables
b) To initialize object properties
c) To call another class
d) None of the above
Answer: b) To initialize object properties

Which keyword is used for inheritance in JavaScript?
a) implements
b) extends
c) inherits
d) prototype
Answer: b) extends

Which method in a class is used to call the parent class constructor?
a) parent()
b) super()
c) this()
d) constructor()
Answer: b) super()

Which statement about JavaScript classes is true?
a) They support multiple inheritance
b) They are syntactic sugar over prototypes
c) They can be redeclared
d) They do not support inheritance
Answer: b) They are syntactic sugar over prototypes

Web APIs & Asynchronous JavaScript
Which API is used for making HTTP requests in JavaScript?
a) XMLHttpRequest
b) Fetch API
c) Axios
d) All of the above
Answer: d) All of the above

Which method sends a GET request using Fetch API?
a) fetch(url)
b) fetch(url, { method: 'GET' })
c) Both a and b
d) None of the above
Answer: c) Both a and b

What does navigator.geolocation.getCurrentPosition() do?
a) Gets user’s IP address
b) Gets user’s location
c) Opens a Google Maps page
d) None of the above
Answer: b) Gets user’s location

Which storage API stores data persistently?
a) localStorage
b) sessionStorage
c) cookies
d) All of the above
Answer: a) localStorage

How can you set an interval in JavaScript?
a) setTimeout()
b) setInterval()
c) setRepeat()
d) repeatInterval()
Answer: b) setInterval()

Miscellaneous
Which method removes an element from an array?
a) splice()
b) slice()
c) remove()
d) delete()
Answer: a) splice()

What does typeof NaN return?
a) "NaN"
b) "undefined"
c) "number"
d) "object"
Answer: c) "number"

Which JavaScript engine is used in Google Chrome?
a) SpiderMonkey
b) V8
c) Chakra
d) Nitro
Answer: b) V8

Which method converts a string into a number?
a) parseInt()
b) Number()
c) + (unary plus)
d) All of the above
Answer: d) All of the above

Which function generates a random number between 0 and 1?
a) Math.random()
b) random()
c) generateRandom()
d) Math.rand()
Answer: a) Math.random()


Which of the following is a falsy value in JavaScript?
a) "false"
b) "0"
c) undefined
d) "undefined"
Answer: c) undefined

What will console.log([] == false); return?
a) true
b) false
c) undefined
d) Error
Answer: a) true

Which of the following is NOT a primitive data type in JavaScript?
a) Number
b) String
c) Object
d) Symbol
Answer: c) Object

How do you deep clone an object in JavaScript?
a) Object.assign({}, obj)
b) JSON.parse(JSON.stringify(obj))
c) obj.clone()
d) obj.copy()
Answer: b) JSON.parse(JSON.stringify(obj))

What is the output of console.log(2 + "2" - 1);?
a) "21"
b) 21
c) "22"
d) 1
Answer: b) 21

Functional Programming
Which method is used to filter elements from an array?
a) map()
b) filter()
c) reduce()
d) slice()
Answer: b) filter()

Which function combines array elements into a single value?
a) reduce()
b) map()
c) join()
d) concat()
Answer: a) reduce()

Which method creates a new array with transformed values?
a) map()
b) filter()
c) reduce()
d) splice()
Answer: a) map()

What does the following code return?

js
Copy
Edit
console.log([1, 2, 3].map(num => num * 2));
a) [2, 4, 6]
b) [1, 4, 9]
c) [1, 2, 3]
d) [2, 3, 4]
Answer: a) [2, 4, 6]

Which of the following is NOT an immutable operation?
a) map()
b) filter()
c) splice()
d) concat()
Answer: c) splice()
Event Loop & Asynchronous JavaScript
What is the event loop in JavaScript?
a) A process that handles function calls
b) A mechanism that allows async operations
c) A feature that prevents infinite loops
d) A method to execute code
Answer: b) A mechanism that allows async operations

Which of the following executes first in the event loop?
a) setTimeout()
b) setInterval()
c) Promise.resolve().then()
d) console.log()
Answer: d) console.log()

Which queue does setTimeout() use in JavaScript?
a) Microtask queue
b) Callback queue
c) Event loop queue
d) Execution stack
Answer: b) Callback queue

What will be the output of this code?

js
Copy
Edit
console.log("A");
setTimeout(() => console.log("B"), 0);
console.log("C");
a) A B C
b) A C B
c) B A C
d) C A B
Answer: b) A C B

Which of the following runs immediately after the main execution?
a) setTimeout()
b) setImmediate()
c) process.nextTick() (Node.js)
d) requestAnimationFrame()
Answer: c) process.nextTick() (Node.js)
Best Practices & Optimization
Which of the following is a best practice in JavaScript?
a) Using == instead of ===
b) Avoiding global variables
c) Using var instead of let
d) Nesting loops as deep as possible
Answer: b) Avoiding global variables

What does "debouncing" do in JavaScript?
a) Delays function execution until a pause in events
b) Executes a function immediately
c) Runs a function continuously
d) None of the above
Answer: a) Delays function execution until a pause in events

What does "throttling" do?
a) Executes a function only at fixed intervals
b) Prevents a function from running
c) Removes unnecessary function calls
d) Stops event propagation
Answer: a) Executes a function only at fixed intervals

Which of the following improves JavaScript performance?
a) Minifying JavaScript files
b) Using lazy loading
c) Avoiding unnecessary DOM manipulations
d) All of the above
Answer: d) All of the above

What is the best way to check if a variable is null or undefined?
a) if (x == null)
b) if (typeof x === "null")
c) if (x === null || x === undefined)
d) if (x == undefined)
Answer: c) if (x === null || x === undefined)

Miscellaneous Advanced Questions
What does document.createElement('div') do?
a) Creates and appends a div
b) Creates a div but does not append it
c) Selects an existing div
d) Deletes all div elements
Answer: b) Creates a div but does not append it

Which API is used to create animations in JavaScript?
a) WebGL
b) requestAnimationFrame()
c) animateCSS()
d) window.setInterval()
Answer: b) requestAnimationFrame()

Which of the following is true for the this keyword in arrow functions?
a) It binds to the global object
b) It binds to the enclosing lexical context
c) It binds to the calling object
d) It refers to the function itself
Answer: b) It binds to the enclosing lexical context

Which function removes whitespace from both ends of a string?
a) trim()
b) slice()
c) removeSpace()
d) strip()
Answer: a) trim()

Which method removes the last element from an array?
a) pop()
b) shift()
c) splice()
d) removeLast()
Answer: a) pop()
