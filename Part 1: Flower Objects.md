## Multiple Objects

Since software developers utilize objects to represent real-world things that need to be automated with software, it is critical to know that the properties of the "things" are. Consider an example where a fire chief needs to assign some firefighters to fire stations. What would need to be an object in this scenario.

1. An object representing each firefighter
2. An object representing each fire station
3. An object representing the fire chief

First, the fire chief.

```js
const fireChief = {
	firstName: "Samantha",
	lastName: "Robinson",
	yearsOfService: 13,
	emtCertification: true,
	paramediaCertification: true,
	firefighterCertification: true
}
```

Now some firefighters.

```js
const matthew = {
	firstName: "Matthew",
	lastName: "Ingersoll",
	yearsOfService: 4,
	emtCertification: false,
	paramediaCertification: true,
	firefighterCertification: true
}

const jamal = {
	firstName: "Jamal",
	lastName: "Ross",
	yearsOfService: 5,
	emtCertification: true,
	paramediaCertification: false,
	firefighterCertification: true
}

const erin = {
	firstName: "Erin",
	lastName: "McNamara",
	yearsOfService: 3,
	emtCertification: false,
	paramediaCertification: true,
	firefighterCertification: true
}
```

Now, two objects for the fire stations.

```js
const eastStation = {
	address: "1002 Main Street",
	squareFootage: 4720,
	kitchen: true,
	beds: true,
	showers: true
}

const northStation = {
	address: "9 Lighthouse Road",
	squareFootage: 3233,
	kitchen: false,
	beds: false,
	showers: true
}
```

## Different Properties

Some of the objects represent the people, and some objects represent buildings. Therefore, the properties vary. Each JavaScript object should have only the properties that describe the real-world object it is representing. The value of each property can be different, depending on the current state of the real-world object. Just because two objects represent the same kind of thing does not mean the property values will always match.

## Exercise: Flower Shop

In this exercise, you are going to create two objects that represent flowers - a Tulip and a Rose. The objects will be largely the same, but since roses have thorns and tulips do not, there will be a difference between the properties on each one. 

In the starter code in the editor, create two objects where you see the comments.

Both flower objects should have the following keys.

* `color`, which will be a string
* `stemLength`, which will be a number
* `growingSeason`, which will be a string like "Summer" or "Spring"

You can decide on the values for each of the properties.

On the rose object, provide the following additional property.

* `thorny` which will have the boolean value of `true`






```js
const createTulip = () => {
    // Complete your tulip object here.
    const tulip = {

	}
    
    
    return tulip
}

const createRose = () => {
    // Complete your rose object here.
    const rose = {
    
    }
    
    
    return daisy
}

```
<!--stackedit_data:
eyJoaXN0b3J5IjpbODMzMDY3NywyNjY5MDE4NDUsLTE5NjAzOD
UwOTAsLTcwNDc1NjE3MSwtMjA4ODc0NjYxMiw3MzA5OTgxMTZd
fQ==
-->