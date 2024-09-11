# Week-37-coding


/*
    Task: Example
*/
console.log("Task: Example");
const people = ["Tony", "Christian", "Håkon"]

for (let index = 0; index < people.length; index++) {
    let person = people[index];
    console.log(person);
}


/*
    Task: A
*/
console.log("Task: A");
for (let i = 0; i < 100; i++) {
    console.log("Debugging is like being a detective in a crime drama where you are also the murderer");
}


/*
    Task: B
*/
console.log("Task: B");

const max = 99;
for (let index = max; index > 0; index--) {  // Start from max and count down
    console.log(index + " bottles of soda on the shelf");
    console.log(index + " bottles of soda on the shelf");
    console.log("Take one down, pass it around, " + (index - 1) + " bottles of soda on the shelf");
    console.log("");  // Empty line for spacing
}

console.log("No more bottles of soda on the shelf");


/*
    Task: C 
*/
console.log("Task: C");
const gravity = 9.81;
const PI = 3.14;
const NumberOfPeople = 40;

console.log("Gravity is ", gravity);
console.log("PI is ", PI);
console.log("The number of people is ", NumberOfPeople);
/*
    Task: D
*/

console.log("Task: D");

function add(num1, num2) {
    return num1 + num2;
}
console.log("3 + 6 = " + add(3, 6));
console.log("5673 + 234 = " + add(5673, 234));

/*
    Task: E
*/
console.log("Task: E");
for (let i = people.length - 1; i >= 0; i--) {
    console.log(people[i]);
}


/*
    Task: F
*/
console.log("Task: F");
const phoneNumbers = ["+47 412 34 567", "+47 915 12 345", "+47 478 91 234"];
console.log(phoneNumbers[0]);
console.log(phoneNumbers[1]);
console.log(phoneNumbers[2]);

/*
    Task: G
*/
console.log("Task: G");
console.log(phoneNumbers[phoneNumbers.length - 1]);
/*
    Task: H
*/
console.log("Task: H");
let peopleNames = [["Christian", "Simonsen"], ["Tony", "Bergholtz"]];

for (let i = 0; i < peopleNames.length; i++) {
    console.log(peopleNames[i][1]);
}
