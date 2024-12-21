#Facultad 

![[Pasted image 20240823105850.png]]

### Fuentes sobre los 3 incidentes 
https://www.fyccorp.com/articulo-10-grandes-errores-de-software

#### Mariner 1
Articulo dedicado: https://www.mtp.es/blog/testing-software/qabalgando-por-la-historia-iii-la-destruccion-del-mariner-i-1962/
###### Desarrollo:
¿Qué impacto tuvo?
El fracaso de poner en orbita el satélite le costó a la Nasa 18,5 millones de dólares.
¿Cómo se descubrió?
Aquellos encargados de la seguridad de la misión descubrieron la falla porque a los pocos minutos de despegar el cohete que pondria en marcha el satélite, notaron una inclinación inesperada hacia el noreste que dejaba la ventana de que este se estrellase en una zona de rutas navales en el Atlántico.
¿Cual fue su root cause?
El error fue causado por la omision de un guion en el programa que guiaba el cohete.
¿Como se solucionó?
Esto se habria solucionado haciendo un testing del programa guia, corroborando que las entradas de las señales se correspondan con las aplicadas a la trayectoria.
¿Que se puede aprender del fallo?
Del fallo se puede aprender que cuando se trata de temas de navegacion espacial, y sobre todo, de proyectos de campo tan unicos y particulares, en los que la primera prueba es la unica y la ultima, simulaciones digitales de campo no solo son necesarias, son imprescindibles.

#### Apagón del 2003 en el noreste de EEUU
Articulo dedicado: https://es.wikipedia.org/wiki/Apag%C3%B3n_del_noreste_de_Estados_Unidos_de_2003
###### Desarrollo:
¿Qué impacto tuvo?
Un apagon que dejo a oscuras a un cuarto de Canada y Estados Unidos durante casi 7 horas a todo el territorio afectado por el error, y dias o semanas debido a las complicaciones para restablecer bien la conexión del suministro. 
¿Cómo se descubrió?
Hubo una subida repentina de potencia de 3500 megavitos de la red electrica del estado de Nueva York.
¿Cual fue su root cause?
El error fue dado por una condición de carrera en el equipo de gestion de energia XA/21 basado en Unix de General Electric Energy que manejaba la NYISO, que generó una falsa desactivación del sistema de alarmas. Inadvirtiendo a los operadores de pistas visuales o audibles que hayan podido revelar un mal funcionamiento (Una sobrecarga) surgido de la caida de varias lineas de transmision en arboles.  
¿Como se solucionó?
Se solucionó con una compleja planificacion interestatal que gradualmente volvio a reestablecer las principales plantas generadoras. 
¿Que se puede aprender del fallo?
Que existen una determinada serie de protocolos que una compañia electrica debe cumplir para disponer del uso de sistemas de software para la gestion de energia de la red publica. 

#### Therac-25
Articulo dedicado: https://www.campusmvp.es/recursos/post/GAMBADAS-Therac-25-la-maquina-de-radiacion-asesina.aspx
###### Desarrollo:
¿Qué impacto tuvo?
La muerte de 6 personas debido a sobredosis por radiacion.
¿Cómo se descubrió?
Cuando se aplicaban dosis con haces de alta intensidad, la placa metalica que servia como proteccion intermedia no se activaba.
¿Cuál fue su root cause?
El error fue dado por una condicion de carrera en el software de control que no le permitio saber si la placa estaba o no puesta. Si el operador humano era mas rapido que el therac disponiendo la placa metallica, el programa no detectaba su presencia, pero por accion del operador lanzaba el haz igual.
¿Cómo se solucionó?
Mejorando las practicas de diseño de los softwares utilizados en los siguientes equipos de radioterapia y automatizando sus pruebas en la logica de sus programas. 
¿Qué se puede aprender del fallo?
Del fallo se pueden aprender varias cosas:
- Es importante no centralizar el funcionamiento de todo un equipo a un solo componente software.
- Es de carácter obligatorio confirmar el éxito de pruebas medicas con equipo de dicha indole mediante certificaciones oficiales.
- Es imperativo que si, en el ambito de la programacion se trabaja con planificacion de eventos que culminan en el desarrollo de una sucesion fisica, hayan una serie de precondiciones unicas que deban cumplirse antes de llevarse a cabo los respectivos algoritmos de planificacion, como en este caso es el tema de tiempo esperado antes de iniciar el haz de alta intensidad.
