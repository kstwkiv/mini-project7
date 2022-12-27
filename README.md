# mini-project7
def is_fibonacci(num):
    a,b=0,1
    while b<=num:
        if b==num:
            return True
        a,b=b,a+b
    return false
def are_fibonacci(nums):
    return
all(is_fibonacci(num)
    for num in nums)
print(is_fibonacci(0))
print(is_fibonacci(7))
print(are_fibonacci([0,7]))
print(are_fibonacci([0,1,2,3]))
