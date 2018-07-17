# Challenge 3

##  Even or Odd
Write a function called `isCharEven()` that takes a string and a character. Return `true` if the character's position in the alphabet divided by the index of the first instance of the character is even. Otherwise, return `false`.

If the string is empty, return  `null` .

## Reminders

 - You are only allowed to use the built-in methods of the `Math` object: round up when necessary.
 - Recall the notation for indexing characters of strings
 - You can refer to documentation if you get stuck:
	 - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String
	 - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array

## Example

    //input ('hello world!', 'w')

    function isCharEven(string, char) {
     // your code here
    }

    //output false

## Stretch Goals

 - Modify your function to accept two characters; account for the sum of their respective alphabetical position and index
