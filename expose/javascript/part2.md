1. Line 12 will print out 3 because the for loop will loop for all elements of the array.
2. Line 13 will print out 150 because the 150 is the last update to discounted price.
3. Line 14 will print out 150, which is the last update to finalPrice.
4. The code will return [50, 100, 150] because the 50% discount is applied to all prices.
5. The code would return an error because i is not defined outside of the block of code with the for loop because of the "let" declaration.
6. The code would return an error because discountedPrice isn't accessible outside the for loop or the initial declaration block.
7. The code will print 150 because finalPrice is in the same scope as the console output, so the last update to finalPrice will be printed.
8. [50, 100, 150] is printed because discountedPrice is accessible outside the for loop since it is declared in the same scope. 
9. Line 11 would return a ReferenceError because i is only defined for the scope of the for loop, not the whole function.
10. Line 12 would print 3 because the console.log is accessing a cont variable, not editting it, which is allowed. 
11. The function would return [50, 100, 150] because the values in the array can be modified even if the variable it's assigned to is const.
12. Given the above Object, write the notation for: 
    1.  student.name
    2.  student["Grad Year"]
    3.  student.greeting()
    4.  student{"Favorite Teacher"}.name
    5.  student.courseLoad[0]
13. Arithmetic
    1.   32 because 3 is a character and that typecasts the 2 from integer into a character and appends them
    2.   1 because the operator is subtraction, so the character is typecasted into int.
    3.   3 is printed because null is worth nothing, which is also worth 0, so 3 + 0 is 3.
    4.   3null is printed because the null is directly casted into a string because the '3' is a string.
    5.   4 is printed because true is worth 1, and adding 3 gives 4.
    6.   0 is printed because false is worth 0, and null is also worth 0, and 0 + 0 is 0.
    7.   3undefined is printed because since the operator is addition, the understand is typecasted into a string, so is appended to 3.
    8.   NaN is printed because doing arithmetic operations on an undefined value and a string is not allowed, resulting in a Not a Number.
14. Comparison
    1.  true would be printed because 2 is typcasted into an integer and 2 > 1.
    2.  false because the two strings are compared at each index, and 2 is not less than 1.
    3.  true because the string is typecasted into an integer, and 2 is same as 2
    4.  false because triple equals are a strict comparison, and 2 and '2' are not the same data type, so false
    5.  false because true is the same as 1, and 1 is not the same as 2
    6.  true because Boolean(2) returns true, and true is the same as true.
15. == is a regular comparison and === is a strict comparison. == does not take into account data type, but === does.
16. file
17. The result would be [2, 4, 6]. In each for loop iteration, the value at each index is multiplied by two because of the callback variable calling the doSomething function.
18. file
19. 
    1
    4
    3
    2