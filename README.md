# programa-de-ad-n-y-pedro}
def suma(a, b):
    return a + b

def resta(a, b):
    return a - b

def main():
    print("Programa que suma y resta dos números")
    num1 = float(input("Introduce el primer número: "))
    num2 = float(input("Introduce el segundo número: "))
    operacion = input("¿Qué operación deseas realizar? (suma/resta): ").strip().lower()

    if operacion == "suma":
        resultado = suma(num1, num2)
        print(f"La suma de {num1} y {num2} es: {resultado}")
    elif operacion == "resta":
        resultado = resta(num1, num2)
        print(f"La resta de {num1} y {num2} es: {resultado}")
    else:
        print("Operación no reconocida. Usa 'suma' o 'resta'.")def multiplicar(a, b):
    return a * b

def dividir(a, b):
    if b == 0:
        return "Error: No se puede dividir entre cero."
    return a / b

def main():
    print("Programa que multiplica y divide dos números.")
    a = float(input("Ingresa el primer número: "))
    b = float(input("Ingresa el segundo número: "))

    print(f"{a} * {b} = {multiplicar(a, b)}")
    resultado_div = dividir(a, b)
    print(f"{a} / {b} = {resultado_div}")

if __name__ == "__main__":
    main()

if __name__ == "__main__":
    main()
