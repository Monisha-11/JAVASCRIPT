# JAVASCRIPT

## NAME : MONISHA T
## REGISTER NUMBER : 212221240029

```java
 1) Get user input using prompt(“Enter your age:”). If user is 18 or older , give feedback: 'You are old enough to drive' but if not 18 give another feedback stating to wait for the number of years he needs to turn 18. 

Enter your age: 30
you are old enough to drive.
Enter your age:15
You are left with 3 years to drive

PROGTRAM :-
var age = prompt("Enter your age:");
if (age >= 18)
{
  console.log("You are old enough to drive.");
}
else {
  var yearsLeft = 18 - age;
  console.log("You are left with " + yearsLeft + " years to drive.");
}

```
### OUTPUT :-

<img width="322" alt="image" src="https://user-images.githubusercontent.com/93427240/233376839-858789e3-3da4-42c8-ad70-03cc15c7f074.png">

```java
2) Compare the values of myAge and yourAge using if … else. Based on the comparison and log the result to console stating who is older (me or you). Use prompt(“Enter your age:”) to get the age as input.

Enter your age: 30

You are 5 years older than me

PROGRAM :-

var myAge = prompt("Enter My age: ");
var yourAge = prompt("Enter your age:");

if (yourAge > myAge)
{
   var a = yourAge - myAge;
  console.log("You are " + a + " years older than me");
} 
else if (yourAge < myAge)
{
    var b = myAge-yourAge;
  console.log("I am " + b + " years older than you");
} 
else {
  console.log("We are of the same age");
}

```
### OUTPUT :-
<img width="326" alt="image" src="https://user-images.githubusercontent.com/93427240/233378000-a7c2f7d1-0249-4b9a-a775-6c93df69075f.png">

```java
3) Even numbers are divisible by 2 and the remainder is zero. How do you check, if a number is even or not using JavaScript?

Enter a number: 2

2 is an even number

Enter a number: 9

3 is an Odd number

PROGRAM :-

var a = prompt("Enter Any Number: ");
if (a%2==0)
{
    console.log(+ a + " is an Even Number");
}
else
{
    console.log(+ a + " is an Odd Number");
}

```
### OUTPUT :-

<img width="304" alt="image" src="https://user-images.githubusercontent.com/93427240/233378985-370ce399-2742-4b39-a5f0-9558273d450c.png">

