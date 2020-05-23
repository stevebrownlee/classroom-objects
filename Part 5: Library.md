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

The starter code has two functions. The `bookAuthor()` function should return the last name of the author of a book. The `checkedInBy()`  function should return the last name of the librarian that checked the book in.

All you need to do is write the proper code after each `return` keyword to access the correct key on the objects.








