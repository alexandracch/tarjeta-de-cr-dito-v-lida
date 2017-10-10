# ***Tarjeta de Crédito Válida***
## **Página web de validación de tarjetas de crédito**

Esta página valida tarjetas de crédito en base al algoritmo de Luhn

Flujo grama del código: ![recursos](https://fotos.subefotos.com/dc0be22265447ab1a66f2968bdb99a4fo.png)



### *Pseudocódigo*
1.Primero tengo que crear una variable que contega el prompt 'Inserta tu numero de tarjeta', allí el usuario pone su número que sería el input.
2.Luego lo que hago es condicionar que el input sea únicamente number, no un string o vacío.
3.Sigue el código para que el input "correctamente ingresado" se convierta en un array por medio de un for y nuevo hago otro que contenga los mismos digitos pero al revés.
4.Después de hacer esto, tengo que ubicarme en los digitos que se encuentren en las ubicaciones pares.
5.Al extraerlo tengo que multiplicarlo por 2. Si y solo si, el número obtenido es mayor a 10, tengo que sumar sus cifras y quedarme con el producto, este será el nuevo dígito.
6.Hago un arreglo con los nuevos dígitos.
7.Creo una nueva funcion ya para validar.
8.Comienzo a recorrer en el algoritmo.
9.Sumo todos los elemetos de mi array, es decir de los nuevos dígitos.
10.Si la suma es menor a 10, hago un alert 'Tarjeta valida', si es mayor o igual a 10 hago un alert de 'Tarjeta ínvalida'.
