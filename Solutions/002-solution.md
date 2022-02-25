```python

if __name__ == '__main__':
	n = int(input().strip())
	#Takes input and assigns it to variable n
	if n % 2 ==0 :
		#Divdes n by 2 and checks to see if the remainder is equal to 0
		#An even number would have a remainder of 0
		
		if n > 2 and n < 5 :
			#If n is greater than 2 or less than 5 preforms a print
			print("Not Weird")
		elif n > 6 and n < 20:	
			#If n is greater than 6 or less than 20 preforms a print
			print("Weird")
		else:
			#For all other cases print Not Weird
			print("Not Weird")
			
	else:
		#If the input is odd or not a number prints "Weird"
		print("Weird")
```