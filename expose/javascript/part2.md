### Answers

1. The console will output 3 as this is the value of 'i' where the loop breaks. 'i' was declared with var so line 12 is not out of scope.
2. The console will output 150 as this is the final value of the variable, it was also declared with var so line 13 is not out of scope.
3. The console will output 150 as this is the final value of the variable.
4. The function will return [50, 100, 150], the function simply multiplies each of the prices by the discount and returns this. 
5. Error as 'i' was declared with let within a block that is out of scope at line 12.
6. Error as 'discountedPrice' was declared with let within a block that is out of scope at line 13.
7. The console will output 150 as this is the final value of the variable, it was declared with let but line 14 is within the same block as the declaration.
8. The function will return [50, 100, 150], the function simply multiplies each of the prices by the discount and returns this. 'discounted' was declared within the same block as the return.
9. Error as 'i' was declared with let within a block that is out of scope at line 11.
10.  Console will output '3' as this is the value assigned to the constant at declaration.
11.  Console will output [50, 100, 150]. The function works the same as before, the const declaration for discounted is just saying that there is a constant reference to the array but the elements can still be changed so the function still works.

12. :
A - student.name
B - student['Grad Year']
C - student.greeting()
D - student['Favorite Teacher'].name
E - student.courseLoad[0]

13. :
A - '32', integers map to their exact string representation
B - 1, the string is mapped to an integer as integers are needed fro mathematical operations
C - 3, null becomes 0 as an integer
D - '3null', null becomes 'null' as a string.
E - 4, true becomes 1 as an int
F - 0, false and null both become 0 as an integer.
G - '3undefined', undefined just becomes a string.
H - NaN, undefined numerically converts to NaN and since the subtract is used everything converts to numbers.

14. :
A - true, when different types are used javascript converts to numbers and then 2 is greater than 1.
B - false, two strings are being compared and the first index is compared first, the '1' is less that the '2' therefore '12'<'2'.
C - true, different types are converted to numbers and then it is the same number being compared.
D - false, the types are different and therefore are not strictly equal.
E - false, true is converted to 1 and that is not equal to 2.
F - true, Boolean(2) is a function that results in true and then true is strictly equal to true.

15. === is a strict comparison where value and type have to be the same. == only requires that value is the same.
16. part2-question16.js
17. The function will return [2,4,6]. The for loop goes through each element of the given array [1,2,3] and puts it into the doSomethong function which just doubles the number and returns it. Each of these doubled numbers is pushed into a new array which is then returned at the end.
18. parts-question18.js
19. Output,
1
4
3
2















