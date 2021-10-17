1. prints 2, as i will be a local variable and accessible anywhere in the function after it. The for loop starts at 0 and loops 3 times (as prices.length is 3), so the final i will be 2.
2. prints 150, as discountedPrice will be a local variable and accessible anywhere in the function after it. The loop ends on the last index of prices, so calculation will be discountedPrice = 300 * (1-0.5) = 150
3. prints 150, as finalPrice will be a local variable and accessible anywhere in the function after it. The loop ends on the last index of prices, so calculation will be finalPrice = (150 * 100) / 100
4. Returns an array [50, 100, 150], which is calculated within the for loop and pushed to the discounted variable.
5. Returns an error, let i is not accessible outside the scope of the for loop. 
6. Returns an error, let discountedPrice is not accessible outside the scope of the for loop. 
7. Prints 150, let finalPrice is defined outside the for loop scope, and although the value is changed in the scope of the for loop, the final value is accessible at line 14.
8. Returns an array [50, 100, 150], which is calculated within the for loop and pushed to the discounted variable. let discounted was declared as a local variable to the function.
9. Returns an error, let i is not accessible outside the scope of the for loop. 
10. Prints 3, const length was declared within the scope of the function (and was unchanged from declaration to call on line 12)
11. Returns an array [50, 100, 150], which is calculated within the for loop and pushed to the discounted variable. const discounted was declared as a local variable to the function
12. Answers:
- a. student.name
- b. student['Grad Year']
- c. student.greeting()
- d. student['teach'].name
- e. student['courseLoad][0]
13. Answers:
- a. 32, '3' is a string and a string '2' is concatenated to it (by the + operator)
- b. 1, although '3' is a string, the - operator implies substraction and so 3-2 becomes an integer
- c. 3, 3 is an integer and null represents an empty value, so 3 plus empty is 3.
- d. 3null, '3' is a string and the string 'null' is concatenated to it (by the + operator)
- e. 4, true is represented as an integer 1, so the expression is 1 + 3
- f. 0, false is represented as an integer 0 and null is empty value, so the expression is 0 + ""
- g. 3undefined, '3' is a string and a string 'undefined' is concatenated to it (by the + operator)
- h. NaN, AKA Not-A-Number, which is caused by attempting to subtract 3 by an undefined number
14. Answers:
- a. true, "2" becomes a number so 2 > 1
- b. false, string comparison where the first character is compared, but 2 > 1
- c. true, "2" becomes a number so 2 == 2
- d. false, the === operator compares value type, string type is not equal to an integer type
- e. false, true is converted to a number 1, but 1 != 2
- f. true, Boolean(2) returns true since 0, -0, null, false, NaN, undefined, or the empty string was not inputted. true === true
15.  The == operator compares the two values to be equal, but the === operator compares the value and the value type. So "2" == 2 would return true, but "2" === 2 would return false as string is not equal to integer. 
16.  In JS file
17.  [2, 4, 6], the modifyArray function passes in the array [1, 2, 3] and the doSomething function as a callback function. The for loop iterates through the array and doSomething multiplies each value by 2. 
18.  The output would be
        `1  4  3  2` (where each is separated by a \n).
        This is caused from the set delay of printing to the console. Lines 2 and 5 would print immedately while lines 3 and 4 are delayed by the specified amount.