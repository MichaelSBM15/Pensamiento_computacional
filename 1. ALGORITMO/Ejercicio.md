  # 1. DESARROLLA UN ALGORITMO SOBRE ALGUNA ACTIVIDAD EN TU VIDA COTIDIANA.
  ## EJERCICIO 1. "TOMAR AGUA" :) .
 
  ![image](https://user-images.githubusercontent.com/119713702/212167699-791b6b26-3dc0-4feb-96da-7eb05974f629.png)

  	Algoritmo Vida_Diaria
	Dato1 <- garrafon_de_agua
	Dato2 <- jarra
	Dato3 <- vaso
	Escribir 'Tomar el Garrafon de agua.'
	Leer garrafon_de_agua
	Escribir 'Vaciar agua del garrafon de agua hacía la jarra'
	Leer jarra
	Escribir 'Vaciar agua de la jarra hacía el vaso'
	Leer vaso
	Escribir 'Ingiera el agua contenida en el vaso; ¡listo!, !Acaba de hidratarse¡ :)'
	FinAlgoritmo
 
  # 2. DESARROLLA UN ALGORITMO QUE CALCULE LA EDAD DE UNA PERSONA CON BASE A LA OBTENCIÓN DE SU FECHA DE NACIMIENTO. 
  ## EJERCICIO 2. "CALCULA LA EDAD DE ALGUNA PERSONA" :).
  
  ![image](https://user-images.githubusercontent.com/119713702/212204447-71582005-d2dc-4438-8365-3ebf4b50c996.png)

    Algoritmo Calcula_la_edad
	Dato1 <- Nombre_completo_de_la_persona
	Definir Edad, díaActual, mesActual, añoActual Como Entero
	Definir díaNacimiento, mesNacimiento, añoNacimiento Como Entero
	Escribir 'Ingrese por favor su nombre completo'
	Leer Nombre_completo_de_la_persona
	Escribir 'Ingrese por favor la FECHA ACTUAL en el siguiente orden <día, mes, año>'
	Leer díaActual, mesActual, añoActual
	Escribir 'Ingrese por favor su FECHA DE NACIMIENTO en el siguiente orden <día, mes, año>'
	Leer díaNacimiento, mesNacimiento, añoNacimiento
	Edad = añoActual - añoNacimiento
	Si mesNacimiento > mesActual entonces 
	Edad = Edad - 1
	FinSi
	Escribir Nombre_completo_de_la_persona	" su edad actual es: " Edad " años."
	FinAlgoritmo
	
  # 3. REALICE UN ALGORITMO QUE RESUELVA LA SIGUIENTE SITUACIÓN: UN PRODUCTO TENÍA UN PRECIO INICIAL QUE DEBE SOLICITARSE Y AHORA TIENE UN NUEVO VALOR, MAYOR, QUE TAMBIÉN DEBERÁ PEDIRSE, DETERMINE EL PORCENTAJE DE INCREMENTO DEL PRODUCTO.

  ## EJERCICIO 3. "PRODUCTO, PORCENTAJE MAYOR" :).
  
  ![image](https://user-images.githubusercontent.com/119713702/212222247-9d8cef5a-e6c1-42f1-8419-681e73e187a0.png)

	Algoritmo Producto_Porcentaje
	Escribir 'Escriba el nombre del producto'
	Leer Producto
	Escribir 'Ingresa el precio inicial:'
	Leer precio_inicial
	Escribir 'Ingresa el precio nuevo:'
	Leer precio_nuevo
	porcentaje_de_incremento <- 0
	Si precio_inicial<precio_nuevo Entonces
	porcentaje_de_incremento <- 100.0*(precio_nuevo-precio_inicial)/precio_inicial
	FinSi
	Escribir Producto 'Valor de porcentaje de incremento: ',porcentaje_de_incremento
	FinAlgoritmo
