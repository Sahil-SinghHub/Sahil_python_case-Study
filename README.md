a=float(input("Enter the cost of 1st item: "))
n1=int(input("Enter the quantity of 1st items: "))
b=float(input("Enter the cost of 2nd item: "))
n2=int(input("Enter the quantity of 2nd items: "))
c=float(input("Enter the cost of 3rd item: "))
n3=int(input("Enter the quantity of 3rd items: "))
total=(a*n1)+(b*n2)+(c*n3)
if(total>50):
  total=total-((1/10)*total)
  print(total)
else:
  print(total)
