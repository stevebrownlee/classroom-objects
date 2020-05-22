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
console.log(flower.species.idealCondition.clay)

> false
```

## Practice: Librarian and Book Author

The starter code has two functions. The `bookAuthor()` function should return the author of a book. The `checkedInBy()`  function should return which librari
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjI4OTEwNzczLDM0NzMyNDEzM119
-->