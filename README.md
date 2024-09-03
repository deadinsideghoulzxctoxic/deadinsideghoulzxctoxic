what = input ( "Что делаем? (+ или - или / или * или ** или !): " )
while not (what in ['+', '-', '/', '*', '**', '!']):
    print("Плохааааа, плохааааааааа")
    what = input ("Что делаем? (= или - или / или * или ** или !): " )
while True:
    try:
        a = int(input("Введите первое число: "))
        b = int(input("Введите второе число: "))
    except:
        print("Плохааааа, плохааааааааа")
    else:
        if what == "+":
            c = a + b
            print("Результат: " + str(c))
            break
        elif what == "-":
            c = a - b
            print("Результат: " + str(c))
            break
        elif what == "/":
            c = a / b
            print("Результат: " + str(c))
            break
        elif what == "**":
            c = a ** b
            print("Результат: " + str(c))
            break
        elif what == "*":
            c = a * b
            print("Результат: " + str(c))
            break
        elif what == "!":
            factorial = 1
            if(a%1==0 and a>=0):
                for i in range(1, a+1):
                    factorial = i*factorial
                print(f'{a}! = {factorial}')
            else:
                print('Невозможно вычислить факториал нецелого и/или отрицательного числа!')
        break #Булдаков, Александров
<!---
deadinsideghoulzxctoxic/deadinsideghoulzxctoxic is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
