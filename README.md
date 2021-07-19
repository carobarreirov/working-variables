# working-variables

The next step would be to go to the document you are working on, the second part of the platform, and read all the code once. So we can identify the lines commented on there is a // TODO. It is these blocks of text that will help us to go step by step to solve the exercise.



In the exercise you mention: Working With Variables Step 1, the following block of code is found.

/*Instructions

 - Greet your friend by printing a message to the console.

*/

//your code here


///////////////

function greetings() {

 //also your code here

 ///////////////

}


//leave this line unchanged to console log the results

console.log('results: ', greetings());


//don't change this line

if (typeof module !== 'undefined') {

 module.exports = greetings;

}


In this case we don't have the TODO like in other exercises but we have the //your code here hint. 

So we will start in line 5 and follow the Task Instructions that are in the "text" column in Next Tech. 



Task Instructions

In this activity, you will define a variable within a JavaScript function. You'll learn more about functions later. For now, we'll focus on variables.



To accomplish this task, you need to do the following:

Open the Variables-01 folder and add code to the variables01.js file to do the following:

Create a variable called myFriend using one of the variable declarations described above.
var myFriend 
Set the variable you created to contain your friend's name.
var myFriend = "Diego"
Note: You can change Diego for any name you want
Inside the greetings function, return the string: "Greetings [your-friend's-name]."
In this parte we are changing from line 5 to 9 to be inside the function greetings()
return `Greetings ${myFriend}!`
​

Those would be all steps for that exercise making our block of code look as the following: 

/*Instructions

 - Greet your friend by printing a message to the console.

*/

//your code here

var myFriend = "Diego"

///////////////

function greetings() {

 //also your code here

 return `Greetings ${myFriend}!`

 ///////////////

}


//leave this line unchanged to console log the results

console.log('results: ', greetings());


//don't change this line

if (typeof module !== 'undefined') {

 module.exports = greetings;

}
