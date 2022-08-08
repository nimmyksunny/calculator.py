# python calculator
operation=input('''please type in the math operation you like: 
+ for addition
- for substraction
* for multiply
/ for division
''')
num1=int(input("enter the number :"))
num2=int(input("enter the number :"))

if operation== '+':
    print('{} +{}='.format(num1,num2))
    print(num1+num2)
elif operation== '-':
    print(num1-num2)
elif operation== '*':
    print(num1*num2)
elif operation== '/':
    print(num1/num2)
else:
    print("you not input the valid operation. ")
    

