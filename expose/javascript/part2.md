# Part 2 "A little more of a challenge..." Questions
## Question 1: ^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^
### Answer: 3 because we are utilizing keyword var that allows for reassignment and ignores the block scope.

## Question 2: ^^^ What will happen at line 13 and why? If the code causes an error, explain why. ^^^
### Answer: 150 because we are utilizing keyword var that allows for reassignment and ignored the block scope.

## Question 3:^^^ What will happen at line 14 and why? If the code causes an error, explain why. ^^^
### Answer: 150 because we are utilizing keyword var that allows for reassignment and ignored the block scope.

## Question 4: ^^^ What will this function return? Give a brief explanation why. If the code causes an error, explain why. ^^^
### Answer: [ 50, 100, 150 ], because these are the correctly calculated discounted values.

## Question 5: ^^^ What will happen at line 12 and why?  If the code causes an error, explain why. ^^^ (assume this function is being called like the others: discountPrices([100, 200, 300], 0.5)).
### Answer: This would cause an error because you are attempting to utilize a variable out of scope.

## Q uestion 6: ^^^ What will happen at line 13 and why? If the code causes an error, explain why. ^^^
### Answer: This would cause an error because you are attempting to utilize a variable out of scope.

## Question 7: ^^^ What will happen at line 14 and why? If the code causes an error, explain why. ^^^
### Answer: This would cause an error because you are attempting to utilize a variable out of scope.

## Question 8: ^^^ What will this function return? Give a brief explanation. If the code causes an error, explain why. ^^^
### Answer: [ 50, 100, 150 ], because we are properly utilizing the dicounted let variable as it was defined in  the scope of the function.

## Question 9: ^^^ What will happen at line 11 and why? If the code causes an error, explain why. ^^^
### Answer: This will cause an error as we are attempting to field the i variable out of its scope.

## Question 10:^^^ What will happen at line 12 and why? If the code causes an error, explain why. ^^^
### Answer: 3 because we are properly fielding the const variable length in the correct scope, without assigning any const variables more than once.

## Question 11: ^^^ What will this function return? Give a brief explanation. If the code causes an error, explain why. ^^^
### Answer: [ 50, 100, 150 ] because we are properly utilizing the const variable keyword.

# Part 2 Data Types Questions

## Questiion 12: Given the above Object, write the notation for:  (These should be in your part2.md)
1. Accessing the value of the name property in the student object
### Answer: student.name;
2. Accessing the value of the Grad Year property in the student object
### Answer: student['Grad Year'];
3. Calling the function for the greeting property in the student object
### Answer: student.greeting();
4. Accessing the name property of the object in the Favorite Teacher property in student
### Answer: student['Favorite Teacher'].name;
5. Access index zero in the array of the courseLoad property of the student object
### Answer: student.courseLoad[0];

## For each of the following 2 questions, note down the output as well as a brief explanation why that output was given

## Question 13: Arithmetic
1. ‘3’ + 2
### Answer: 32 becuase the first value is a string, and will thus perform string concatentation and convert 2 to a string '2'.
2. ‘3’ - 2
### Answer: 1 because the subtraction operator is only used for numeric types and will convert '3' to a number.
3. 3 + null
### Answer: 3 because it will convert null to 0 and sum the values.
4. ‘3’ + null
### Answer: '3null' because it will see that the first value in the summation is a string and will thus perform a string concatention.
5. true + 3
### Answer: 4 because it will type convert true to a number which is 1 by true/false convention.
6. false + null
### Answer: 0 because it will convert both false and null to 0.
7. '3' + undefined
### Answer: similar to question 4, it will result in '3undefined' because it will perform a string concatenation.
8.  '3' - undefined
### Answer: NaN because we are attempting to perform a subtraction operation with undefined type.


## Question 14: Comparison
1. ‘2’ > 1
### Answer: true because it will convert '2' into 2 and compare it to 1
2. ‘2’ < ‘12’
### Answer: true because when we compare the '2' with the second character in 12, 2, it will return true.
3. 2 == ‘2’
### Answer: true because it will convert '2' into a number
4. 2 === ‘2’
### Answer: false because this operator performs strict equality comparison and will not perform any type convertions. 
5. true == 2
### Answer: false because true converts to 1 but 1 != 2.
6. true === Boolean(2)
### Answer: true because Boolean(2) returns true.

## Question 15: Explain the difference between the == and === operators.
### Answer: The == operator performs loose comparisons while === performs strict comparisons. The == will attempt to perform type convertions between values if detects different types. The === operator will not perform any type convertions, and thus requires both operands to be of the same type before making the comparison, or else it will just be false.

## Question 17: If the function above is called with the following parameters modifyArray([1,2,3], doSomething), what will be the result? Briefly walk through how you arrived at that result.
### Answer: The result will be [2, 4, 6] because it will perform the doSOmething function on each element of our input array '[1,2,3]', it will push the result of each operation into a new array before returning to us.

## Question 19: What is the output of the above code?
### Answer: 
### 1
### 4
### 3
### 2