"# Javascript_01_Bascis" 
Basics
Variables - let const var
condtional statemets
objects
array
Strings
Funtios
Arrow Function
Tempalte Strings
Dafault function parameter
1.sync and async 
Map reduce
Filter


Http integration
Routing
Middleware
Api integration

Write a simple if else in javascript

example: 
function passwordcheck(pass){
	if (pass==8){
		return `strong password`
	}else{
	 return 'password should be 8 charcters'
  }
let pas = passwordcheck(3);
console.log(pas);

simple way
usig ternary operator ?

function passwordchecker(ps){
return pass===8 ? "password should be 8 character" : "Strong Password";
}

const res = passwordchecker(ps);
console.log(res);


for in loop:

let num = ['one', 'two', 'three'];
for (let index in num){
    console.log(`${index}:${num[index]}`)
}


for  of loop: it is iterbel the characters  in the string, object etc..

let name = 'hello';
for (let char of name){
 console.log(char);
 }
    console.log(char)
}

#for each it is iterarate by using the function
#Hooks #props #component
#Async #await




🔥 1️⃣ What is forEach()?

	forEach() is a method used to repeat something for every item inside an array.

Simple meaning:

👉 “For each item, do something.”

That’s it.

🔥 2️⃣ Important Rule

	⚠️ forEach() works only on ARRAYS.
	
	Example of array:
	
	let students = ["Ravi", "Priya", "Arun"];

3️⃣ Whole Array

	Rarely used, but possible.
	
	numbers.forEach(function(num, index, arr) {
	  console.log(arr);
	});
