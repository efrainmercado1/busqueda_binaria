p_max = 20
p_min = 0
numero_escogido = False
num_input = input("Escoje un número entre el 0 y el 20. \n")
su_numero = num_input

while not numero_escogido:
    
    su_numero = (p_max + p_min)//2
    
    print('¿Es ' + str(su_numero) + ' tu número? \n')
    
    inpu_usuario = input('Si el número es alto, presione "a". Si es bajito "b". Si es su número "c". \n')

    if inpu_usuario == 'c':
        numero_escogido = True
    elif inpu_usuario == 'a':
        p_max = su_numero
    elif inpu_usuario == 'b':
        p_min = su_numero
    else:
        print('Lo que ingresó no es válido.')

print('¡Encontramos tu número! ' +str(su_numero) + ' es tu numero!')
