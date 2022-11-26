# First-and-Last-swap
n=int(input())
a=[]
for i in range(0,n):
    b=int(input())
    a.append(b)
print(a)
q=a[0]
a[0]=a[-1]
a[-1] = q
print(a)
