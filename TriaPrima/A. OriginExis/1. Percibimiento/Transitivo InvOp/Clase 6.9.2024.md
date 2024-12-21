#Facultad #SoftwareTesting 
 Profe: Marcos Rivera 
## Tema: Unit Testing

Utilizando condesandbox.io, vamos a hacer unit testing usando jest. Jest **utiliza funciones como describe, it (o test), beforeEach y afterEach para estructurar y organizar los tests**.
Basicamente, jest se usa para hacer tests de codigo. Jest usa determinadas funciones para evaluar el resultado y la logica de una porcion de codigo. 
Hay una piramide de prioridad para las pruebas que se hacen, a mas simple y componencial es la prueba, mas se acerca a ser una prueba unitaria. Varia en funcion de la user interface, de los servicios usados, entre otras cosas (En este caso):
![[Pasted image 20240906095347.png]]
Como se ve en la piramide, si el test involucra mayor integracion de componentes, mas lento es el testeo, y menos numerosos suelen ser, por temas practicos, y viceversa. 

Existen varios diagramas o piramides que priorizan y categorizan los test, depende del tipo de prueba, el proyecto y el sistema que se va a probar. La empresas tienen sus piramides personalizadas, aca un ejemplo que usa en Spotify: 
![[Pasted image 20240906095636.png]]
> "Las pruebas unitarias son mas rápidas siempre."
> "Es muy recomendable siempre hacer los testeos a la par que se escribe el código"

Como se ha dicho antes, la unidad es la menor expresión de funcionalidad que tenga sentido. La prueba unitaria entonces es la prueba de la menor expresion de funcionalidad de un programa. 

#### Algunas definiciones de examen
![[Pasted image 20240906100636.png]]

#### Que modelo mental vamos a usar para hacer las pruebas unitarias?
Acordemonos que el modelo mental es la aproximacion abstracta de la realidad de una persona.
Se basara en el "Test Driven Development":
![[Pasted image 20240906100835.png]]

### Tarea: Hacer los puntos 1, 2 y 4 del archivo preview (Que envio el profe) y de ellos hacer 5 pruebas unitarias en un test