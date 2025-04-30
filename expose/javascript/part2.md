1. At line 12, the console will print the value of i, which will be 3, as the loop runs from i = 0 to i < prices.length, which is 3, meaning it will fail this condition and exit the loop when i is 3.
2. At line 13, the console will print the value of discountedPrice, which will be 150, as the last calculated value in the i = 2 loop has prices[2] = 300, meaning discounted price = 300 * 0.5 which is 150.
3. At line 14, the console will print the value of finalPrice, which is 150, as it does the same as part 2, but then rounds 150, which once again is 150.
4. This function will return the array of prices discounted, being [50, 100, 150], as these are the original values discounted 50% (0.5). For each value, it loops and discounts it by 50% and then adds the new value to the new array.
5. At line 12, it will cause a ReferenceError, as the variable i uses let, meaning it has block scope, and line 12 is outside of the loop block, resulting in a ReferenceError.
6. At line 13, it will cause a ReferenceError, as discountedPrice also uses let, so it cannot be accessed at line 13, and a ReferenceError is thrown.
7. At line 14, the console will print the value of finalPrice, which is 150. It is declared using let, but line 14 is still in the block scope, so everything works as intended and it prints 150.
8. This function will return the discounted price array the same as question 4. There are no errors, all declarations are correct and the ones using let are used only in their blocks.
9. At line 11, it will cause a ReferenceError, as i was declared using let, and accessed on line 11, outside of the loop, meaning it wasn't in the scope, resulting in this error.
10. At line 12, the console will print the value 3, as length is declared as a const, and the length of the array is 3 (100,200,300). Therefore, the length is 3. No block scope issues as length is declared with const, but the block is the whole function.
11. a) student.name
    b) student['Grad Year']
    c) student.greeting()
    d) student['Favorite Teacher'].name
    e) student.courseLoad[0]
