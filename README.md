#work4.variant1
LR4 DKIP-282
Составить программу, которая печатает таблицу умножения
и сложения натуральных чисел в десятичной системе счисления.

def multiplication_table():
    print("Табл умнож.:")
    for i in range(1, 11):
        for j in range(1, 11):
            result = i * j
            print(f"{i} × {j} = {result}")
        print()
                                        #Изменение от Княжева
def addition_table ():
    print("Табл слож.:")
    for i in range(1, 11):
        for j in range(1, 11):
            result = i + j
            print(f"{i} + {j} = {result}")
        print()

multiplication_table()
print()
addition_table()
