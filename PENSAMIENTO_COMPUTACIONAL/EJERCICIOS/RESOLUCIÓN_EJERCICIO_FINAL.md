Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero en 10 intentos, que imprima si lo atina, y si no le indique si el número ingresado es mayo o menor al almacenado, así como el número de intemtos restantes.

Algoritmo ADIVINANZA
	sec = azar (100)+1
	num = 0
	i=10
	escribir "Adivina un número del 1 al 999"
	leer num
	Mientras num<>sec y i>1 Hacer
		i = i -1
		si num >sec escribir "el número es mayor al número secreto. "
			sino escribir "el número es menor al número secreto."
			FinSi
			Escribir "Te quedan " i " intentos"
			escribir "Ingresa otro número del 1 al 999"
			leer num
		Fin Mientras
		si num=sec Escribir "Eres lo máximo, le atinaste en " i "intentos"
		sino escribir "Se terminaron tus oportunudades, el numero era " , sec
		FinSi
FinAlgoritmo
