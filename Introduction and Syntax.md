## Representing Life as Objects

Software developers are paid to represent real-world things and processes in code. To represent things like people, tools, animals, flowers, businesses, and financial transactions, we use objects.

You can identify an object in JavaScript by a series of properties surround by curly braces `{` and `}`. Here's a simple object that represents this chapter.

```js
const objectsIntro = {
	site: "repl.it",
	classroom: "Objects",
	chapter: "Introduction and Syntax",
	audience: "Beginners",
	minutesToComplete: 4.25
}
```

A property on an object is comprised of a key and a value. You can think of them just like declaring a variable, but the syntax is slightly different, and the variable is now grouped together with other ones in the context of the object. 

```js
// Regular variable declarations
const firstName = "Michael"
const lastName = "McLenton"
const age = 25
const city = "Nashville"

// Same variables scoped to an object
const michael = {
	firstName: "Michael",
	lastName: "McLenton",
	age: 25,
	city: "Nashville"
}
```

You've replaced the `=` sign with a colon `:` for assigning a value to a variable. When a variable is defined this way - in the scope of an object - it's called a property. The variable name is now now called a key. The value is still called value. 

Here is an example of representing a book as an object in JavaScript.

```js
const book = {
	title: "Where the Wild Things Are",
	isbn: "0-06-025492-0",
	publisher: "Harper & Row",
	publicationDate: "1963",
	pages: 40
}
```

You can put as many properties on an object as you like

## Exercise: Your First Object


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwMTczNDA1NzEsLTY4NTYwMDAwOCw4OD
UwNDQyNTQsNzMwOTk4MTE2XX0=
-->