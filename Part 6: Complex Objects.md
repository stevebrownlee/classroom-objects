## Complex Objects That Contain Other Objects

Data structures can get even more complex when you are working with objects. Consider a dog and her favorite toy. You can represent the dog and the toy seperately.

```js
const gypsy = {
    name: "Gypsy",
    age: 5,
    breed: "Schnauzer",
    weight: 25
}

const favoriteToy = {
    brand: "Hasbro",
    name: "Mean Kitty",
    price: 8.99
}
```

You can also make the toy a property of the dog itself.

```js
const gypsy = {
    name: "Gypsy",
    age: 5,
    breed: "Schnauzer",
    weight: 25,
    favoriteToy: {
	    brand: "Hasbro",
	    name: "Mean Kitty",
	    price: 8.99
	}
}
```

You have an object contained within the scope of another object. To access the `price` property for the favorite toy, you have use the dot `.` character twice.

```js
const toyPrice = gypsy.favoriteToy.price
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExNTg1Mjg4MSw4ODg2MDM3NjUsMTkwNj
U1MDQyNl19
-->