Variable is used to store our data 







Function are  used to perform same tasks ,by calling one method at a time 
def double(my_number):
    Actions
    return my_number * 2
    
eg:
def double(my_number):
    return my_number * 2

## create a new variable called `my_var` which equals
## the value returned by calling double() on the value 5.
my_var = double(5)
## print our new `my_var`
print(my_var)
If Statement
------------
If the condition is true, it prints out the indented expression. If the condition is false, it skips printing the indented expression.

'''In this program, 
we check if the number is positive or
negative or zero and 
display an appropriate message'''

num = 3.4

# Try these two variations as well:
# num = 0
# num = -4.5

if num > 0:
    print("Positive number")
elif num == 0:
    print("Zero")
else:
    print("Negative number")
![ifelse9_nk5ugf](https://user-images.githubusercontent.com/85831369/121815558-b8a55080-cc94-11eb-8a90-970a6a2b82d9.png)
