# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

* Programa que pida un número y diga si es positivo o negativo
* Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.

**1 INICIO

**2 DECLARAR(LETRA)char

**3 MOSTRAR: "ESCRIBA UNA LETRA"

**4 ASIGNAR LETRA

**5 IF LETRA = S || LETRA = N

**6 MOSTRAR: "LETRA VÁLIDA"

**7 ELSE 

**8 MOSTRAR: "LETRA INVÁLIDA"

**9 FIN


![image](https://user-images.githubusercontent.com/99224635/164295148-47e105ae-3057-4332-82da-d09d66b0063d.png)


![image](https://user-images.githubusercontent.com/99224635/164535682-6320d028-ecf5-4ebf-8650-898feb81a531.png)




* Un programa que pida una letra y detecte si es una vocal. 

**INICIO

**DECLARAR(vocal)char

**MOSTRAR: "ESCRIBA UNA LETRA PARA SABER SI ES VOCAL O NO"

**ASIGNAR:vocal

**CASE (vocal)

*** "A" o "a":mostrar ("Es vocal")
*** "E" o "e":mostrar ("Es vocal")
*** "I" o "i":mostrar ("Es vocal")
*** "O" o "o":strar ("Es vocal")
*** "U" o "u"mostrar ("Es vocal")
SiNo: "No es Vocal"
**7 FIN

![image](https://user-images.githubusercontent.com/99224635/164535350-47a89e87-ea6c-4e38-9efa-ecb3c5866255.png)


![image](https://user-images.githubusercontent.com/99224635/164535419-a97b1af4-389b-4722-9384-c398b61d2101.png)



* Programa que pida 3 números y los muestre en pantalla de menor a mayor.  

**INICIO

**DECLARAR(NUM1, NUM2, NUM3)Int

**MOSTRAR: "ESCRIBA TRES NÚMEROS"

**ASIGNAR NUM1

**ASIGNAR NUM2

**ASIGNAR NUM3

**IF NUM1 < NUM2 &&  NUM2 < NUM3 
**MOSTRAR NUM1, NUM2, NUM 3
** IF NUM 3 < NUM 2
** MOSTRAR NUM1, NUM 3, NUM 2

**IF NUM2 < NUM1 && NUM1 < NUM3
**MOSTRAR NUM2, NUM1, NUM 3
** IF NUM 3 < NUM 1
** MOSTRAR NUM2, NUM 3, NUM 1

**IF NUM3 < NUM2 && NUM2 < NUM1
**MOSTRAR NUM3, NUM2, NUM 1
** IF NUM 1 < NUM 2
** MOSTRAR NUM3, NUM 1, NUM 2

**FInN

![image](https://user-images.githubusercontent.com/99224635/164303810-649356e1-6638-48a5-9240-ce96f41058d9.png)


![image](https://user-images.githubusercontent.com/99224635/164371535-88d0275a-a844-43bd-9cb1-39750f33c0d4.png)


![image](https://user-images.githubusercontent.com/99224635/164373349-c506abac-f44d-4c71-825f-e6d5a69aefed.png)



* De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.
**1 INICIO

**2 DECLARAR(mes)Int

**3 MOSTRAR: "INGRESE UN NÚMERO DEL 1 AL 12"

**4 ASIGNAR mes

**5 CASE (mes)

*** 1:mostrar (Enero)

*** 2:mostrar (Febrero)

*** 3:mostrar (Marzo)

*** 4:mostrar (Abril)

*** 5:mostrar (Mayo)

*** 6:mostrar (Junio)

*** 7:mostrar (Julio)

*** 8:mostrar (Agosto)

*** 9:mostrar (Septiembre)

*** 10:mostrar (Octubre)

*** 11:mostrar (Noviembre)

*** 12:mostrar (Diciembre)

*** SiNo:mostrar ("Error""

**7 FIN

![image](https://user-images.githubusercontent.com/99224635/164530538-9b84a806-a55f-49d7-8ebe-47cf5e312614.png)


![image](https://user-images.githubusercontent.com/99224635/164530578-1b1a0db9-b89d-4418-bfc6-6377abe33096.png)



* De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.
* Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.
