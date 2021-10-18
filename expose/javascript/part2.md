1. Line 12 will print the number 3. This is the length of the input prices array, and will be the value of i after the loop executes, is still in scope because i was declared with the var keyword
2. Line 13 will print the number 150.0. This is the discounted price of the last item, and is still in scope because it was was declared with the var keyword
3. Line 14 will print the number 150.0. This is the final price of the last item, and is still in scope because it was was declared with the var keyword
4. This function will return the array [50.0, 100.0, 150.0]. It loops through all the prices, applies the discount to each, rounds it to two decimal places, and appends the result to the array which the function returns.
5. Line 12 will throw an error because i is out of scope at this point. It is declared with the let keyword in the for loop, so it is only in scope in the loop
6. Line 13 will throw an error because discountedPriceis out of scope at this point. It is declared with the let keyword in the for loop, so it is only in scope in the loop
7. Line 14 will print the number 150.0. This is the final price of the last item, and is still in scope because it was was declared with the let keyword in the same block as line 14
8. This function will return the array [50.0, 100.0, 150.0]. It loops through all the prices, applies the discount to each, rounds it to two decimal places, and appends the result to the array which the function returns. It doesn't matter that discounted was defined with the let keyword because its returned in the same block
9. Line 11 will throw an error because i is out of scope at this point. It is declared with the let keyword in the for loop, so it is only in scope in the loop
10. Line 12 will print the number 3, as this is the length of the input prices array
11. This function will return the array [50.0, 100.0, 150.0]. It loops through all the prices, applies the discount to each, and appends the result to the array which the function returns. All of the variable declarations and usages are valid
12a. student.name
12b. student["Grad Year"]
12c. student.greeting()
12d. sudent["Favorite Teacher"].name
12e. student.courseLoad[0]
13a. 5, the '3' is converted to the number 3
13b. 1, the '3' is converted to the number 3
13c. 3, null is converted to 0
13d. 3, the '3' is converted to 3 and the null is converted to 0
13e. 4, the true is converted to 1
13f. 0, both false and null are converted to 0
13g. NaN, the undefined is converted to NaN and math with NaNs becomes NaN
13h. NaN, the undefined is converted to NaN and math with NaNs becomes NaN
14a. True, the '2' is converted to 2
14b. False, '12' comes before '2' in lexicographical order
14c. True, the '2' is converted to 2
14d. False, with no type conversion 2 does not equal '2'
14e. False, true is converted to 0
14f. True, Boolean(2) evaluates to true
15. == performs type conversions as necessary and compares the resulting values, === does not perform type conversion, so values are only equal if they are the same type and value
17. When called with the listeed parameters, the function will return the array [2, 4, 6]. The callback (doSomething(num)) is  called on each element of the array, doubling it. The result is then appended to newArr, and then this array is returned
18. This function will print 1, 4, 3, and 2, each on their own line and in that order