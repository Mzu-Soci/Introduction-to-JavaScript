# Section - 9: Introduction-to-JavaScript ES6

- 101: Intro to JS
- 102: JS Alerts - Adding Behaviour to Websites
- 103: Data Types
- 104: JS Variables
- 105: JS Variables Exercise Start
- 106: JS Variables Exercise Solution
- 107: Naming and Naming Converntions for JS Variables
- 108: String Concatenation
- 109: String Lengths and Retrieving the Number of Characters
- 110: Slicing and Extracting Parts of a String
- 111: Challenge: Changing Casing in Text
- 112: Challenge: Changing String Casing Solution
- 113: Basic Arihmentic and the Modulo Operator in JS
- 114: Increment and Decrement Expressions
- Quiz: JS numbers quiz

/**
 * Welcome to the Stanford Karel IDE.
 * This is a free space for you to 
 * write any Karel program you want.
 **/
function main(){
   //your code here
   altBeeper();
   altBeeper();
   beepTurn();


}

function altBeeper() {
   putBeeper();
   move();
   move();
   }
   
function beepTurn(){
   putBeeper();
   turnLeft();
   move();
   turnLeft();
   move();
   }

function diagBeeper(){
   putBeeper();
   move();
   turnLeft();
   move();
   turnRight();
   }
   
function step4(){
   move();
   move();
   move();
   move();
   }

