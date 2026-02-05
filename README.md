# NAME:POOJA S
# REG NO: 212223040146
# Experiment - 4
## Armstrong Number

# Aim : 
Write a python program to check the number is Armstrong number or not and inspect for failures. 

# Algorithm :
1.	Start the program.
2. Read an integer input number.
3. Initialize the variables current_digit, sum = 0, and num = number.
4. Repeat Steps 5 to 7 until num > 0
5. current_digit = (num % 10).
6. sum = sum + (current_digit * current_digit * current_digit).
7. num = num / 10.
8. Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9. Stop the program. 

# Program :
```
num = int(input("Enter a number: "))
num_str = str(num)
power = len(num_str)
armstrong_sum = sum(int(digit) ** power for digit in num_str)
if num == armstrong_sum:
    print(num, "is an Armstrong number.")
else:
    print(num, "is not an Armstrong number.")
```
# Output :
<img width="379" height="128" alt="Screenshot 2025-08-25 111436" src="https://github.com/user-attachments/assets/c725aa85-b507-48bf-989f-c1203235bcd4" />

<img width="378" height="130" alt="Screenshot 2025-08-25 111452" src="https://github.com/user-attachments/assets/091c019c-3a6c-4d0f-b43d-a67e2d8c0d92" />

# Result :
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.
