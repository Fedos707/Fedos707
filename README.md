what =  input ('Что будем делать?(+,-):')
a = float( input ('Введите первое число') )
b = float( input ('Введите второе чило') )
if what == ('+'):
    c = a + b
    print ('Результат:' + str(c))
elif what == ('-'):
    c = a - b
    print('Результат:' + str(c))
else:
    print('Введена неверная операция!')
    
