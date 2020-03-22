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

Using the same kind of logic that was in the example above, you can replace the string values in the array with objects that represent each teammate. It's still a collection of your teammates, but instead of simple string representations of each person, you now have object representations.

```js
// Array of objects
const teammateArray = [
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
	},
	{
		firstName: "Greg",
		lastName: "Killgrew"
	},
	{
		firstName: "Mary",
		lastName: "Thomas"
	}
]

// Blank string
const team = ""

// Iterate teammate name array
for (const teammateObject of teammateArray) {

	// Append to the team variable's value.
	// Use dot notation to access properties on objects.
	team += `
	Teammate: ${teammateObject.firstName} ${teammateObject.lastName}`
}

console.log(team)
/* 
Teammate: Jameka Williams
Teammate: Rose McCallister
Teammate: Martin Orodruin
Teammate: Greg Killgrew
Teammate: Mary Thomas
*/
```

## Exercise: Doctor's Office Schedule

The office manager of a doctor's office wants to provide a list each day that shows the name of each patient, and the time of their appointment. An array of objects is provided with some same patients represented an objects. Write a `for..of` loop that iterates the objects in the array, and then use dot notation to append the patient's full name, and the time of their appointment to the string value of the `schedule` variable.

#### Example output (yours will look different because the data is different)

Patient Nancy Johnson has an appointment at 9:30
Patient Clarrissa Ford has an appointment at 10:15
Patient Abigail Debrowski has an appointment at 11:00
Patient John Beury has an appointment at 1:20


```js
const makeSchedule = () => {
	const patients = [
		{
			firstName: "MaryBeth",
			lastName: "Rodriguez",
			appointment: "8:45"
		},
		{
			firstName: "Chase",
			lastName: "Freely",
			appointment: "9:15"
		},
		{
			firstName: "Calvin",
			lastName: "Murray",
			appointment: "10:55"
		}
		{
			firstName: "Lorena",
			lastName: "Rodriguez",
			appointment: "2:20"
		}
	]
}
```

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0NDEwNjQ4OTgsNzMwOTk4MTE2XX0=
-->