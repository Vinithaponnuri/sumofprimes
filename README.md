n=int(input())
sum = 0
for i in range(n):
    if i > 3:
        for j in range(2,i):
            if (i%j)==0:
                break
            elif j == (j-1):
                sum += i
                print(i)
print(sum)
