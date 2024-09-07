# 02
# 1) sum of number 

 total = 0
 for i in range(1,101):
   total += i
 print(total)

# 2) factorial of a number

 num = int(input("Enter the number:"))
 factorial = 1
 for i in range(1,num+1):
   factorial *= i
 print(factorial)   

# 3) print even number
 nu1 = int(input("Enter the number:"))
 for i in range(1,nu1+1):
   if i % 2 == 0:
     print(i)

# 4) sum of even number

 nm1 = int(input("Enter the number:"))
 total = 0
 for i in range(1,nm1+1):
   if i % 2 == 0:
     total += i
 print(total) 

# 5) print table of number

 mn1 = int(input("Enter the number:"))
 for i in range(1,11):
   print(f"{mn1} X {i} = {5 * i}")

 # 6) 

 prices = [10,20,30,40,50]
 total = 0
 for price in prices:
   total += price
 print(total)  

# 7) sum of square root 

 mn1 = int(input("Enter the number:"))
 total = 0
 for i in range(1,mn1+1):
   total += i**2
 print(total)

# 8) print odd number

 mn1 = int(input("Enter the number:"))
 for i in range(1,mn1+1):
  if i % 2 != 0:
     print(i)

# 9) creat a list of even square number

 square = []
 mn2 = int(input("Enter the number:"))
 for i in range(1,mn2+1):
   if i % 2 ==0:
     square.append(i**2)
 print(square) 

# 10) find the largest number in a list

 list1 = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15]
 largest = list1[0]
 for i in list1:
   if i > largest:
     largest = i
 print(largest)    
 

