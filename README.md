# WeCodeProperties

## Bienvenidos al  taller de Property Based Testing

*Porperty based test* o *test generativos* es una técnica de pruebas adoptada inicialmente por el paradigma de programación funcional.
Tiene dos peculiaridades fundamentales:

1. No tenemos control absoluto de los datos con los que ejercitamos el sistema.
2. No nos fijamos tanto en el estado de nuestro sistema como en las propiedades que debe cumplir el mismo.

## ¿Qué necesito para acudir al taller?
Lo primero de todo es que tengas ganas de aprender y ayudar a tus compis. Tened en cuenta que podemos llegar a ser un grupo numeroso y eso puede dificultar el desarrollo normal de una kata.
Además pensad en el impacto de la red si todos decidimos descargar todas las librerías y dependencias a la vez. Con la intención de agilizar lo máximo posible y de aprovechar el tiempo he creado proyectos en varios lenguajes para que os sirvan de punto de partida. De este modo no dedicaremos demasiado tiempo a montar un proyecto de cero. Por favor, antes de venir al taller, intentad descargaros el repositorio del lenguaje con el que os sintáis más cómodos y aseguraros de que podéis ejecutar los tests. En el repo de cada proyecto hay información específica.
A continuación os dejo una lista con las implementaciones que he podido ir haciendo. Si os apetece ampliar la lista con algún otro lenguaje sería taaaan feliz :)

* Scala: [https://github.com/delr3ves/WeCodePropertiesScala](https://github.com/delr3ves/WeCodePropertiesScala)
* Kotlin: [https://github.com/delr3ves/WeCodePropertiesKotlin](https://github.com/delr3ves/WeCodePropertiesKotlin)
* JavaScript: [https://github.com/delr3ves/WeCodePropertiesJs](https://github.com/delr3ves/WeCodePropertiesJs) (en progreso)


## Ejercicios

### 1. Familiarizarnos con las librerías

En esta parte del taller pretendemos familiarizarnos con las librerías, la idea es conocer sus conceptos principales y llevarlos a la práctica

#### Propiedades de la suma (15'):

* Escribir nuestro primer test con las propiedades de la suma.
* ¿Qué pasa si cambiamos la implementación de la suma por la de la implementación?

#### Jugando con la librería (20'):

* Poner trazas de log para ver cómo ejecuta nuestro test.
* Configurar el número de veces que queremos ejecutar un test.
* Ver cómo funciona el shrink haciendo fallar un test y mirando trazas.
* Hacer generadores custom y comprobar como hacer por filtrado y por modificación

#### Propiedades de algunas funciones/series matemáticas conocidas (5'):

* Cual es la propiedad fundamental de la serie de fibonacci?
* Con dicha propiedad tenemos la certeza de que la serie está bien?

#### Determinar las propiedades de las distintas operaciones de una lista (20'):

* Añadir un elemento a una lista
* Eliminar elementos de una lista
* Concatenar listas
* Eliminar duplicados


### 2. Resolver un problema "real"

Gracias a nuestros amigos de [Karumi](https://www.karumi.com/) por prestarnos su archiconocida kata de los Maxibon. Sois un amor, muchísimas gracias por vuestro curro y vuestro aporte a que el mundo del desarrollo software sea un lugar un poquito mejor :kissing_heart:

En esta segunda parte del training nos dedicaremos a probar las propiedades de un software ya construido aunque con posibles fallos de implemnetación. De esta forma veremos si los test de propiedades nos ayudarían a encontrar algún error no encontrado con otras técnicas de testing más tradicionales
