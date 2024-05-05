print("Welcome to the Prime Checker!")


num = int(input("Please enter a number: "))


if num < 2:
    is_prime = False
else:
    is_prime = True
    divisor = 2
    while divisor * divisor <= num:
        if num % divisor == 0:
            is_prime = False
            break
        divisor += 1


if is_prime:
    print(num, "is a prime number.")
else:
    print(num, "is not a prime number.")
