def nivel_1():
    print("=== NIVEL 1 ===")
    correctas = 0
    respuesta = input ("cuanto es 10 + 25:")
    if respuesta == "35":
        print ("Correcto!!")
        correctas = correctas +1
    else:
        print ("incorrecto!!")

    respuesta = input ("cuanto es 130 + 30:")
    if respuesta == "160":
        print ("Correcto!!")
        correctas = correctas +1
    else:
        print ("incorrecto!!")

    respuesta = input ("cuanto es 39 + 47:")
    if respuesta == "86":
        print ("Correcto!!")
        correctas = correctas +1
    else:
        print ("incorrecto!!")


    if correctas >= 2:
        print ("Pasaste de nivel!!")
        nivel_2()
    else:
        print ("no pasaste de nivel- intentalo de nuevo")
        nivel_1()


def nivel_2():
    print ("=== NIVEL 2 ===")
    correctas = 0
    respuesta = input ("cuanto es 30 - 18")
    if respuesta == "12":
        print ("Correcto!!")
        correctas = correctas +1
    else:
        print ("incorrecto!!")

    respuesta = input ("cuanto es 95 - 23")
    if respuesta == "72":
        print ("Correcto!!")
        correctas = correctas +1
    else:
        print ("incorrecto!!")

    respuesta = input ("cuanto es 86 - 79")
    if respuesta == "7":
        print ("Correcto!!")
        correctas = correctas +1
    else:
        print ("incorrecto!!")
    if correctas >= 2:
        print ("Pasaste de nivel!!")
        nivel_3()
    else:
        print ("no pasaste de nivel - intentalo de nuevo ")
        nivel_2()


def nivel_3():
    print ("=== NIVEL 3 ===")
    correctas = 0
    respuesta = input ("cuanto es 4 * 5:")
    if respuesta == "20":
        print ("Correcto!!")
        correctos = correctos +1
    else:
        print ("incorrecto!!")

    respuesta = input ("cuanto es 5 * 7:")
    if respuesta == "35":
        print ("Correcto!!")
        correctos = correctos +1
    else:
        print ("incorrecto!!")

    respuesta = input ("cuanto es 30 / 5:")
    if respuesta == "6":
        print ("Correcto!!")
        correctos = correctos +1
    else:
        print ("incorrecto!!")
    if correctas == 3:
        print ("Has ganado el juego!!")
        print ("Felicitaciones!!")
    else: 
        print ("no has logrado ganarlo")


    



print (" ===== MATEMATICAS =====")
print ("1-jugar")
print ("2-salir")
opcion = input("elegi una opcion:")

if opcion == "1":
    nivel_1()
else:
    print ("Hasta Luego!!")
