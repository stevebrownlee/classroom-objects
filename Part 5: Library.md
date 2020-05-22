## Libraries and Books

In this exercise, you are going to practice accessing properties on nested objects again. Remember that for each nested object, you need to use the dot `.` character to access it.

```js
const flower = {
	color: "Yellow",
	species: {
		name: "Tulip",
		rare: false,
		idealCondition: {
			shade: false,
			dailyWater: true,
			clay: false,
			soil: true
		}
	},
	price: 1.29,
	arrangements: ["Birthday", "Mother's Day"]
```

If you want to check if the ideal condition for a flower includes growing it in clay, you would write the following code.

```js
const clayFlower = flower.species.idealCondition.clay

// false
```

## Practice: Sales Associate Email

You work for a car dealership, and you want to get the email address of each sales associate. In the starter code provided, return the email address of the sales associate.


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTMxNDY5OTQyMywzNDczMjQxMzNdfQ==
-->