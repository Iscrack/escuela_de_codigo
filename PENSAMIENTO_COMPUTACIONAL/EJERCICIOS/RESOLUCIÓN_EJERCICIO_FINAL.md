# Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero en 10 intentos, que imprima si lo atina, y si no le indique si el número ingresado es mayo o menor al almacenado, así como el número de intemtos restantes.

Algoritmo ADIVINANZA
	sec = azar (100)+1
	num = 0
	i=10
	escribir "Adivina un número del 1 al 99"
	leer num
	Mientras num<>sec y i>1 Hacer
		i = i -1
		si num >sec escribir "El número es mayor al número secreto. "
		sino escribir "El número es menor al número secreto."
		FinSi
		Escribir "Te quedan " i " intentos"
		escribir "Ingresa otro número del 1 al 99"
		leer num
	Fin Mientras
	si num=sec Escribir "Eres lo máximo, le atinaste en " i " intentos"
	sino escribir "Se terminaron tus oportunudades, el numero era " , sec
	FinSi
FinAlgoritmo



# RETO. Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero del 1 al 100 en 10 intentos; que imprima si lo atina, y si no, le indique si el número ingresado es mayor o menor al almacenado, así como el número de intemtos restantes. Si el número ingresado es menor a cero o mayor a cien marque error y no contabilice el intento.

Algoritmo RETO_ADIVINANZA
	sec <- azar(100)+1
	num <- 0
	i <- 10
	Escribir 'Adivina un número secreto que va del 1 al 99. Tienes 10 intentos'
	Escribir 'Ingresa el número'
	Leer num
	Mientras num<0 O num>100 Hacer
		Escribir 'Error. El número debe ser entre 1 y 100. Ingresa el número. Tienes 10 intentos'
		Leer num
	FinMientras
	Mientras num<>sec Y i>1 Hacer
		Si num>sec Entonces
			Escribir 'El número es mayor al número secreto. '
		SiNo
			Escribir 'El número es menor al número secreto.'
		FinSi
		i <- i-1
		Escribir 'Te quedan ',i,' intentos'
		Escribir 'Ingresa el número'
		Leer num
		Mientras num<0 O num>100 Hacer
			Escribir 'Error. El número debe ser entre 1 y 100. Ingresa el número. Te quedan ',i,' intentos'
			Leer num
		FinMientras
	FinMientras
	Si num=sec Entonces
		Escribir 'Eres lo máximo, acertaste en ', 11-i,' intentos'
	SiNo
		Escribir 'Se terminaron tus oportunudades, el numero era ', sec
	FinSi
FinAlgoritmo

![image](https://user-images.githubusercontent.com/99224635/165885984-3cdfde0f-42e0-49c7-a724-7b4fdfc1b1e9.png)

