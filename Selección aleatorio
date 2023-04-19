import random

# ingresar nombres separados por coma
nombres_str = input("\n \t Ingrese los nombres separados por coma: \n")
nombres = nombres_str.split(",")

# ingresar temas separados por coma
temas_str = input("\n \t Ingrese los temas separados por coma: \n ")
temas = temas_str.split(",")

# unir las listas de manera aleatoria
random.shuffle(nombres)
random.shuffle(temas)

# imprimir las parejas formadas
for i in range(len(nombres)):
    print("\n " +nombres[i] + " - " + temas[i] )

# esperar al usuario para salir
input("\nPresione Enter para salir...")
