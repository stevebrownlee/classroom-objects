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
	yearsOfService: 10,
	emtCertification: true,
	paramediaCertification: true,
	firefighterCertification: true
}
```

Now some firefighters.

```js
const matthew = {
	firstName: "Samantha",
	lastName: "Robinson",
	yearsOfService: 10,
	emtCertification: true,
	paramediaCertification: true,
	firefighterCertification: true
}

const jamal = {
	firstName: "Samantha",
	lastName: "Robinson",
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
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTcxMjc4ODYyNiwtMjA4ODc0NjYxMiw3Mz
A5OTgxMTZdfQ==
-->