import random
contador = 0
salir = False
while salir == False:
    numero_usuario = input("Pon un númnero")
    if numero_usuario in range(0,100):
        print("Has de poner un número entre 0 y 100")
    numero_maquina = random.randint(0,100)
    if numero_usuario == numero_maquina:
        print("Has adivinado el número!!")
    else:
        print("No es correcto, inténtalo de nuevo. Intentos:",contador)
    contador = contador + 1
    if contador == 3:
        salir = True
print("No has adivinado el número, inténtalo otra vez más tarde. El número es:", numero_maquina)