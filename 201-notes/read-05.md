
# Class 05

### Code Challenge

```
// write a for loop that puts the number 1 - 10 in the console.log
for(let i = 1; i <= 10; i++) {
  console.log(i);
}

// write a for loop that puts the number 10-1 in the console.log
for(let i = 10; i >= 1; i--) {
  console.log(i);
}


let myFightMoves = ["Jab", "Elbow", "Knee", "Left Hook", "Right Hook", "Kick", "Guillotine"]

// write a for loop than console logs all the even number between 0 - 20
for(let i = 0; i <= myFightMoves.length; i = i + 2) {
  console.log(myFightMoves[i])
}

```
= This is assigning a value to something: Example let myNumber = 5

== is something equal to something else (== does not care what type something is. Example the number 5 the same as the string "5")//
Example: myNumber == "5" this is ok.  

=== this means strictly equal it means the types have to match so 5 is 5 but 5 is not "5" as "5" is a sentence not a number.

## css selectors

Putting a . infront of the class name means you are selecting a class.  
Example.

```
 <h1 class="heading">This is a heading<h1>
 
 <style>
  .heading{
    color: red;
  }
 </style>
 
```

putting a # infront of something means you are selecting an id. 

```
 <h1 id="heading">This is a heading<h1>
 
 <style>
  #heading{
    color: red;
  }
 </style>
 
```










