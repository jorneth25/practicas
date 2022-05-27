# practicas
#EJERCICIO PROPUESTO: SE SOLICITA DESARROLLAR UNA CALCULADORA, CON LAS SIGUIENTES CARACERISTICAS:#
# DEBERA SER CAPAZ DE CALCULAR OPERACIONES DE; SUMA, RESTA, MULTIPLICACION, DIVISION, DIVISION ENTERA, 
# EXPONENTE, MODULO#
# LA CALCULADORA DEBERA TENER UN MENÚ DE OPCIONES DONDE EL USUARIO PUEDA ELEGIR QUE OPERACIONES DESEA EJECUTAR#
# LA CALCULADORA DEBERA SOLICITAR UNICAMENTE DOS VALORES POR CADA OPERACION##

print("********************")
print("Calculadora CASIOPEA")
print("******************** \n\n")

print("Menu de Opciones")
print("Suma (1)")
print("Resta (2)")
print("Multiplicacion (3)")
print("Potenciacion (4)")
print("Division (5)")
print("Division Entera (6)")
print("Modulo o Resto (7)")

operacion = int(input("Que operacion de deseas realizar "))

if operacion == 1:
    print("Elegiste Suma")
    numero = float(input("Ahora introduce un numero "))
    numero += float(input("Ahora introduce otro numero "))
    print("el resultado es", numero)
elif operacion == 2:
    print("Elegiste Resta")
    numero = float(input("Ahora introduce un numero "))
    numero -= float(input("Ahora introduce otro numero "))
    print("el resultado es", numero)
elif operacion == 3:
    print("Elegiste Multiplicación")
    numero = float(input("Ahora introduce un numero "))
    numero *= float(input("Ahora introduce otro numero "))
    print("el resultado es", numero)
elif operacion == 4:
    print("Elegiste Potenciación")
    numero = float(input("Ahora introduce un numero "))
    numero **= float(input("Ahora introduce otro numero "))
    print("el resultado es", numero)
elif operacion == 5:
    print("Elegiste Division")
    numero = float(input("Ahora introduce un numero "))
    numero /= int(input("Ahora introduce otro numero "))
    print("el resultado es", numero)
elif operacion == 6:
    print("Elegiste Division entera")
    numero = float(input("Ahora introduce un numero "))
    numero //= float(input("Ahora introduce otro numero "))
    print("el resultado es", numero)
elif operacion == 7:
    print("Elegiste Módulo o resto")
    numero = float(input("Ahora introduce un numero "))
    numero %= float(input("Ahora introduce otro numero "))
    print("el resultado es", numero)
else:
    print("el numero seleccionado no corresponde a una opción")

