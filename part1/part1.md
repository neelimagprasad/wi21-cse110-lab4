# Introduction to JavaScript
1. The variable i, which stores the value prices.length will printed to the console because "i" is visible after loop, since it ignors code blocks
2. The variable discountedPrice will be printed to the console, because it is defined as a var, which ignores code blocks
3. The variable finalPrice will be printed to the console, because it is defined as a var, which ignores code blocks
4. The function will return 
```
 [50 ,100 ,150]
```
because the values that get pushed are 100x0.5 = 50, 200x0.5 = 100, 300x 0.5 = 150

5. There will be a reference error because the keyword let ensures that if a variable is declared inside a code block, it’s only visible inside that block. Since i is defined in the code block
6. There will be a reference error because the keyword let ensures that if a variable is declared inside a code block, it’s only visible inside that block.Since i is defined in the code block
7. The variable final price will be printed to the console,because it was defined outside of the code block at the beginning of the code. 
8. The function will return 
```
 [50 ,100 ,150]
```
just like #4 because  discounted was defined outside of the code block. 

9. There will be an error that reads 

```
TypeError: invalid assignment to const "x"
```
because i was used when attempting to alter a constant value

10.  There will be an error that reads 

```
TypeError: invalid assignment to const "x"
```
because there was an attempt to alter a constant value

11.  There will be an error that reads 

```
TypeError: invalid assignment to const "x"
```
because there was an attempt to alter a constant value

12.  There will be an error that reads 

```
TypeError: invalid assignment to const "x"
```
because there was an attempt to alter a constant value

13.
- A) student.name
- B)
```
for (var key in student) {
  if(key == 'Grad Year')
  console.log(` ${student[key]}`);
  ```
}
- C) student.greeting
- D)
```
for (var key in student) {
  if(key == 'Favorite Teacher')
  console.log(` ${student[key].name}`);
  ```
     
}
- E) student.courseLoad[0]
14. 
- A) '32' because the values get concatenated
- B) 1 because the strings cannot be subtracted, so they get parsed as number and 3-2 = 1
- C) 3 because since 3 is a number, null gets parsed as the number 0, 3+0 n= 3
- D) '3null' because since '3' is a string, the + operator concats the two strings
- E) 4 because the boolean value of true is 1, 1+3 = 4
- F) 0 because the boolean value of false is 0, 0+0 = 0
- G) '3undefined' because since 3 is a string, the + operator concats undefined to 3
- H) NaN because 3 - undefined is not a number, which is what NaN stands for

15. 
- A) true because '2' becomes a number when comparing
- B) false because the first character '2' > '1' , not <
- C) true becuase '2' and 2 are the same value, but different types
- D) false because '2' and 2 are not the same type
- E) false because true = 1 is not equal to 2
- F) true because Boolean(2) is true, whihc is the same as true

16. The == operator checks if the two operands are the same value or not, regardless of type. The === operator returns true if two varaibles are of the same type, are not numeric, and have the same value.

17. How are you? because 2 == true is false, since true ==1, but 2 == 2.

18. see file


