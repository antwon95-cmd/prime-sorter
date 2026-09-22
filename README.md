# prime-sorter

def prime(n):
    new=list()  # Creates list for number entered
    for num in range(1,n):  # reads every number in range
        for item in range(2,num): # checks if num in range is divisible by 2
            if num%item==0:
                break
        else:
            new.append(num)
    return print(new) # returns prime numbers
prime(100)
