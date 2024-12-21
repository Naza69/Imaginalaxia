#Facultad #EstudioMetodologias

Profe: Marcos Riveros

Vamos a ver pruebas de software
Vamos a usar postman, usar maquinas virtuales, nodejs, pruebas de integracion. 

## La investigación operativa
La investigación operativa es un estudio científico que surgió formalmente en la segunda guerra mundial. Estudia la administración de los recursos de un tema o campo. En este caso como es aplicado a la computación, los recursos son ciertos componentes físicos que sirven como estándar o base. A ver, el profe muy claro no fue, pero acá esta la definición de wikipedia:
> La **investigación de operaciones**, también llamada **investigación operativa** o **ciencia administrativa**, es una disciplina que se ocupa de la aplicación de métodos analíticos avanzados para ayudar a tomar mejores decisiones. Forma parte de la disciplina administrativa y la ingeniería industrial.

> "Si quieren ir a estudiar desarrollo de software en la Aconcagua, no se las recomiendo, sigan ustedes estudiando por si solos" - Profe Marcos Rivera

Conviene chequearse [[LeetCode]] y el canal de youtube [[NetCode]] para practicar haciendo programas.

Si a ver, el pantallazo que nos dio, es el del testeo de los metodos de insercion de datos para una base de datos, la cosa es comprenderlos para poder testearlos, y por eso empezo a puntualizar todos los posibles.
Aca un dibujo del profe que lo ilustra:
![[Pasted image 20240816100232.png]
![[WhatsApp Image 2024-08-16 at 10.02.54.jpeg]]

## El profe tuvo un percance en el laburo con un forcejeo a una base de datos
Dentro del codigo insertable, el profe tenia una carpeta llamada "Migration", en donde tenia un codigo que creaba una tabla. Resulta que no pudo crearla porque el codigo no se se ejecutaba en la DB de forma normal, entonces forzo la ejecucion, funciono, pero al dia siguiente le informaron que el staging de la DB se habia caido. Pero no era su culpa, fue un sustito, no paso nada.
![[Pasted image 20240816102501.png]]
Aca un dibujito mas detallado del problema:
![[Pasted image 20240816102836.png]]
Resulta que la grabacion no resulto porque habia un nombre mal puesto de una tabla, lo que generaba una falta de relacion entre entidades. 

## Muchas oportunidades dentro del manejo de datos con apis
Los distintos procesos en la secuencia de acciones que llevan al uso de la api, requieren de personas que sepan de ciberseguridad, de analisis de datos, etc. No solo se limita el desarrollo intrínseco de la api.

## Cosas que necesitamos tener instaladas
Node js
Vscode
Postman
Jest (Libreria para hacer testing)
![[Pasted image 20240816105003.png]]