## Create function following below :</br>
add(a, b)</br>
subtract(a, b)</br>
multiply(a, b)</br>
divide(a, b)</br>

function add(a, b){
  return a + b
}
const result = add(10, 10)
console.log(result) // output: 20

function subtract(a, b){
  return a - b
}
const result = subtract(10, 10)
console.log(result) // output: 0

function multiply(a, b){
  return a * b
}
const result = multiply(10, 10)
console.log(result) // output: 100

function divide(a, b){
  return a / b
}
const result = divide(10, 10)
console.log(result) // output: 1

## -----another exercise Create Function Inform---</br>
console.log("Hi, my name is " + firstName + "I live in " + location + "and enjoy "+hobby);

function functionName(firstName,location,hobby) {
  console.log("Hi, my name is " + firstName + " I live in " + location + " and enjoy "+hobby);
}
functionName('Tay','Nan','Playing games');