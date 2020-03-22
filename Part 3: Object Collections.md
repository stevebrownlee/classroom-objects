Introduction to array of objects

## Object Collections

If previous work in the Foundations Course, you learned how to store a collection of related data in an array and how to use iteration to do something with everything in the array.

Example, an array of your teammates's names can be joined together using a `for..of` loop, which iterates the array.

```js
// Array of strings
const names = ["Jameka", "Rose", "Martin", "Greg", "Mary"]

// Blank string
const team = ""

// Iterate teammate name array
for (const name of names) {
	// Append to the team variable's value
	team += `
	Teammate: ${name}`
}

console.log(team)
/* 
Teammate: Jameka
Teammate: Rose
Teammate: Martin
Teammate: Greg
Teammate: Mary
*/
```

In this exercise, you will be working with an array of objects. 

Using the same kind of logic that was in the example above, you can replace the string values in the array with objects that represent each teammate.

```js
// Array of strings
const names = [
	{
		firstName: "Jameka",
		lastName: "Williams"
	},
	{
		firstName: "Rose",
		lastName: "McCallister",
	},
	{
		firstName: "Martin",
		lastName: "Orodruin"
		

"Rose", "Martin", "Greg", "Mary"]

// Blank string
const team = ""

// Iterate teammate name array
for (const name of names) {
	// Append to the team variable's value
	team += `
	Teammate: ${name}`
}

console.log(team)
/* 
Teammate: Jameka
Teammate: Rose
Teammate: Martin
Teammate: Greg
Teammate: Mary
*/
```

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTQyODYwODA4Nyw3MzA5OTgxMTZdfQ==
-->