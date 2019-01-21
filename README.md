
# Quiz 4

01. Question 6 Explanation: The correct answer for question 6 is 
function sayHi() {
    document.getElementById("my-paragraph").innerHTML = "Hi, there!";
}
instead of the wrong answer I gave
(function sayHi() {
    document.getElementById("my-paragraph") = "Hi, there!";
})
because the function needs to know what to put in the <p></p> tag or the paragraph. You would need to do this with the .innerHTML element equaling to a value (82), text ("Hi, there!"), variable, or etc. and adding it in this case to document.getElementById("my-paragraph") or a variable, like p, assigned to document.getElementById("my-paragraph");. 

02. Question 7 Explanation: The correct answers is false, "", null, Nan, 0, and undefined. This is because JavaScript uniquely assigns everything an inherent boolean value. The inherent boolean values are truthy or falsey. JavaScript always assigns false, 0, '' or "", null or undefined, and NaN as falsey.

03. Question 8 Explanation: The correct answer is
let x;
x = 27;
because the you need to declare the variable and then assigns a value to it. You can't declare a variable and assigns the variable a value on the same line using the let keyword. 
(If this is not the right answer then I don't know. If it is correct, ignore this comment.)

04. Question 10 Explanation: The correct answer is null, string, number, object, symbol, boolean, and undefined. These are just the valid data types in JavaScript since JavaScript is a dynamically typed language and needs a lot of different ways to store different types of data.

# Quiz 5

01. Question 1 Explanation: The correct answer for the first if statement is a < b && a < c because the first if statement would say if a is less than b and c and then would console.log "we know for sure that a is the smallest of the three." which is logically true since a has to be smaller than b and c for the if statement to run and console log "we know for sure that a is the smallest of the three.". The correct answer for the second if statement is c > a || c > b because this says c has to be greater than a or b for the if statement to run and console log "we know for sure that c is not the smallest of the three." which is logically true then if we used c > a || c > b.

02. Question 4 Explanation: The correct answer for this is ==, !=, >=, <=, <, >, !==, and ===. These are the valid relational operators in JavaScript. These are tasked with comparing values or variables

03. Question 9 Explanation: The correct answer to this question is 
if (score >= 90) {
    letterGrade = "A";
} else if (score >= 80) {
    letterGrade = "B";
} else if (score >= 70) {
    letterGrade = "C";
} else if (score >= 60) {
    letterGrade = "D";
} else {
    letterGrade = "F";
}
because it is most simplest way to achieve the goal in the question. It achieves the goal like most of the other choices but it just uses the simple if, else if, and else statement to solve the problem unlike the switch statement, which is somewhat complex or the other complex ways or the wrong choice/answer to achieve the goal.

04. Question 11 Explanation: The correct answer to this question is 
1. Setup
2. Expression
3. Loop body
4. Update
5. Return to Step 2
because the syntax for a for loop is 
for (setup; expression; update) {
    // do stuff here
}
since the update statement updates the variable in the setup by your update value. After the for loop does the stuff in the {} brackets, it updates the variable by a certain value in the update segment. Then, it goes back into the parameters, the stuff in the parentheses, and checks if the expression is true or false. If the expression is true, it returns to step 2 and does the update and the loop body again and if the expression is false, it breaks out of the for loop. That is how for loops work.

05. Question 13 Explanation: The correct answer that I didn't select for this question is 
do {
   x++;
} while (x < 100);
because this do...while loop will terminate when x equals 100. This will happen because the do...while loop has one added to x in it. x will equal to 100 and make the conditional expression false and break out of the do...while loop at some point.

05. Question 15 Explanation: The correct answer to this question is 
for (let i = 0; i < 5; i++) {
    console.log(i);
}
because i = 0 and 0 is less than 5. This would allow the for loop to run and update itself and check itself. The for loop will terminate too when i = 5 after running the for loop and the update a few times. 

# Quiz 6

01. Question 1 Explanation: The correct answers is 
let difference = subtract(x, y);
console.log(difference); 
and 
console.log(subtract(x, y));
because both answers would use x and y to substitute a and b respectively and would return x - y when the function doMath() runs and does
let x = Math.random() * 100;
    let y = Math.random() * 50;
    
    let difference = subtract(x, y);
console.log(difference); 
or
console.log(subtract(x, y));
. This would call subtract to the console using the console.log function. These two answers are the mostly the same but console.log(subtract(x, y)); is condensed.

02. Question 2 Explanation: The correct answer I did not choice is 
I need to do chores, homework, and undefined... So busy!
because if c does not have a value to it and c is in a parameter in a function then when used in the function, it will be undefined. This is because c does not have a value assigned to it and that makes it undefined.

03. Question 6 Explanation: The correct answer to this question is "The parameters that did not receive arguments will be undefined." This is because one or more of the parameters does not have a variable or argument assigned to it, one of the parameters/variables will not have a value assigned to it and the parameters that did not receive arguments will be undefined.

04. Question 9 Explanation: The correct answers are the built-in functions prompt, alert, console.log. This is because you can add (//number, variable, or text in quotation marks) right after the built-in functions prompt, alert, console.log with no spaces.

05. Question 10 Explanation: The correct answer for this question is prompt. This is because prompt needs you to return a value like a number or words for the code or function to continue again.

06. Question 11 Explanation: The correct answer for this question is 4 or undefined because a, b, and c need to be 1, 2, and 3 respectively for the variable d to be declared and d assigned a value of 4. If a, b, and c are not 1, 2, and 3 respectively, then variable d would not be created so d is not defined and undefined will be printed to the console. If a, b, and c are 1, 2, and 3 respectively, then 4 would be printed to the console since d was declared and assigned a value of 4. 

07. Question 15 Explanation: The correct answer for this question is 1 and 2 will be printed to the console. This is because x = 1 already existed before the console.log(x);. It console logs 1 and then since variable y was declared and assigned a value of 2, it console logs 2 since console.log(y) is on line 10 and y = 2.
