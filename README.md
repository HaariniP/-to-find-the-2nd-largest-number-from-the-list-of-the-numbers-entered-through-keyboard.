# -to-find-the-2nd-largest-number-from-the-list-of-the-numbers-entered-through-keyboard.
a=[]
n=int(input("Enter number of element:"))
for i in range(1,n+1):
    b=int(input("Enter element:"))
    a.append(b)
a.sort()
print("Second largest element is:",a[n-2])

output:
Enter number of element:6Enter the limit less than 9999999 7
Enter 1th number:67
Enter 2th number:435
Enter 3th number:789
Enter 4th number:243
Enter 5th number:87
Enter 6th number:324
Enter 7th number:980
Smallest no.is: 67a=[]
