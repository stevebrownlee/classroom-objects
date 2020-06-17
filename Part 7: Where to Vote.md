## Practice: Voting Booth Volunteers

In this exercise, you are going to access some nested object properties, and practice adding properties. Then you will use string interpolation to display the name, location, and manager of a voting booth location.

### Step 1

In the starter code provided, add a new property to the booth object after it is created. Do not modify the original object. 

* Property name should be `manager`
* Property value should be "Abigail Brown"

### Step 2

Use string interpolation to return the following string from the function. Remember to use the backticks and `${}` to inject variables into the string.

"Abigail Brown manages the Commonwealth Community Center at 70 Main Street in Nashville, TN"

## Next Steps

After you complete this exercise, go back to the classroom and open the Closet Inventory project to see how software developers use objects to display information in the browser.







```js
{
	name: "Commonwealth Community Center",
	address: {
		street: {
			number: 70,
			name: "Main Street"
		},
		city: "Nashville",
		state: "TN",
		zipCode: "37021"
	}
}
```

#### Starter Code

const votingBooth = () => {
    const votingLocation = {
    	name: "Commonwealth Community Center",
    	address: {
    		street: {
    			number: 70,
    			name: "Main Street"
    		},
    		city: "Nashville",
    		state: "TN",
    		zipCode: "37021"
    	}
    }
    // Add the new property
    votingLocation. = ""
    
    // Use string interpolation after the `return` keyword to produce the required string
    return 
}




<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg4OTk3Mzg4OF19
-->
