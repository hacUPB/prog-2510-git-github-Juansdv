# Programa para calcular el promedio de una lista de números

print("Bienvenido al programa de cálculo de promedios.")
print("Ingresa números uno por uno. Escribe 'salir' para terminar.")

# Lista para almacenar los números
numeros = []

while True:
    entrada = input("Ingresa un número (o escribe 'salir'): ")
    
    if entrada.lower() == 'salir':
        break  # Salir del bucle si el usuario escribe 'salir'
    
    try:
        # Convertir la entrada a número
        numero = float(entrada)
        numeros.append(numero)
    except ValueError:
        print("Por favor, ingresa un número válido.")
        continue

# Verificar si hay números en la lista antes de calcular el promedio
if len(numeros) > 0:
    promedio = sum(numeros) / len(numeros)
    print(f"El promedio de los números ingresados es: {promedio:.2f}")
else:
    print("No ingresaste ningún número.")
