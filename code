mport random

symbols = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

while True:
    length = int(input("Введите длину пароля: "))
    password = ""

    for i in range(length):
        password += symbols[random.randint(0, len(symbols)-1)]

    print("Сгенерированный пароль:", password)

    stop = input("Хотите сгенерировать еще один пароль? (y/n) ")
    if stop.lower() != "y":
        break
