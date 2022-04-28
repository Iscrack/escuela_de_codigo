# ESCRIBIR 10 CALIFICACIONES. CONTABILIZAR LAS QUE SEAN MENOR DE 7 Y LAS QUE SEAN MAYORES A 7
Algoritmo Diez_Calificaciones
	calif = 0
	i = 0
	men = 0
	may = 0
	Mientras i < 10  Hacer i = i + 1
		Escribir "Escribir calificación " i
		Leer calif
		Si men < 7 Entonces
			men = men + 1
		SiNo
			Si may > 7 Entonces
				may = may + 1
			FinSi
		Fin Si
	Fin Mientras
	Escribir "El total de calificaciones menor a 7 es " men
	Escribir "El total de calificaciones mayor a 7 es " may
FinAlgoritmo

![image](https://user-images.githubusercontent.com/99224635/165600288-0b91d670-f7b9-481e-92af-8623b17fe50a.png)


# RETO ESCRIBIR 10 CALIFICACIONES. CONTABILIZAR LAS QUE SEAN MENOR DE 7 Y LAS QUE SEAN MAYORES A 7. MARCAR ERROR SI ES MENOR A CERO Y MAYOR A DIEZ
Algoritmo Reto_Diez_Calificaciones
	calif <- 0
	i <- 1
	men <- 0
	may <- 0
	Mientras i<11 Hacer
		Escribir 'Escribir calificación ',i
		Leer calif
		Mientras calif<0 O calif>10 Hacer
			Escribir 'ERROR. Escribir calificación ',i
			Leer calif
		FinMientras
		i <- i+1
		Si calif<7 Entonces
			men <- men+1
		SiNo
			Si calif>7 Entonces
				may <- may+1
			FinSi
		FinSi
	FinMientras
	Escribir 'El total de calificaciones menor a 7 es ',men
	Escribir 'El total de calificaciones mayor a 7 es ',may
FinAlgoritmo

![image](https://user-images.githubusercontent.com/99224635/165663922-c601728c-2215-4f94-859a-bdd86322ea59.png)




![image](https://user-images.githubusercontent.com/99224635/165600428-f28f744d-9b1d-45ec-99bd-f482f9c20b85.png)
**falta si estatura es menor a 110 y mayor a 225
