<div>
1. Console will print 3, because the for loop ends at var i = 3.
2. Console will print 150, because that's the last value stored in var discountedPrice during the last iteration of the for loop.
3. Console will print 150, because that's the last value stored in var finalPrice during the last iteration of the for loop.
4. This function will return [50, 100, 150] because the for loop pushes the 3 discounted values into var discounted, which are then returned. 
5. Error, since i is declared using "let", it is not accessible outside the for loop.
6. Error, since discountedPrice is declared using "let", it is not accessible outside the for loop.\
7. Console will print 150, because that's the last value stored in let finalPrice during the last iteration of the for loop.
8. This function will return [50, 100, 150] because the for loop pushes the 3 discounted values into let discounted, which are then returned. The return statement is in the same scope as the discounted variable declaration so no errors.
9. Error, since i is declared using "let", it is not accessible outside the for loop.
10. Console will print 3, because that's the value length was initialized to on line 4.
11. This function will return [50, 100, 150] because the for loop pushes the 3 discounted values into discounted, which are then returned. discounted is a const variable, but pushing values is fine since no variable reassignment occurs. 
12. 	A. student["name"]
	B. student["Grad Year"]
	C. student["greeting"]()
	D. student["Favorite Teacher"]["name"]
	E. student["courseLoad"][0]

13. 	A. '32' because 2 maps to a string
	B. 1 because '3' is converted to a number
	C. 3, because null is treated as a 0
	D. '3null' because null is converted to a string
	E. 4, since true evalutates as 1
	F. 0, since false and null both evaluate to 0
	G. '3undefined' since undefined converts to a string
	H. NaN because undefined becomes NaN when it is attempted to be changed to a number

14. 	A. true, since '2' is converted to a number
	B. false, since both are evaluated as strings
	C. true, since == converts '2' to a number
	D. false, since they are different data types so === does not convert
	E. false, since true is evaluated as 1
	F. true, since 2 casted as a Boolean is true

15. == checks for regular equality while === is strict equality. The regular equality check can compare different data types (eg. 0 and false) but the strict equality check cannot. 

17. This function returns [2, 4. 6]. The function that's passed in doubles the input parameter, which is then applied to all elements of the old array, then pushed into the new array.

19. This program prints 1 4 3 2. 
  
</div>
