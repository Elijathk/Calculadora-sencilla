import operator

action = {
    "/" : operator.truediv,
    "+" : operator.add.
    "-" : operator.sub,
    "*" : operator.mul
namber1=int(input("introduzca el numero que desea calcular"))
Operators=input("introduzca el operador deseado / + - *: ")
nambre2=int(input("Introduzca el siguiente numero de la operacion: "))

print (action[Operators](namber1, namer2))
