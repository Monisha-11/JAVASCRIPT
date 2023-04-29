# JAVASCRIPT

## NAME : MONISHA T
## REGISTER NUMBER : 212221240029

```java
 1) Get user input using prompt(“Enter your age:”). If user is 18 or older , give feedback: 
 'You are old enough to drive' but if not 18 give another feedback stating to wait for the number of years he needs to turn 18. 

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
2) Compare the values of myAge and yourAge using if … else. Based on the comparison and log the result
to console stating who is older (me or you). Use prompt(“Enter your age:”) to get the age as input.

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









# WEBSITE USING HTML AND CSS

## NAME : Monisha T
## REGISTER NO : 212221240029

### PROGRAM 

```java
HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>webpage</title>
    <link rel="stylesheet" href="1.css"/>
</head>
<body>
    <div class="container">
        <div id="header">
            <div style="color:red ;font-size: 30px">BEST TUNING</div>
            <div style = "font-size: 30px"><a href="#"> Home</a></div>
            <div style = "font-size: 30px"><a href="#">Project</a></div>
            <div style = "font-size: 30px"><a href="#">Team</a></div>
            <div style = "font-size: 30px"><a href="#">Contact</a></div>
            <div style = "font-size: 30px"><button style="background-color: red;padding:8px;border-radius: 15px;"><a href="#">Book An Appointment</a></button>
        </div>
        
        
    </div>
    <center><img src="1.jpeg" height="500px" width="1000px;margin-top: 100px"></center>
    <div class="img">
        <p style="font-size:30px"><b><i>TUNING PERFECTION</i></b></p>
        <p style="font-size:30px"> in an upgrade that unlocks hidden<br/>potential of your car</p>
        <p style="font-size:20px"><a href="#">Explore more</a></p>
    </div>
    <img src="2.jpg" style="float:right;padding-left: 120px;">
    <div>
        <p style="color:white;padding-top: 50px;font-size: 25px;"><b>WHY DO YOU WANT IT?</b></p>
        <p style="color:white;font-size:60px">WHAT IS TUNING AND <br/>WHY DO YOU WANT IT?</p>
        <p style="text-align: justify;color:white;font-size:25px">Tuning is an upgrade to the software in the vehicle's computer.Custom software is installed that charges many parameters
        that control the way the engine operators. With proper tuning you can increase both power and fuel of economy.</p>
    </div>

    <img src="1.jpeg" height="500px" width="700px" style="float: left;padding-right:50px;">
    <div style="color:white;font-size: 20px;margin-bottom:100px;">
        <h3 style="font-size:30px"><b>ADVANTAGES</b></h3>
        <p style="font-size:50px">WHATCAN I EXPECT FROM TUNING?</p>
        <p style="text-align: justify;font-size:30px">What can I expect from Tuning?<br/>Through proper modification, it is possible to greatle increase the power output of the vehicle, while 
            at the same time omproving safety and longevity of the engine,drivability, and smoothness.
        </p>
        <div style="display: flex;">
            <h3 style="padding-right: 300px; font-size:30px">20-35 hp</h3>
            <h3 style="font-size:30px">35-50 hp</h3>
        </div>
        <div style="display: flex;">
            <h4 style="padding-right: 200px;font-size:30px">Roughly increase from <br/>a stage 1 tune</h4>
            <h4 style="font-size:30px">Roughly increase from <br/>a stage 2 tune</h4>
        </div>
    </div>
    <div id="footer">
        <div style="color:red ; font-size: 30px">BEST TUNING</div>
        <div style = "font-size: 30px"><a href="#">Home</a></div>
        <div style = "font-size: 30px"><a href="#">Project</a></div>
        <div style = "font-size: 30px"><a href="#">Team</a></div>
        <div style = "font-size: 30px"><a href="#">Contact</a></div>
        <div style="color:white ;font-size: 30px">&copy 2009 Best Tuning. All rights reserved.</div>
        <div style="font-size:40px"><a><b>f</b></a></div>
        <div style="font-size:40px"><a><b>in</b></a></div>
    </div>    
</body>
</html>

```
```java

css

body{
    background-color: black;
   margin:50px;
}

#header
{
    display:flex;
    justify-content:space-around;
}
a{
    color:white;
    
}
.img
{
    font-size:20px;
    color:white;
}
#footer
{
   display: flex;
   justify-content:space-around;
}

```
### OUTPUT

#### FRONT - PAGE
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/93427240/235308834-a011d8a3-5e00-4d1c-82f7-36805a026430.png">

#### MAIN - PAGE
<img width="1268" alt="image" src="https://user-images.githubusercontent.com/93427240/235308887-1a0f8d1a-c497-47cb-ad09-9c243db22848.png">

#### FOOTER

<img width="1250" alt="image" src="https://user-images.githubusercontent.com/93427240/235308957-193c452e-6ccc-4159-a3e7-683a49d17224.png">







