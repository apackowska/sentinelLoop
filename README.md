# sentinelLoop



def sentinel_loop():
    total = 0
    count = 0
    x = float(input("What is a number, negative to quit: "))
    while x >= 0:
        total += x
        count += 1
        x = float(input("What is a number, negative to quit: "))
    print("Average of the numbers is", total / count)

sentinel_loop()
