# Python
Дз по питону

# Задание 1
num = 123
sum_digits = sum(int(digit) for digit in str(num))
print(f"Задача 1: {num} -> {sum_digits}")

# Задание 2
S = 60
petya = S // 6
katya = 4 * petya
sereja = petya
print(f"Задача 2: {S} -> {petya} {katya} {sereja}")

# Задание 3
ticket = 385916
first_sum = sum(int(d) for d in str(ticket)[:3])
second_sum = sum(int(d) for d in str(ticket)[3:])
print(f"Задача 3: {ticket} -> {'yes' if first_sum == second_sum else 'no'}")

# Задание 4
n, m, k = 3, 2, 4
if k < n * m and (k % n == 0 or k % m == 0):
    print(f"Задача 4: {n} {m} {k} -> yes")
else:
    print(f"Задача 4: {n} {m} {k} -> no")
