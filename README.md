# assignment2-23-02-22
write a program to print max and min elements from the list
l=[]
n=int(input())
for i in range(n):
    x=int(input())
    l.append(x)
min=l[0]
max=l[0]
for i in range(1,n):
    if l[i]<min:
        min=l[i]
    for i in range(1,n):
        if l[i]>max:
            max=l[i]
print('min',min)
print('max',max)
OUTPUT:
9
6
5
4
7
8
3
2
1
11
min 1
max 11
