# Sum-of-even-numbers-and-odd-numbers in python
n = int(input())
arr = [int(input()) for i in range(n)]
even_sum = 0
odd_sum = 0
for i in range(n):
    if arr[i] % 2 == 0:
        even_sum += arr[i]
    else:
        odd_sum += arr[i]
print("The sum of the even numbers in the array is", even_sum)
print("The sum of the odd numbers in the array is", odd_sum)
