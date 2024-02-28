# largest-odd-no
#largest odd no using range
n=int(input())
a=list(map(int,input().split()))
r=0
for i in range(n):
  if a[i]%2!=0 and a[i]>r:
    r=a[i]
print(r)


#largest no without using range
n=int(input())
a=list(map(int,input().split()))
r=0
for i in a:
  if i%2!=0 and i>r:
    r=i
print(r)
