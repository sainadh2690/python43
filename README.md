# AMSTRONG NUMBER
print("Try programiz.pro")
num= int(input("Enter the number:"))
temp= num
n=len(str(num))
sum=0
while temp>0:
    digit= temp%10
    temp //=10
print("latest value of sum:", sum)
print("latest value of temp:", temp)
if sum==num:
    print("is a amstrong number")
else:
    print("is not a amstrong number")
