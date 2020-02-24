## Objects Representing Things

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

Some of the object represent the people, and some objects represent buildings. Therefore, the properties vary. Each objec


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTA1NDU1NjQyNywtMjA4ODc0NjYxMiw3Mz
A5OTgxMTZdfQ==
-->