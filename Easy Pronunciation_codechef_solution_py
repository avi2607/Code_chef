# https://www.codechef.com/problems/EZSPEAK

t = int(input())

for i in range(t):
    n = int(input())
    w = input()
    v = ['a', 'e', 'i', 'o', 'u']
    flag = 0

    for j in range(n-3):
        if(w[j] not in v and w[j+1] not in v and w[j+2] not in v and w[j+3] not in v):
            flag = 1
    
    if flag == 1:
        print("NO")
    else:
        print("YES")
            
