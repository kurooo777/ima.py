def main():
    print "Числа Фибоначчи"
    x1=1
    x2=2
    n=input("напишите порядковый номер вашего числа:")
    y=2
    while y<n:
        sum=x1+x2
        x1=x2
        x2=sum
        y=y+1
    print sum
main()
