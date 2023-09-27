### Nicolas Maya
---
*Programa Ingenieria de Sistemas*

![Alt](https://github.com/usernicolasmaya/usernicolasmaya/assets/143303604/0d3f619e-78e9-43db-99b5-d6af04cca144)


- Nicolas Maya
- Adquiriendo conocimientos en Phyton y Java
- Estudio en universidad mariana ing de sistemas

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=usernicolasmaya&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=usernicolasmaya&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=usernicolasmaya&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://visitcount.itsvg.in/api?id=usernicolasmaya&icon=0&color=0)](https://visitcount.itsvg.in)

# Apo2
![Logo Java](https://seeklogo.com/images/J/java-logo-7833D1D21A-seeklogo.com.png)

# Apo2 Funciones.

Se creo en eclipse un programa que le pide al usuario ingresar dos numero enteros para con estos valores multiplicar, resta, dividir y sumar.  

## Empezando

Estas instrucciones le permitirán obtener una copia del proyecto en funcionamiento en su máquina local para fines de desarrollo y prueba.

### Requisitos previos

Instalar Eclipse en tu computador

```
Link de instalación de Eclipse: https://www.eclipse.org/downloads/
```

### Instalación

Importar la libreria JOptionPane.


```
import javax.swing.JOptionPane es para que funcione JOptionPane.
```

## Ejecutando las pruebas

```
Para ejecutar las pruebas, debemos darle control+f11 para iniciar la aplicación.
```

### Dividir en pruebas de principio a fin

```
Este proyecto nos ayuda a solucinar operaciones primarias
Como resta, suma, multiicacion y division
Ingresando numeros por teclado
```

### Y pruebas de estilo de codificación.

```
package proyecto;

import javax.swing.JOptionPane;
//Se importa una nueva libreria que permite ingresar datos de manera manual

public class proyecto3 {
	public static void main(String[]args) {
		JOptionPane.showMessageDialog(null,"Digite un valor\n");
//Se muestra un mensaje de lo que hara el programa
		int x=Integer.parseInt(JOptionPane.showInputDialog(null,"Ingrese el primer numero"));
//Se pide al usuario que ingrese un valor entero
		int y=Integer.parseInt(JOptionPane.showInputDialog(null,"Ingrese el segundo numero"));
//Se pide al usuario que igrese el segundo valor entero
		int t=suma(x,y);
//Se define t como suma y esta misma como un valor entero
		int z=resta(x,y);
//Define z como resta y esta misma como un valor entero
		int m=multiplicacion(x,y);
//Define m como multiplicacion y esta misma como un valor entero
		int d=division(x,y);
//Define m como division y esta misma como un valor entero
		JOptionPane.showMessageDialog(null,"El total de la suma es: " + t ,"suma",1);
		JOptionPane.showMessageDialog(null,"El total de la resta es: " + z,"resta",1);
		JOptionPane.showMessageDialog(null,"El total de la multiplicacion es: " + m,"multiplicacion",1);
		JOptionPane.showMessageDialog(null,"El total de la division es: " + d,"division",1);
//Se muestra un mensaje de lo que hara el programa
	}
		public static int suma(int a,int b) {
			return a+b;
//Esto permite hacer la operacion y llamar en los parametos para poder generar la suma 
		}
		
		public static int resta(int x,int y) {
			return x-y;
//Esto permite hacer la operacion y llamar en los parametos para poder generar la resta
			
		}
		public static int multiplicacion(int a,int b) {
			return a*b;
// esto permite hacer la operacion y llamar en los parametos para poder generar la multiplicacion 
	}
		public static int division(int a,int b) {
			return a/b;
// esto permite hacer la operacion y llamar en los parametos para poder generar la division
}
}
```

## Despliegue (Deployment)

Agregue notas adicionales sobre cómo implementar esto en un sistema en vivo


## Construido con

Dropwizard : el marco web utilizado
Maven - Gestión de dependencias
ROMA : se utiliza para generar canales RSS

## Versionado

Usamos Git para el control de versiones. Para conocer las versiones disponibles, consulte las etiquetas en este repositorio .

## Autores

* **Juan Zambrano**
* **Danna Lagos**
* **Anyeli Jaramillo** 


## Licencia

Este proyecto tiene la licencia MIT; consulte el archivo LICENSE.md para obtener más detalles.

## Expresiones de gratitud (Acknowledgments)


* Un consejo para cualquiera cuyo código se haya utilizado
* Inspiración
* etc
