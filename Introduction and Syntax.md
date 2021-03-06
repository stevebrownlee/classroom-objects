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

You can put as many properties on an object as you need to appropriately describe that object, and what you need to display to people who are viewing the information.

## Exercise: Your First Object

In the code editor, you will see some starter code. You only need to focus on the following code.

```js
/* Create your student object here */
const student = 
```

After the `student = `, your job is to create an object that represents a new student who is learning how to write software. The student should have the following properties.

* A name property with a value of "Jeremy Landy"
* A location property with a value of "Phoenix, AR"
* A gender property with value of "male"
* An age property with a value of 31

So you need the curly braces, and the properties. Leave the rest of the code unchanged.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1MzI2OTAzNTcsLTEzMDg4NTQxMjcsMT
E0MTYxMjQwMywtMjExMTc5MzM1NSwtMTgyNTI4MDMzOSwtNjg1
NjAwMDA4LDg4NTA0NDI1NCw3MzA5OTgxMTZdfQ==
-->