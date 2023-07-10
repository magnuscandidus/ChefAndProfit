# ChefAndProfit
# cook your dish here
t=int(input())
while t:
    x,y,z=map(int,input().split())
    print((x*z)-(x*y))
    t-=1
