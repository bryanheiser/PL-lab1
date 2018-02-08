2.a. At line 4 pi is bound to line 3 where pi is declared in the scope of the circumference function. The use of pi at line 7 is bound to line 1 because in the scope of the area function pi was declared as a val at line 1.

b. The use of x at line 3 is bound to line 2 where x is defined to be input for the function f. The use of x at line 6 is bound to line 5 where the pattern matched "case x". The use of x at line 10 is bound to line 5 as well, not line 8 where x is declared as a val, but it is declared within a different scope than at line 10. The use of x at line 13 is bound to line 1 because every use of x between, and including, lines 2 and 12 are in a different scope than at line 13.

3. Yes the body of g is well-typed.

(b, 1) or (b, a + 2): ((Int, Int), Int) because
	a = 1: Int
	x: Int
	b = (x, 3): (Int, Int)
	a + 2 = 3: Int 
