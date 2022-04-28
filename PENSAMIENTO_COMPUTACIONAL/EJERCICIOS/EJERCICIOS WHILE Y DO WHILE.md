# ESCRIBIR 10 CALIFICACIONES. CONTABILIZAR LAS QUE SEAN MENORES A 7 Y LAS QUE SEAN MAYORES A 7
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


# RETO ESCRIBIR 10 CALIFICACIONES. CONTABILIZAR LAS QUE SEAN MENORES A 7 Y LAS QUE SEAN MAYORES A 7. MARCAR ERROR SI LA CALIFICACIÓN ES MENOR A CERO O MAYOR A DIEZ
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



# PROMEDIO DE ALTURA 
Algoritmo Promedio_Estaturas
prom = 0
alt = 0
i = 0
suma = 0
personas = 0
Escribir "¿De cuántas personas desea leer la altura?"
leer personas
Mientras i < personas Hacer i = i + 1
	Escribir "Ingresa altura"
	leer alt
	suma = suma + alt 
	prom = suma / personas
Fin Mientras
Escribir "El promedio de altura de las " personas " personas, es de " prom

FinAlgoritmo

![image](https://user-images.githubusercontent.com/99224635/165665571-a7490381-980e-4611-9c25-a84263b74855.png)



# RETO PROMEDIO DE ALTURA CON RANGO INFERIOR Y SUPERIOR
lgoritmo Promedio_Estaturas
	prom = 0
	alt = 0
	i = 0
	suma = 0
	personas = 0
	Escribir "¿De cuántas personas desea leer la altura?"
	leer personas
	Mientras i < personas Hacer Escribir "Ingresa altura. Ejemplo 160"
		leer alt
		Mientras alt<110 o alt>230 Hacer
			Escribir "ERROR. Altura Inválida. Ingrese altura"
			leer alt
		FinMientras
		suma = suma + alt 
		prom = suma / personas
		i = i + 1
	Fin Mientras
	Escribir "El promedio de altura de las " personas " personas, es de " prom
FinAlgoritmo


![image](https://user-images.githubusercontent.com/99224635/165666890-a8cbccf7-41ab-4cbb-b269-9e4c27ffffd2.png)


