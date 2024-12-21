Java Persistence App, es un estandar que tiene java para el acceso de base de datos cuando se trabja conobjetos, y esta ultima base de datos es relacional.
¿Porque se necesita este software como estandar? 
(Persistente, en este caso, quiere decir que se puede grabar en la base de datos y que como tal se puede acceder en cualquier momento; aun asi, el concepto de [[Persistencia|persistencia]] es mucho mas amplio, y da para mas).
El JPA no es un software como tal sino unas normas que surgieron como convencion de la Object Managment Group, que es un consorcio surgido en 1989.

Los JPA se manejan con orm (Mapeo relacional de objetos), el que nosotros vamos a usar es hibernate enver. Para simplificar, entendamos a hibernate como una api que es capaz de manejar y modificar la base de datos desde el codigo de java.

JPA es un api que se encarga de convertir en entidades todas aquellas clases que se quieran almacenar en la base de datos.
![[Pasted image 20240514082535.png]]

JPA tiene annotaciones que, vendrian a hacer la ejecucion de consulta e insercion que normalmente se hace con sql (Mapeo de atributos). Pero que se hacen desde el codigo de java:
![[Pasted image 20240514085935.png]]
![[Pasted image 20240514091203.png]]
### ¿Que es una entidad?
La entidad, como ya se menciono, es todo aquel conjunto de datos que se quieren grabar en la base de datos. Para que una entidad se considere como tal, necesita cumplir las siguientes condiciones:
![[Pasted image 20240514082911.png]]
### ¿Desde donde se definen los datos de conexión a la base de datos?
Desde la carpeta "recursos", por y para usar spring se definen en "application.properties":
![[Pasted image 20240514084611.png]]Y por usar hibernate, se definen en un xml dentro la subcarpeta "META-INF" lamado "persistence":
![[Pasted image 20240514084742.png]]
(El proyecto usado es un ejemplo otorgado por la profe que esta en el campus)
### Ejecucion
Cuando se ejecuta el codigo de ejemplo, el jpa, a traves del orm hibernate, modifica y añade a la base de datos lo que sea que se haya especificado como entidad mediante las anotaciones:
![[Pasted image 20240514090354.png]]