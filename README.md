# MarcusCoder
name = input("Insert your name:")

print("Hola " + nombre + " como estas")
input("En que puedo ayudarte?:")

print("Dejame ver como puedo resolver tu cuenta")

n1 = int(input("Ingresa el primer numero:"))
n2 = int(input("Ingresa el segundo numero:"))
 
sumax = ( n1 + n2)
restax = (n1 - n2)
multiplicacionx = (n1 * n2)
divisionx = (n1 / n2)
 
cuenta = input("Que cuenta quieres hacer?:")
if cuenta == "suma":
    print(sumax )

if cuenta == "resta":
    print(restax)

if cuenta == "multiplicacion":
    print(multiplicacionx)

if cuenta == "division":
    print(divisionx)
