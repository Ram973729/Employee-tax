# Employee-tax
empo=input('Enter empo:')
empname=input('Enter Employee Name:')
empdesig=input('Enter designation:')
salary=int(input('Enter Salary:'))
da=int(input('Enter Daily Allowance:'))
ta=int(input('Enter Travelling Allowance:'))
hra=int(input('Enter House Rental Allowance:'))
netsalary=salary+da+ta+hra
if netsalary>100000:
    tax=netsalary*10/100
elif netsalary>50000:
    tax=netsalary*7/100
elif netsalary>40000:
    tax=netsalary*4/100
elif netsalary>20000:
    tax=netsalary*2/100
else:
    tax=0
print(empo)    
print(empname)
print(empdesig)
print('Tax is',tax)
