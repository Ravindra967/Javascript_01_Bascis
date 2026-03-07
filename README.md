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

“What is forEach?”

	Answer:
	
	forEach is an array method in JavaScript that executes a function once for each element in the array. It is mainly used to perform operations like printing, updating values, or calling functions for each item.
	
	🚀 Final Real Life Meaning (Super Simple)
	
	forEach() means:
	
	👉 “Take each item from the list and do something.”


	TCS   DT20267905879

forEach:

	let numbers = [1,2,3,4,5];
	
	let sum = 0;
	
	function adder(number){
		sum += number;
	}
	
	numbers.forEach(adder);
	console.log(sum);


Map() function:

	The map() method create a new array populated with the results of calling a provided function on element in the calling array.
	
	let numbers = [1,2,3,4,5];
	let double = numbers.map((num) => num*2);
	console.log(double);
	
	let numbers = [1,2,3,4];
	let multi = numbers.map((num) => num**10);
	console.log(mutli);
	
	const numbers = [12,14,55];
	
	function myFunction(num){
		return num*10;
	}
	
	const newArr = numbers.map(myFunction);
	console.log(newArr);
	

instead forEach we using the map() function.



filter():
	
	The filter() method is a built-in array method in javascript that allows you to create a new array containing elements that pass a certain condition. It provides a clean and concise way to filter out elements from an array based on a specified criteria.
	
	const names = ["ravi", "Rahul", "Ashok"];
	
	console.log(names.filter((name) => name.Length > 4));


reduce();

	Reduce keyword is used to reduce 







