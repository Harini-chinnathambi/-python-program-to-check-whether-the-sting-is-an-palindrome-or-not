PROGRAM:

def rev(inputstring):
    return inputstring[::-1]

def ispalindrome(inputstring):
    reversestring = rev(inputstring)
    if inputstring == reversestring:
        return True
    return False

s = input("enter a string: ")
result = ispalindrome(s)

if result:
    print("the string is palindrome")
else:
    print("the string is not palindrome")



OUTPUT:

enter a string: hello
the string is not palindrome


