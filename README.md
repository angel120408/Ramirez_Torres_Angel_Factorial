# Examen Del Primer Parcial. Codigo Creado Por Ramirez Torres Angel Manuel De 3°W
- El factorial de un número entero se denota de la siguiente manera
«n!» y su resultado es n!=n*(n-1)*(n-2)*…*1. Por ejemplo: 5!=5*4*3*2*1
siendo el resultado 120. Se pide desarrollar un programa que lee un valor N
y determine su factorial.

print(" ")
d = "Examen del primer parcial:" #Se declara la variable 'd'
a = "/ Alumno: Ramirez Torres Angel Manuel"#Se declara la variable 'a'
b = "/ Grado y Grupo: 3°W"#Se declara la variable 'b'
c = "/ Mi numero de contro es: 1206"#Se declara la variable 'c'
espacio = (" ")#Se declara la variable 'espacio'
info = d +espacio + a + espacio + b + espacio + c #Aqui se juntan los valores (d, a, b, c, espacio) para crear una sola variable 
print (info)#Muestra el contenido de la variable 'info'
print(" ")

def main():
    """Calcula el factorial de un número entero no negativo."""
    
    # Solicita al usuario que ingrese un número entero no negativo
    n = int(input("Ingrese un número entero no negativo: "))
    
    # Verifica que el número sea no negativo
    if n < 0:
        print("Por favor, ingrese un número entero no negativo.")
        return  # Termina la función si el número es negativo

    # Calcula el factorial
    factorial = 1  # Inicializa la variable factorial en 1
    for i in range(1, n + 1):
        factorial *= i  # Multiplica el factorial por cada número hasta n
    
    # Imprime el resultado
    print(f"El factorial de {n} es {factorial}.")

# Ejecuta la función principal
if __name__ == "__main__":
    main()

![image](https://github.com/user-attachments/assets/f2dd7179-7641-42ca-b5d1-bc5b3d1599eb)
![image](https://github.com/user-attachments/assets/aa33f79e-7ded-4d52-beb5-9320b30f4120)
![image](https://github.com/user-attachments/assets/090a1b3d-c147-40b3-a612-088ea03de678)



