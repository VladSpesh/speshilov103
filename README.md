# a = 21
# b = 3
# print(a / b)

# def fibonacci_recursive(n):
#     if n <= 1:
#         return n
#     else:
#         return fibonacci_recursive(n-1) + fibonacci_recursive(n-2)
#
# print(fibonacci_recursive(5))

# a = 5
# b = 2
# sum = a + b
# print(sum)

a = int(input())
if a < -5:
    print('Low')
elif -5 <= a <= 5:
    print('Mid')
else:
    print('High')
