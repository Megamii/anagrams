# anagrams
#function to check if two strings are anagrams 

def check(string1, string2):
	

	if(sorted(string1)== sorted(string2)):
		print("True ; They are anagrams")
	else:
		print("False ; They are not anagrams")		


# recieve input from user
string1 = input('please enter the first word :')
string2 = input('please enter the second word :')


check(string1, string2)
