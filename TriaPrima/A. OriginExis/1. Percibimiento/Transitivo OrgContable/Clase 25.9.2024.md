#Facultad #Ciberseguridad 
Profe: Sergio Neira
## Tema: Conceptos elementales de la criptografia

### Tipologia de los metodos de cifrados modernos mas usados
Los campos de cifrado o decifrado no van a pasar de los caracteres indexados dentro de los dispuestos por ASCII o ANSI. Como ya se ha dicho y mencionado antes, existen dos metodos de cifra moderna: 
- Cifrado en flujo
- Cifrado en bloque

Dentro del cifrado de flujo, nos encontramos con los metodos que usan las compañias de telefonia movil, como el linear feedback shift register ("LFSR") (https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://es.wikipedia.org/wiki/LFSR&ved=2ahUKEwjX2MLq_92IAxUQrJUCHSd9FJwQFnoECBgQAw&usg=AOvVaw35fdor1WruH0KuwK17UDfD)

Dentro del cifrado de bloque, existen los que tratan con claves publicas y claves secretas: 
- Claves secretas ("DES" "T-DES" "CAST" "IDEA" "RIJNDAEL")
- Claves publicas (SUMA/PRODUCTO: "CE" "MOCHILAS MH") (EXPONENCIACION: "RSA" "ELGAMAL")

> Algunos de estos metodos requieren de un conocimiento mayor o menor de matematica, sobre todo matematica discreta. 

>> El material de estudio que se uso para sintetizar esto esta descargado en un libro pdf, para ser especifico es el libro 10 de "Cifra moderna" de Julio Ramió Aguirre

## Cifrado de flujo
### Principios generales
A. El espacio de las claves es igual o mayor que el espacio de los mensajes. (O sea, las claves no son nunca menores a los mensajes que cifran).

#### Ejercicio

> Para practicar: construir un programa que haga un cifrado con un bloque de 128 bits usando una funcion xor
> Para hacer posta: hacer un programa que genere una clave, y persistirla en una base de datos. Luego, hacer un programa que decifre la clave  


Programa para optimizar el funcionamiento del computador segun el profe: Bleachbit 