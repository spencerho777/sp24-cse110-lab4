1. Line 12 will print 2 because that is what the for loop will increment it to before it ends and it has function scope with var
2. Line 13 will print 150 because in the final iteration of the for loop, it will be set to 300 * 0.5 which is 150 and it has function scope with var
3. Line 14 will print 150 because in the final iteration of the for loop, it will be set to Math.round(150*100) / 100 which is 150 and it has function scope with var
4. [50, 100, 150], the function applies the discount to each price
5. Error, i will not be defined because it was declared in the previous block's scope with let
6. Error, discountedPrice will not be defined because it was declared in the previous block's scope with let
7. Line 14 will print 150, finalPrice will be properly updated each iteration and it was defined in the same block as the log
8. [50, 100, 150], the function applies the discount to each price
9. Error, i will not be defined because it was declared in the previous block's scope with let
10. Line 12 will print 3, lengtj was defined in the same block as the log using const
11. [50, 100, 150], the function applies the discount to each price
12. A. student.name, B. student['Grad Year'], C. student.greeting(), D. student['Favorite Teacher'].name, E. student.courseLoad[0]
13. A) '32', 2 maps to '2' and adds
B) 1, '3' maps to 3 and subtracts
C) 3, null maps to 0
D) '3null', null maps to 'null'
E) 4, true maps to 1 and adds
F) 0
G) '3undefined', undefeind maps to 'undefined'
H) NaN, undefined cannot subtract so with string so we get NaN
14. A) true, '2' maps to 2
B) false, '2' is lexigraphically bigger than '12'
C) true, 2 maps to '2' so they are equivalent
D) false, === represents type and value equivalency
E) false, true maps to 1 which is not 2
F) true, Boolean(2) is equal to true
15) == checks for value equivalency, === enforces type equivalency as well
16) part2-question16.js
17) modifyArray returns [2, 4, 6]. In the for loop, each element gets passed through the callback-- which mulitiplies it by 2 and returns that value-- and then gets added to newArr. This is returned at the end of the function
18) part2-question18.js
19) 1, 4, 3, 2