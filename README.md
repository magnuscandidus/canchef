# canchef
t=int(input())
while t:
    x,y=map(int,input().split())
    if((x*15)>=(2*y)):
        print("YES")
    else:
        print("NO")
    t-=1
