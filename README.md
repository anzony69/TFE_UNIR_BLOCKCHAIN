# TFE_UNIR_BLOCKCHAIN

Proyecto Blockchain realizado por Anzony y Rodrigo

Descripción del Trabajo Final de Experto:

Objetivo

El objetivo del presente trabajo es que el alumno realice un diseño y un desarrollo basado en blockchain, en el que aplique y desarrolle los conocimientos adquiridos a lo largo del curso.

Descripción del caso

Una empresa ha desarrollado un sistema de fumigación con drones y nos ha solicitado que desarrollemos una solución basada en la blockchain de Alastria para su uso.

Las características propias de los drones son:

Un identificador único y ascendente, comenzando en 1 y que no puede repetirse.
La empresa que lo gestiona, que será la única que pueda mandar acciones al dron.
Altura máxima y mínima de vuelo.
Una lista de pesticidas que puede suministrar. Los pesticidas existentes son cinco y sus nombres son: Pesticida A, Pesticida B, Pesticida C, Pesticida D y Pesticida E.
Coste.
La operación de fumigación es inmediata y debe lanzar un evento de parcela fumigada con el ID de la parcela.

Las características de las parcelas son:

Un identificador único y ascendente, que comienza en 1 y que no puede repetirse.
Un propietario.
Altura máxima y mínima de vuelo permitida.
Pesticida aceptado, que va a ser uno de la lista de pesticidas descrita anteriormente.
Otras operaciones que debe suministrar la plataforma son:

Contratar un dron a la empresa para desinfectar una parcela con un pesticida determinado.
Pago de la operación realizada desde la cuenta del propietario a la de la empresa.
Para la gestión de pagos se debe crear un token propio basado en el estándar ERC 20. Además, los drones y las parcelas pueden gestionarse mediante tokens no fungibles basados en el estándar ERC 721.

La empresa solicita tener una interfaz web que le permita registrar los drones y asignarles trabajos. A su vez, también se debe proporcionar una interfaz web para que los propietarios de las parcelas las puedan registrar y tengan la posibilidad de contratar un dron con las características que requiere su parcela y que pueda desplazarse hasta la misma.
