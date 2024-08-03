num = int(input("Enter any num "))
n1,n2= 0,1
sum=0
if num<=0:
    print("please enter num greater than 0 ")
else:
    for i in range(0,num):
        print(sum,end=" ")
        n1=n2
        n2=sum
        sum=n1+n2

