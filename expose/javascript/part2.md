1. Line 12 will print the value of `i` which in this case is 3.
2. Line 13 will print the last calculated value of `dicountedPrice`, which in this case is 150.
3. Line 14 will print the last calculated value of `finalPrice`, which in this case is 150 again.
4. This code will take a set of prices, apply a given discount to each, then return the total price of the discounted goods. In this case, it will return 300.
5. Line 12 will cause an error because `i` is no longer in scope due to it being declared with the `let` keyword.
6. Line 13 will cause an error because `discountedPrice` is no longer in scope due to it being declared within the loop with the `let` keyword.
7. Line 14 will print the last calculated value of `finalPrice`, which in this case is 150.
8. This function works much the same as before, and will take a list of values, apply a given discount to each, then return the sum of the discounted prices. In this case, it will return 300.
9. Line 11 will cause an error because `i` is out of scope after the `for` loop.
10. Line 12 will return the length of the input array, in this case 3.
11. The code will cause errors because there will be multiple redefinitions of constants. It will return an empty array no matter the input.
12. A. `student.name`
    B. `student["grad year"]`
    C. `student.greeting()`
    D. `student["favorite teacher"].name`
    E. `student.courseLoad[1]`
13. A. `'32'` - Because one of the operations is a string, the `+` operater is seen as concatenation.
    B. `1` - Even though `'3'` is a string, there is no operation that `-` can do on strings, so it is converted to an integer and evaluated.
    C. `3` - When used in a statement with integers, `null` converts to the integer 0.
    D. `'3null'` - When used in concatenation with a string, `null` is literally converted to a string.
    E. `4` - When used in an expression as a number, `true` becomes the integer 1.
    F. `0` - Because neither operation is a string, this statement treats `+` as addition. Both `false` and `null` map to integer 0 in this case.
    G. `'3undefined'` - Much like part D, `undefined` is literally interpreted when used in concatenation.
    H. `NaN` - Much like part B, the `-` operater does not operate on strings, so it converts its arguments to integers, where `undefined` maps to `NaN`.
14. A. `true` - Lexicographical order is used with strings, and since 2 is lexicographically after 1, the result is true.
    B. `false` - Lexicographical ordering comes in again, but it compares character by character looking for the first one that doesn't match, and results in calculating the expression `'2' < '1'` which is lexicographically incorrect.
    C. `true` - Type conversion takes place. The string `'2'` is converted to the number 2, which is equal to itself.
    D. `false` - The triple equal sign checks for type equality, which fails since a string and number are being compared.
    E. `false` - The boolean `true` maps to the number 1, which does not equal 2.
    F. `true` - The two types are equal and both evaluate to `true`.
15. The standard equality operator `==` will try to convert its to operands to a like type in order to check equality. The strict equality operator `===` will not perform such a conversion and will instead return `false` if the operands are different types.