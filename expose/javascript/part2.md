Q1: it will prrint i, which is 2, since after for loop, value of i becomes 2.

Q2: it will prrint discounted price, which is 150, since after for loop, value of discounted price becomes 150.

Q3: it will prrint final price, which is 150, since it is value round by discounted price and becomes 150.

Q4: it will return the discounted price [50,100,150], since it contain all the price after discount of 50% and its value becomes half of the orginal [100,200,300].

Q5: there will be an error since it is using let to define "i" and we can not use it outside of the block scope.

Q6:there will be an error since it is using let to define "discountedPrice" and we can not use it outside of the block scope.

Q7:it will prrint final price, which is 150, since it is value round by discounted price and becomes 150, also, it is defined in the same block scope of line 13, therefore we can access to its value. In addition, after the for loop, it values become half of 300 and after round, it has the value of 150.

Q8: it will return the discounted price [50,100,150], since it contain all the price after discount of 50% and its value becomes half of the orginal [100,200,300].

Q9: there will be an error since it is using let to define "i" and we can not use it outside of the block scope.\

Q10: it will print 3 because length is assigned with the length value of prices array which is 3.

Q11:it will return the discounted price [50,100,150], since it contain all the price after discount of 50% and its value becomes half of the orginal [100,200,300].

Q12: 
- A. student.name
- B. student["Grad Year"]
- C. student.greeting()
- D. student["Favorite Teacher"].name
- E. student.courseLoad[0]

Q13:
- A."32". since it will take 2 as a string and add them up as a string
- B.  1. since when using "-" the "3" will be regarded as a number and do 3-2=1
- C. 3. The output was given because numeric conversion happens to null when tring to add a number with it. The numerical value of null is 0. 
- D. "3null". The output was given because string conversion happens to null when trying to add it with a string. The string value of null is "null".
- E. 4. when doing this, true will be take as an integer 1 and do 1+3 = 4.
- F. 0. since numeric conversion needed and false becomes 0 and null becomes 0. Therefore, 0+0=0 is the answer.
- G. "3undefined". The output was given because with string conversion to undefined when trying to add it with a string 3. Then it becomes "3"+"undifined"="3undifined"
- H. NAN. the global undefined property represents the primitive value undefined . It tells us that something has not assigned value isn't defined. undefined isn't converted into any number, so using it in maths calculations returns NaN.

Q14:
- A. True since numeric conversion makes "2" to 2 and 2>1
- B. False. To see whether a string is greater than another, JavaScript uses “dictionary” or“lexicographical” order. '2' has a bigger lexicographical order when comparing the first letters in the string. Therefore, false.
- C. True.because operands of different types are converted to numbers by the equality operator ==. '2' was converted to 2 and 2==2, therefore, it returns true.
- D. False. since they are in different type and === checks equality without type conversion.
- E. False. because operands of different types are converted to numbers by the equality operator ==. '2' was converted to 2 and true was converted to 1. Since 2 is not equal to 1, therefore, the answer is false.
- F.True. since a strict equality operator === checks the equality without type conversion. Since 2 was casted to boolean type by Boolean(2), it becomes true. So the answer returns true.

Q15: Operands of different types are converted to numbers by the equality operator == so that it cannot differentiate 0 from false. However, a strict equality operator === checks the equality without type conversion. In other words, === can check type while == can not.

Q16: in the part2-question16.js file

Q17:the result would be [2,4,6] since the function use dosomething to the origin array [1,2,3]and with a for loop, it create an arrat that every element in original array becomes 2 times of itself and return. Therefore, we get [2,4,6].

Q18: in the part2-question18.js file

Q19: The output is 1 4 3 2