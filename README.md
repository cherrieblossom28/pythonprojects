# pythonprojects
exercises
#######INSTRUCTIONS########
# Given N numbers: the first number in the input is N, after that N integers are given. Count the number of zeros among the given integers # and print it.
#######INSTRUCTIONS########
h = int(input())
res = 0
num = 1
for x in range(h):
    x = int(input())
    if x == 0:
        res += num 
print(res)
