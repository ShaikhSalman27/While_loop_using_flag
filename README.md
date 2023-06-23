# While_loop_using_flag

# Set a variable flag = True, num = 5
# Run a while loop till flag = True
# Inside the while loop -
        # Increment the value of num by 5
        # If value of num is greater then 50, set flag to be False


flag = True
num = 5
while flag:
    print(num)
    num += 5
    if num>50:
        flag = False
