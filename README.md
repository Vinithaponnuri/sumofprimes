start=int(input())
end=int(input())
sum=0
for i in range(start,end+1):
    for j in range(2,i):
        if(i%j==0):
            break
    else:
        print(i,end='\t')
        sum=sum+i 
print("\nsum of prime numbers is",sum )
