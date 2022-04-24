# Hacer un programa que solicite seis números y que los vaya sumando automáticamente
**INICIO
* DECLARAR num
* FOR i=1; i<=6; i++
* MOSTRAR "Ingrese un número"
* ASIGNAR num
* total: total + num
 * MOSTRAR "La suma final es " + total
 * fin FOR
 **FIN

** ![image](https://user-images.githubusercontent.com/99224635/164957043-59759ec8-fac9-44e8-a374-6b9ff59110d7.png)
 
** ![image](https://user-images.githubusercontent.com/99224635/164957054-44074430-d84a-427c-9858-931c0000e23c.png)



# Multiplicar un número en una tabla del 1 al 10





var num;

var i;

var total;

num = (prompt ("Ingrese el número que desee multiplicar"));

for (i=0; i<=10; i++)

{

 total = num * i

document.write ( num + " x " + i + " = " + total + "<br>");

}
