for _ in xrange(int(raw_input())):
	n=int(raw_input())
	power=str(2**n)
	result=0
	for i in power:
		result += int(i)
	print(result)
