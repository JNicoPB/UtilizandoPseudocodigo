# UtilizandoPseudocodigo
Algoritmo que permite mostrar un producto con sus caracteristicas

_Escribir un programa en pseudocódigo que permita escribir un algoritmo que imprima el nombre de un artículo, el código, precio original y su precio con descuento. El descuento lo hace en base al código, si el código es 1, el descuento es del 10% y si el código es 2 el descuento es del 20%. (solo existen 2 códigos)._

```Algoritmo ActividadUtilizandoPseudocodigo
	Escribir "Hola bienvenido a tu tienda virtual"
	Escribir "Escribe el nombre del articulo que deseas"
	Leer Articulo
	Escribir "Escribe el codigo del articulo para acceder al descuento: 1 o 2"
	Leer Codigo
	Escribir "Escribe el precio de tu articulo $"
	Leer Precio_sin_descuento
	
	Si Codigo=1 Entonces
		Descuento=Precio_sin_descuento*0.10
		Total_a_pagar=Precio_sin_descuento-Descuento
	SiNo
		Descuento=Precio_sin_descuento*0.20
		Total_a_pagar=Precio_sin_descuento-Descuento
	Fin Si
	
	Imprimir "Nombre del articulo " Articulo
	Imprimir "Codigo del articulo " Codigo
	Imprimir "Precio sin descuento $" Precio_sin_descuento
	Imprimir "Tu descuento es de: $" Descuento
	Imprimir "En total pagas: $" Total_a_pagar
	Imprimir "Gracias por tu compra, vuelve pronto"
	
FinAlgoritmo```

