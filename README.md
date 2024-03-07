#Approach-1
n=int(input())
a=list(map(int,input().split()))
res=0
for i in range(n):
  if a[i]%2!=0 and a[i]>res:
    res=a[i]
print(res)

#Approach-2
n=int(input())
a=list(map(int,input().split()))
res=0
for i in a:
  if i%2!=0 and i>res:
    res=i
print(res)

#Approach-3
n=int(input())
a=list(map(int,input().split()))
r=[]
for i in range(n):
  if a[i]%2!=0:
    r.append(a[i])
print(max(r))

#Approach-4
n=int(input())
a=list(map(int,input().split()))
r=[]
for i in a:
  if i%2!=0:
    r.append(i)
print(max(r))
