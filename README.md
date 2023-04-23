# JAVASCRIPT
1. Get user input using prompt(“Enter your age:”). If user is 18 or older , give feedback: 'You are old enough to drive' but if not 18 give another feedback stating to wait for the number of years he needs to turn 18. 

Enter your age: 30

you are old enough to drive.

Enter your age:15

You are left with 3 years to drive
```
#solution program
var a = prompt("Enter your age:");
if(a>=18)
{
    console.log("you are old enough to drive.")
}
else
{
    a = 18-a;
    console.log("You are left with",a," years to drive")
}
```
## OUTPUT
![image](https://user-images.githubusercontent.com/94372294/233849620-4b074cb9-83f8-448a-aa25-4c07b8a961f5.png)
<br>
<br>
<br>
2. Compare the values of myAge and yourAge using if … else. Based on the comparison and log the result to console stating who is older (me or you). Use prompt(“Enter your age:”) to get the age as input.

Enter your age: 30

You are 5 years older than me
```
#solution program
var me = prompt("Enter my age");
var you = prompt("Enter your age");
if(me>you)
{
    me = me-you;
    console.log("I am",me, "years older than you")
}
else
{
    you = you-me;
    console.log("You are" ,you, "years older than me")
}
```
## OUTPUT :
![image](https://user-images.githubusercontent.com/94372294/233850023-3da93315-a0d2-4696-b3de-112e4e06f78f.png)
<br>
<br>
<br>
3. Even numbers are divisible by 2 and the remainder is zero. How do you check, if a number is even or not using JavaScript?

Enter a number: 2

2 is an even number

Enter a number: 9
```
var num = prompt("Enter a number");
if(num%2==0)
{
    console.log(num,"is an even number")
}
else
{
    console.log(num,"is an odd number")
}
```
## OUTPUT :
![image](https://user-images.githubusercontent.com/94372294/233850290-ccd4b48c-27c2-4a1c-afb2-2880182cc1af.png)




















