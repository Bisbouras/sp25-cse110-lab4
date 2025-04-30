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
11. This function will return the array [50,100,150] as usual, as all variables are used in their scope, and even though the array is declared using const, it's contents can still be modified, resulting in the correct answer.
12. a) student.name
    b) student['Grad Year']
    c) student.greeting()
    d) student['Favorite Teacher'].name
    e) student.courseLoad[0]
13. a) '32' - when a string and a number are added, it converts to a string and concatenates them
    b) 1 - subtraction only works with numbers, so the string is converted to a number
    c) 3 - null is converted to 0, so 3 + 0 = 3
    d) '3null' - since '3' is a string, this simply concatenates both strings resulting in 3null.
    e) 4 - true is converted to 1 when used in numeric operations, so it becomes 1 + 3 = 4
    f) 0 - both false and null are 0 when used in numeric operations, so this is 0 + 0
    g) '3undefined' - Once again, since 3 is a string in this case, it performs string concatenation.
    h) NaN - undefined converts to NaN when used in numeric operations, and if any arithmetic uses NaN, the result is NaN
14. a) true - converts 2 to a number for the comparison, and the comparison is true
    b) false - both are strings, so it compares them alphabetically, and since 2 comes after 1, '2' is not less than '12'
    c) true - == does type conversion, so the string is converted into a number and they are indeed equal.
    d) false - === doesn't do type conversion, so the string isn't converted, therefore they are not the same.
    e) false - 2 is not equal to 1 (true converts to 1)
    f) true - any non zero number is true in boolean, so true === true is true.
15. == checks if values are equal AFTER type converting them into a common type, while === simply checks if the values are equal as they are, without any type conversion.

17. The result of calling this array will be [2, 4, 6]. The array is called with 2 parameters, array and callback. Then, a new empty array is created, and a for loop goes through each element in the original inputted array. For each element, the function doSomething multiplies each array element by 2, therefore 1*2 = 2, 2*2 = 4, 3*2 = 6. After this, each result is pushed to the new Array, which is returned.
