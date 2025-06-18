#task1_odd_or_even
x=int(input("Enter a number:"))
if x==0:
    print(x,"is neither odd nor even")
elif x%2==0:
    print(x,"is a even number")
else:
    print(x,"is a Odd Number")
Output:
Enter a number:5
5 is a Odd Number

#task2
sum = 0

for x in range(1, 51):
    sum += x

print("Sum of numbers from 1 to 50 is:", sum)


output:
Sum of numbers from 1 to 50 is: 1275
