Introduction to array of objects

## Object Collections

If previous work in the Foundations Course, you learned how to store a collection of related data in an array and how to use iteration to do something with everything in the array.

Example, an array of your teammates's names can be joined together using a `for..of` loop, which iterates the array.

```js
const names = ["Jameka", "Rose", "Martin", "Greg", "Mary"]
const team = ""

for (const name of names) {
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
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4MTI5NjE3Niw3MzA5OTgxMTZdfQ==
-->