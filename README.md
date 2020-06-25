# Python-Assigmemt-6


[25/06, 7:56 pm]  def input(n):
	 if n in range(3,9):
	  print("number is in given range",n)
	 else:
	  print("number is not in given range")
input(6)
[25/06, 7:57 pm] def maximum(a,b,c):
	    if(a>=b)and(a>=c):
	    	 print("maximum is",a)
	    elif(b>=a) and (b>=c):
	    	 print("maximum is",b)
	    else :
	         print("maximum is",c)
	    return maximum
maximum(10,20,30)
[25/06, 7:57 pm]  def fact(n):
	if n==1 :
		return n
	else :
		return n*fact(n-1)
print(fact(5))
