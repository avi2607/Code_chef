# https://www.codechef.com/problems/ATM2


t = int(input())

for i in range(t):
    n,k = map(int,input().split())
    x = list(map(int,input().split()))
    y = 0
    while(n>y):
        for i in x:
            if(k >= i):
                k = k - i
                print(1,end="")
            else:
                print(0,end="")
            y = y + 1
    print()
    
