# Work
# Work
#1
a = 9
tuplex = [4, 6, 2, 8, 3, 1]
tuplex.append(a)
print(tuplex)


tuplex = [4, 6, 2, 8, 3, 1]
tuplex.append(123)
print(tuplex)

#2
l = [(10, 20, 40), (40, 50, 60), (70, 80, 90)]
b=[(t[0],t[1],) + (100,) for t in l]
print(b)

#3
my_list = [(), (), ('',), (), ('a', 'b'), ('a', 'b', 'c'), ('d',)]
another_list = []
for x in my_list:
    if x == ():
        pass
    else:
        another_list.append(x)
print(another_list)



#4
nums = (1,2,3)
for a in nums:
    print(a, end="")
    
  nums = (10,20,40,5,70)
  for a in nums:
  print(a, end="")
  
  #5
  # n1 = int(input("Введите целое число: ")) 
# n2 = 0 
# while n1 > 0: 
#     digit = n1 % 10 
#     n1 = n1 // 10 
#     n2 = n2 * 10 
#     n2 = n2 + digit 
# print(n2) 
 
a = input("Введите число:") 
b = '' 
for i in a: 
    b = i + b 
print(b)
