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

If you want the age of the dog, you only need one dot.

```js
const dogAge = gypsy.age
```

Again, to access the brand of the toy, you need two dots in order to get to the nested object.

```js
const toyBrand = gypsy.favoriteToy.brand
```

## Practice: Sales Associate Email

You work for a car dealership, and you want to get the email address of each sales associate. In the starter code provided, return the email address of the sales associate.


