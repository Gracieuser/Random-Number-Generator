num = list(map(int, input('Enter 10 numbers ').split()))
print(num)
mod = num % 2
if mod > 0:
    print("Odd number.")
else:
    print("Even number.")
