# 1a

1. values added: 20
2. final result: 20
3. values added: 20
4. error, because the result variable was a let, meaning it could only be accessed inside the if statement block it was created in.
5. error, because result was declared as a const so you can't change it, changing result to equal num1 + num2 after its declaration will cause an error. 
6. error, because the result variable is outside the block it was declared in.


# 1b

1. it will print the last value of i before the for loop was terminated.
2. it will print the last value that discountedPrice had before the for loop terminated because its declared as var.
3. it will print the last value that finalPrice had before the for loop terminates.
4. [50, 100, 150] It returns the discounted price of 50%, so each value in the inputted prices is halved.
5. error, i doesn't exist outside the scope of the for loop it was declared for because its declared as a let variable.
6. error, discountedPrice doesn't exist outside the scope of the for loop it was declared for because its declared as a let variable.
7. It will price the last value of the finalPrice before the for loop terminates.
8. [50, 100, 150] It returns the discounted price of 50%, so each value in the inputted prices is halved.
9. error, i doesn't exist outside the scope of the for loop it was declared for because its declared as a let variable.
10. it will print the length variable since it was declared outside the for loop scope block and was never changed.
11. [50, 100, 150] It returns the discounted price of 50%, so each value in the inputted prices is halved.
12. 
    A.  student.name; <br />
    B.  student["Grad Year"]; <br />
    C.  student.greeting(); <br />
    D.  student["Favorite Teacher"].name; <br />
    E.  student.courseLoad[0]; <br />
13. 
    A.  '32', the + operator concatenates. <br />
    B.  1, subtraction cannot be proformmed on string so it converts '3' into the int 3 and subtracts. <br />
    C.  3, null as a number is 0, so 3 + 0 is 3 <br />
    D.  '3null', the string '3' is concatenated to the string null. <br />
    E.  4, true as a number is 1, so 1 + 3 is 4. <br />
    F.  0, false as a number is 0 and null as a number is 0, so 0 + 0 is 0. <br />
    G.  '3undefined', 3 is concatinated to the string "undefined". <br />
    H.  NaN, subtracting a string from undefined is not a valid operation, so it results in it being "Not a Number" NaN. <br />

14. 
    A.  true, 2 becomes the number 2, so 2 > 1 is true <br />
    B.  false, with two strings, it compares each character at a time, and '2' is greater than '1', therefore '2' should be greater than '12'. <br />
    C.  true, '2' is converted into an int 2, so 2 == 2. <br />
    D.  false, === is stricter, and because 2 and '2' are different types, it returns false immediatly since they are different types. <br />
    E.  false, true as an int is 1, so 1 != 2 which is why its false. <br />
    F.  true, all values that are not 0, null, undefined and NaN are true as a boolean. Here 1 is true. <br />
15. == is a weak comparison between two types, while === is strict. === will return false immediatly if the two values being compared are of different values. While == will still evaluate accordingly if the types differ.

17. [2, 4, 6], During each iteration, I called doSomething on each element in the input array, then appended each returned value of doSomething (it multiplies the inputted number by 2) to the newArr array. Then returned it: [2, 4, 6].
19. 1 4 3 2