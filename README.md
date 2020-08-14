# SCAMP-Assessment
Code submition for SheCode Africa
# let the function be called fibonacci
# Python 
def fibonacci(i):
    if i==0:
        return 0
    elif i==1:
        return 1
    else:
       return fibonacci (i-2) + fibonacci (i-1)
    
# I choose 24 as my unique number
for n in range(24):
    print (fibonacci(n))
