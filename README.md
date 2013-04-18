def isPrime(input):
  if input < 2:
		return false
	elif input == 2:
		return str(input) + " is prime"
	else:
		for num in range(2, input):
			if input % num == 0:
				return str(input) + " is not prime"
		return str(input) + " is prime"
		
print isPrime(2)
print isPrime(3)
print isPrime(4)
print isPrime(15)
