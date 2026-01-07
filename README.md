1. Print even numbers 
console.log("Even Numbers:"); 
for (let i = 2; i <= 10; i += 2) { 
  console.log(i); 
} 
 
2. Print odd numbers 
console.log("Odd Numbers:"); 
for (let i = 1; i <= 10; i += 2) { 
  console.log(i); 
} 
 
 3. Print prime numbers 
console.log("Prime Numbers:"); 
for (let num = 2; num <= 20; num++) { 
  let isPrime = true; 
 
  for (let i = 2; i < num; i++) { 
    if (num % i === 0) { 
      isPrime = false; 
      break; 
    } 
  } 
 
  if (isPrime) { 
    console.log(num); 
  } 
} 
A 
 
4. For loop without curly braces 
console.log("For loop without curly braces:"); 
for (let i = 1; i <= 5; i++) 
  console.log(i); 
 
 5. i++ vs ++i in for loop (same behavior) 
console.log("i++ and ++i example:"); 
for (let i = 0; i < 3; ++i) { 
  console.log(i); 
} 
 
 6. Output of given code 
console.log("Output of given loop:"); 
for (let i = 1; i != 10; i += 2) { 
  console.log(i); 
} 
 
 7. Iterate array using for loop 
console.log("Array Iteration:"); 
let arr = ["HTML", "CSS", "JS"]; 
for (let i = 0; i < arr.length; i++) { 
  console.log(arr[i]); 
} 
 
 8. Sum of digits of 12345 
console.log("Sum of digits:"); 
let number = 12345; 
let sum = 0; 
let temp = number.toString(); 
 
for (let i = 0; i < temp.length; i++) { 
  sum += Number(temp[i]); 
} 
console.log(sum); 
 
 9. Loop using float 
console.log("Float Loop:"); 
for (let i = 0.1; i < 1; i += 0.2) { 
  console.log(i.toFixed(1)); 
} 
 
 10. Print name with asterisk 
console.log("Name with Asterisk:"); 
let name = "Ramji"; 
let result = ""; 
 
for (let i = 0; i < name.length; i++) { 
  result += name[i]; 
  if (i < name.length - 1) { 
    result += "*"; 
  } 
} 
console.log(result);
