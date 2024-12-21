#Facultad #DesarolloWeb 
 Profe: Luciano Chiroli
## Tema: TypeScript

Si nosotros sabemos js, sabemos como el 80% de typescript, es simplemente un superconjunto de js. Es un lenguaje de programacion creado por microsoft. Se creo con el objetivo de mejorar las aplicaciones hechas en javascript. Se llama typescript porque tiene un muy fuerte tipeo comparado con js.

Typescript se ejecuta como un codigo js generado por una llamada "transpiracion". Necesariamente Tc no se va a ejecutar por si solo en un navegador, la "transpiracion" entonces, es obligatoria para ejecutar codigo escrito en Tc.

## Tipos de datos

Los tipos de datos que en js no se usaban, y se reemplazaban con el tipo de dato "any", en tc si se usan. Los tipos de datos siguen siendo los mismos que muchos lenguajes: 
- Integer (Defined)
- String (Defined)
- Float (Defined)
- Boolean (Defined)
- Null
- Undefined

#### La interfaz para la creacion de objetos
Para la creacion de objetos en typescript se usan las interfaces, asi es posible darle propiedades u atributos definidos. Curiosamente, en las interfaces de typescript se pueden definir metodos, pero no crudas con la palabra reservada de "function", sino con la "arrow function": () => {}.

#### Se pueden usar intersecciones y uniones para el trato de metodos con type
Aun asi, se suele usar mas las interfaces para esto.