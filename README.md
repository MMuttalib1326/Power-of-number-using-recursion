# Power-of-number-using-recursion
Python language
def power(base,exp):
    assert exp>=0 and int(exp)==exp,'entre a valid number'
    if exp==0:
        return 1 
    if exp==1: 
        return base 
    else:    
        return base*power(base,exp-1)
print(power(4,3))    
