# pr5-unidad2 sepulveda gonzalez angel alejandro 3W

# 5. Preguntar por los números de la lotería y mostrarlos en orden de menor a mayor.

numeros_loteria = []  # Inicializo una lista vacía para almacenar los números de la lotería

cantidad_numeros = int(input("¿Cuántos números de la lotería quieres ingresar? "))  # Solicito al usuario cuántos números ingresará

for _ in range(cantidad_numeros):  # Recorro la cantidad de números que se ingresarán

  numero = int(input("Ingrese un número de la lotería: "))  # Solicito al usuario ingresar un número de la lotería
    
  numeros_loteria.append(numero)  # Agrego el número ingresado a la lista de números de la lotería

numeros_loteria.sort()  # Ordeno la lista de números de menor a mayor

print("Números de la lotería en orden de menor a mayor:", numeros_loteria)  # Despliego los números ordenados

![image](https://github.com/user-attachments/assets/3cb43e1a-99ce-43de-a2d3-a6e854c02b7e)
![image](https://github.com/user-attachments/assets/39e1bfac-d9a7-4272-9168-4e90bc4de862)
