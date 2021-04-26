## Part 1a
1. values added: 20
2. final result: 20
3. values added: 20
4. error: result is not accessible outside the if block.
5. error: result cannot be reassigned any other value.
6. error: result cannot be reassigned any other value.

## Part 1b
1. the value 3 will be logged to the console as the value of i is equal to the value of prices.length at the end of the for loop.
2. the value 150 will be logged to the console as discountedPrice will contain the value of its final reassignment 300 * (1 - 0.5) = 150.
3. the value 150 will be logged to the console as finalPrice will contain the value of its final reassignment Math.round(150 * 100) / 100 = 150.
4. the function will return the array [50, 100, 150] as the for loop takes each value of the original prices array and applys the discount
   before pushing the final price to the returned array.
5. error: i is not accessible outside the for block.
6. error: discountedPrice is not accessible outside the for block.
7. the value 150 will be logged to the console as the for loop is still able to reassign its value, being inside the same block as the original function.
8. the function will return the array [50, 100, 150] for the same reason as stated in question 4, despite the let declarations as everything is still accessible.
9. error: i is not accessible outside the for block.
10. the value 3 will be logged to the console as length is determined by the length of the prices array and declared as a constant.
11. the function will return the array [50, 100, 150] for the same reason as stated in question 4, despite the const declaration as the contents of the array itself is not being
    reassigned.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. '32' : 2 is converted to '2' and string concatenation is performed.
    B. 1 : '3' is converted to the integer 3 and mathematical subtraction is performed.
    C. 3 : null is converted to the integer 0 and 3 + 0 = 3.
    D. '3null' : null is converted to 'null' and string concatenation is performed.
    E. 4 : true is converted to the integer 1 and mathematical addition is performed.
    F. 0 : both false and null are converted to the integer 0 before mathematical addition is performed.
    G. '3undefined' : undefined is converted to 'undefined' and string concatenation is performed.
    H. NaN : undefined is converted to NaN and mathematical subtraction is performed for a solution of NaN as there is no number representation for the operation.
14. A. true : '2' is converted to the integer 2, making the statement true.
    B. false : '2' is converted to the integer 2 while '12' is converted to the integer 12, making the statement false.
    C. true : '2' is converted to the integer 2, making the statement true.
    D. false : '2' is unable to be converted to the integer 2 due to the nature of the strict equality operator, making the statement false.
    E. false : true is converted to the integer 1, making the statement false.
    F. true : Boolean(2) returns the boolean value true, making the statement true.
15. the == operator allows for type conversion before the equality check while the === operator does not.
16. See part1b-question16.js
17. The result of the function modifyArray([1,2,3], doSomething) will be the array [2,4,6]. This array is crated by the function modifyArray initally as the empty array newArr,
    which is filled by the result of doSomething(i) for all elements i of the original array [1,2,3]. doSomething(i) proceeds to multiply its input by 2 before returning the value back to modifyArray, which pushes the value into newArr and continues the procedure until the entirety of the original array is proceesed. newArr is then returned as the result of the function and the process terminates.
18. See part1b-question18.js
19. 1
    4
    3
    2