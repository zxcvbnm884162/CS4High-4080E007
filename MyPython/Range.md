# range的技術
## range的技術(1)
```
list1=range(10)
list1
答案:[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
```

# range的技術(2)
```
list2=range(1,10)
list2
答案是:[1, 2, 3, 4, 5, 6, 7, 8, 9]
```

# range的技術(3)
```
list3=range(1,2,5)
list3
答案:[1]
```

# range的技術(4)
```
for dd in range(10):
   print(dd)
答案:
0
1
2
3
4
5
6
7
8
9
```

# 程式閱讀題:下列程式執行後會印出什麼？
```
list1=range(5)
list2=range(1,5)
list3=range(1,5,2)
list4=range(5,1,-2)

print(list(list1))
print(list(list2))
print(list(list3)) 
print(list(list4))  

答案:
[0, 1, 2, 3, 4]
[1, 2, 3, 4]
[1, 3]
[5, 3]
```

# for 迴圈技術
```
for n in range(10):
  print(n,end=",")
答案:0,1,2,3,4,5,6,7,8,9,
```

&
# 程式閱讀題:下列程式執行後會印出什麼？
```
numbers = [21, 4, 35, 1, 8, 7, 3, 6, 9]
my_numbers = []

for number in numbers:
    if (number % 2 != 0): 
　　my_numbers.append(number)

print(my_numbers)
答案:
```

# 程式設計題:完成等差數列的總和計算:1+3+5+...+9
```
number = 0
for n in range(1,10,2):
  number += n
print(number)
答案:25
```

# 程式設計題:完成等差數列的積和計算:1乘6乘11乘...乘16
```
number = 1
for i in range(1,20,5):
    number *= i
print(number)
答案:1056
```
