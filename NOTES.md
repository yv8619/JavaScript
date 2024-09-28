# async function
async function function_name() {
  
}

# await keyword
The await keyword can only be used inside async functions. It pauses the execution of the async function and waits for the promise to resolve or reject before continuing.
async function function_name() {
  const result = await someAsyncFunction();
}


# Declarative function ( function with a name )
function hello() {
console.log("welcome")
}

# Declarative function with arguments ( function with a name )
function hello(name) {
console.log(name)
}

# Declarative function with return 
function multiple(number) {
let result = number*2
return result
}

# Anonymous function ( function w.o a name ), should be assigned to a variable
var greeting = function() {
console.log("welcome")
}


# arrow function, should be assigned to a variable
var greeting = () => {
console.log("welcome")
}

# import function
import { functionName } from '../path'

# import everything
import * as helper from '../path'
helper.multiple(5)

# export function. For fucntion to be visible across the project we use export keyword.
export function multiple()

# class
export class CustomerDetails {
  printName(firstname){
    console.log(firstname)
  }
}

# using class in another js file
import { CustomerDetails } from '../path';
var customerDetails = new CustomerDetails()
customerDetails.printName("yashu")
}  

# class, hide the class implementation in same file by creating instance in same file
class CustomerDetails {
  printName(firstname){
    console.log(firstname)
  }
}

var customerDetails = new CustomerDetails()






















