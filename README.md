T = int(input())
if T>0 and T<11:
    for j in range(T):
        N = int(input())
        a = list()
        if N>0 and N<=100000:
            for i in range(N):
                a.append(int(input()))
            for k in range(N):
                find = a[k]
                l=0
                for i in range(N):
                    if find == a[i]:
                        l=l+1
                if l%2 != 0:
                    print(a[k])
                    break
