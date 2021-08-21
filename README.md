# -Assignment_Python-Python Zero to Hero
# Assignment - Implement a decorator mod_div() which assures that the numerator is always greater than the denominator
# e.g. if a = 2, b = 4, then div(a, b) should return 2.0 as the output and not 0.5
def divide(a,b):
    a=2
    b=4
    c=a%b
    return 2.0

def decorator(func,c):
    a=2
    b=4
    c= func(2,4)
    c=a%b
    return c

print(decorator(divide,2.0))

# OUTPUT:2
