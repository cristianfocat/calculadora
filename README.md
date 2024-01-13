while True:
    print('Escolha Uma Operação:\n1-soma\n2-sub\n3-div\n4-mul\n5-pot')
    escolha=int(input('escolha uma opção: '))
    n1=int(input('digite primeiro numero: '))
    n2=int(input('escolha segundo numero: '))
    if escolha == 1:
        print(f'{n1}+{n2}={n1+n2}')
    elif escolha == 2:
        print(f'{n1}-{n2}={n1-n2}')
    elif escolha == 3:
        print(f'{n1}/{n2}={n1/n2}')
    elif escolha == 4:
        print(f'{n1}x{n2}={n1*n2}')
    elif escolha == 5:
        print(f'{n1} elevado {n2}= {n1**n2}')
    else:
        print('Não existe essa opção')

    con = input('desja continuar?: ').strip().lower()
    if con == "s":
        continue
    else:
        print('Ate Á Proxima!')
        break
