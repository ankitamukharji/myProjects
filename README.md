# def fibonacci(n):
 a = 0
 b = 1
if n==1:
   print(a)
else:
  print(a)
  print(b)
for i in range(0,50):
  c = a + b
  a = b
  b = c
  print(c)

#programme no.2
original_list = [10, 20, 30, 40, 50, 60] 
new_list = [original_list[len(original_list) - i]
            for i in range(1, len(original_list)+1)]
print(new_list)
OR
wor = ('a,n,k,i,t,a')   
print(wor[::-1])

#Programming no. 3
num = [1,2,3,4,5,6]
x = len(num)
even = []
odd = []
for i in range(x):
  if num[i]%2==0:
    even.append(num[i])
  else:
    odd.append(num[i])
print ('odd numbers are :',odd)
print ('even numbers are :',even)
