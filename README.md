# python-series2
# task 1 odd or even:
number = int(input("enter a number:"))
input("enter a number:") prompts the user to type a number.

int(...) converts the user input (which is a string by default) into an integer.

The value is stored in the variable number.
if number % 2 == 0:
    print(f"{number} is even number")
This line checks if the number is divisible by 2 using the modulo operator %.

If the remainder of number ÷ 2 is 0, the number is even.

It prints a message like: "10 is even number"
else:
    print(f"{number} is an odd number")
If the number is not divisible by 2, the program executes this block.

It prints a message like: "7 is an odd number"

#task2:
total_sum = 0
Initializes a variable named total_sum to 0.

This will be used to store the running total as numbers are added.

 for num in range(1, 51):
This is a for loop that goes through each number from 1 to 50, inclusive.

range(1, 51) generates a sequence: 1, 2, 3, ..., 50.

 total_sum += num
Adds the current value of num to total_sum.

This happens in each iteration, effectively summing the numbers from 1 to 50.

print("The sum of integers from 1 to 50 is:", total_sum)
After the loop is finished (i.e., after all numbers have been added), this line prints the final total.

