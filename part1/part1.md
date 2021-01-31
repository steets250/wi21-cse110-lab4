1. Variable i is declared in the scope of the function discountPrices, so it is accessible by the print statement. The value 3 will be printed for the given input.
2. Variable discountedPrice is declared in the scope of the function discountPrices, so it is accessible by the print statement. The value 150 will be printed for the given input.
3. Variable finalPrice is declared in the scope of the function discountPrices, so it is accessible by the print statement. The value 150 will be printed for the given input.
4. The function will return [50, 100, 150]. For each element in the prices array, it is multiplied by one minus the discount (in this case, still 0.5). That price is then rounded to the nearest hundredth and added to the returned array, all of which have the proper scope to be returned by the function.

5. Variable i is only scoped to the for loop, so an error will occurr.
6. Variable discountedPrice is only scoped to the for loop, so an error will occurr.
7. Variable finalPrice will be printed because it is declared in the same method in which it is printed. The value pr
8. The function will return [50, 100, 150]. It behaves the same way as the previously described function. The value 150 will be printed for the given input.

9. Variable i is only scoped to the for loop, so an error will occurr.
10. Variable discountedPrice is only scoped to the for loop, so an error will occurr.
11. Variable finalPrice is a constant, so an error will occurr when its value is changed later on in the function.

13. A. student.name
13. B. student['Grad Year']
13. C. student.greeting()
13. D. student['Favorite Teacher'].name
13. E. student.courseLoad[0]

14. A. '32'; The 2 is cast to a string and then appended to the '3'
14. B. 1; The '3' is cast to a number and then the value 2 is subtracted
14. C. 3; null has the value 0
14. D. '3null'; null is cast to a string and then appended to the '3'
14. E. 4; true is cast to the value 1 before 3 is added to it
14. F. 0; false and null both have the value 0
14. G. '3undefined'; undefined is cast into a string and then appended to '3'
14. H. NaN; undefined can not be cast to a number, so the result isn't a number
15. A. true; '2' is cast to 2 when being compared
15. B. false; string comparison is used, and '12' is greater length
15. C. true; '2' is cast to 2 when being compared
15. D. false; the === operator compares values, which don't match here
15. E. false; true has the value 1 which does not match 2
15. F. true; Boolean(2) produces the value true which matches
16. == compares values, === compares values and types (non-strict equality vs strict equality)

17. 'How are you?' gets printed, since true casts to 1, which isn't equal to 2, but 2 gets cast to true, which means the else if block runs.

18. External File

19. The result would be [6, 8, 10]. For each element in array, the callback function is called with the element and a function that increases the value by 2. The result of this is plugged into the provided callback function, which returns the number multiplied by 2. Finally, this result is stored in the array to be returned.

20. External File

21. 1, 4, 3, 2 will be printed this order.
