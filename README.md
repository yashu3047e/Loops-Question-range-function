# Loops-Question-range-function
Range Function Tough question which will help you with logic building 

# Program has been written by @yshpvt 


# WAP to find its factorial
# factorial , 5= 5x4x3x2x1 , 0=1

num = int(input("Enter a number to find its factorial : "))
factorial = 1
for i in range(1, num+1):
    factorial= factorial*i
    
print(f"factorial of {num} is {factorial}")

# WAP to print the following Fibonacci series 0,1,1,2,3,5,8....n terms
num = int(input("Enter The Number Of terms : "))
a,b = 0,1
for i in range(num+1):
    print(a, end=" ")
    a,b =b,a + b
    
# WAP to enter 10 numbers and find the sum and avg 

number = []
for i in range(10):
    num = float(input(f"Enter Number {i+1} : "))
    number.append(num)
    
sum = 0
for num in number:
    sum+=num
    
avg = sum/10
print(sum)
print(avg)

# WAP to enter Lower_Limit, Upper_Limit and find the sum of all odds and evens number between the range separately

lower = int(input("Enter Lower Limit : "))
upper = int(input("Enter Upper Limit : "))

sum_odd =0
sum_even=0
for i in range(lower, upper+1):
    if i%2==0:
        sum_even+=i
    else:
        sum_odd+=i
        
print(f"The Sum Of Even Number is {sum_even}")
print("The Sum of odd number is", sum_odd)






