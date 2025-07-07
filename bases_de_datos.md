# Bases de datos enfocadas a uso con IA y formatos de texto

Las bases de datos tienen un rol fundamental en el uso de la IA ya que permiten almacenar y procesar grandes volúmenes de información que después será aprovechada para crear o habilitar otras soluciones que involucran aprendizaje automático (Machine Learning), analítica predictiva, sistemas vectoriales para modelos de incrustaciones o embeddings, etc.

El buen entendimiento del objetivo para construir una base datos permitirá el acceso rápido, la escalabilidad e integración con flujos de trabajo de IA, asegurando que los modelos puedan aprender de bases bien organizadas y de alta calidad.

A continuación encontrarás algunos conceptos básicos relacionados con la construcción y uso de bases de datos con IA.

## Formatos para manipulación de texto digital: TXT, Markdown.

El teclado es nuestro medio de comunicación principal con la computadora y las secuencias de texto nos permiten interactuar con los modelos de lenguaje de gran tamaño o grandes modelos de lenguaje  (LLM).

Un archivo de texto es fácil de crear y tiene extensión ".txt", hay una gran variedad de editores de texto que puedes usar para crear uno nuevo. En Windows encontrarás el Block de Notas y Word, en Mac tendrás Text Edit y Pages, la diferencia entre estos es que en Word o Pages puedes crear texto con diferentes estilos, mientras que en Block de Notas y Text Edit crearás simple y llano texto, sin estilos; no hay nada más básico que eso.

Los archivos TXT se pueden utilizar tanto para almacenar información como para continuar entrenando al LLM y que siga mejorando su precisión en las respuestas mientras enriquece su contenido. Para que esto sea posible, el archivo TXT debe contar con cierta estructura para hacer que la IA lo procese con mayor eficiencia. MARKDOWN es el lenguaje de marcado más popular para crear documentos estructurados usando texto plano.y funciona muy bien para IA porque los LLM los reconocen fácilmente y los procesan rápidamente.

Un lenguaje de marcado o markup, es un sistema de anotaciones como las que se utilizan en las revisiones editoriales, los editores revisaban los manuscritos y ponían notas en el margen con comentarios o correcciones previas a la publicación. Para el mundo digital es muy similar, estas anotaciones utilizan etiquetas, códigos y/o símbolos para indicar cierta estructura de formato o de visualización en pantalla.

En el caso de MARKDOWN se pueden tomar documentos de diferentes formatos como Word, PDF, Página WEB y convertirlos a texto Markdown usando símbolos para definir una estructura jerárquica. Por ejemplo:

-  ```# para nivel 1 (Título)```

-  ```## para nivel 2 (Sub-título)```

-  ```### para nivel 3```

-  ```**texto** para usar una fuente en negritas```

-  _texto_ para itálicas, etc.

De esta forma el LLM puede tomar el contenido usando esta estructura y entender cuáles son las secciones más relevantes por su orden en importancia.

Las principales ventajas de usar Markdown son:

Es portátil y totalmente independiente: se pueden crear y compartir archivos Markdown en cualquier dispositivo que pueda generar texto y en cualquier sistema operativo.

Es fácil de aprender, de escribir y de leer: no se necesitan antecedentes técnicos de ninguna clase para usarlo, usa el alfabeto y algunos símbolos como "#" y "*". 

Son compatibles con IA porque son fáciles de buscar, de indexar, de etiquetar y puedes usarlo tal cual minimizando el recuento de tokens de entrada.

Se pueden quedar en tu computadora, son de bajo peso y puedes usarlas localmente sin necesidad de la nube para conservar tu privacidad.

¿Cómo se ve una línea usando Markdown?

Lo que escribo: 

- ```Tres tristes **tigres** tragaban _trigo_ en un **_trigal_**.```

Lo que veré: 

- Tres tristes **tigres** tragaban trigo en un **_trigal_**.

Ideas, diarios, minutas, evaluaciones de desempeño, encuestas de satisfacción, tus notas en general, si empiezas a usar formato Markdown será más sencillo usarlas para cualquier LLM.



Consulta también:
- [Markdown tutorial](https://www.markdowntutorial.com)
- [Markdown live preview](https://markdownlivepreview.com/)

Libro: 
- The Markdown Guide de Matt Cone (2023) Leanpub.

## ¿Qué son datos estructurados?

Hablar de datos en el contexto digital es hablar del registro de valores, hechos u observaciones en forma de texto, números, imágenes, video o multimedia, que después de ser procesados pueden utilizarse para almacenarse, realizar análisis, generar conocimiento o tomar decisiones basadas en ellos.

Los datos por sí solos no tienen ningún significado, al ser una descripción de lo observado no proporcionan ningún contexto ni interpretación de lo que registran y por consiguiente no detonan ninguna acción cuando se miran aisladamente. Tener muchos o pocos datos no determina que se puedan realizar más o menos acciones con ellos, es mucho más importante procurar tener los datos necesarios para los objetivos que se planteen que almacenarlos sin sentido, solo ocupan recursos y pueden complicar la identificación de lo que es relevante o importante sobre ellos.

Los datos pueden ser:

- **No estructurados:** no poseen una organización o estructura interna, tienen un formato libre, no están en una tabla (archivos de texto, imagen, videos, reportes, correos electrónicos, etc.).

- **Estructurados:** están organizados o tienen un esquema lógico e identificable, usualmente se almacenan en tablas u hojas de cálculo, son el tipo de datos que encontramos en bases de datos relacionales.

Los datos estructurados facilitan tareas de búsqueda, recolección y filtrado porque están organizados en una forma estandarizada que habilita la lectura en diferentes sistemas.

Mira este comparativo entre datos estructurados y no estructurados:

| Estructurados                                              | No - Estructurados                                                              |
| :--------------------------------------------------------- | :------------------------------------------------------------------------------ |
| Pueden representarse como filas, columnas y bases de datos relacionales (RDB) | No suelen representarse como filas, columnas y bases de datos relacionales   |
| Contienen números, fechas y cadenas de caracteres          | Suelen contener imágenes, audio, video, documentos de texto, correos electrónicos, etc. |
| Tienen un esquema bien definido y establecen claramente la relación entre unos y otros datos | No tienen un esquema o relaciones bien definidas entre ellos               |
| Suelen usar menos espacio de almacenamiento                | Requieren mayor espacio de almacenamiento                                     |
| Se pueden explorar usando métodos basados en lenguaje de consulta estructurada (SQL) | Pueden necesitar herramientas especializadas para su exploración              |
| Relativamente fáciles de manejar y proteger con soluciones existentes o herramientas tradicionales | Más difíciles de manejar y proteger con soluciones existentes o herramientas tradicionales |

Algunas ventajas de los datos estructurados son:

- Funcionan bien para ser procesados usando Machine Learning, puede ser más fácil analizarlos por la forma en la que están organizados.

- Son accesibles y fáciles de usar, no se necesita mucho conocimiento sobre ciencia de datos para poder usarlos por su organización.

- Pueden ser utilizados con una amplia variedad de herramientas porque preceden a los datos no estructurados

Algunas desventajas:

- Pueden parecer inflexibles o limitados en su uso porque tienen que apegarse a un modelo predefinido y que persigue un objetivo, entonces no pueden usarse para otra cosa

- Para ser almacenados deben cumplir una serie de requisitos que si se actualizan en el tiempo pueden llevar a tener que actualizar la estructura de los datos también, esto puede ser costoso en tiempo y recursos.

## Formatos de salida para datos estructurados: CSV, JSON

Ya que hemos hablado de datos estructurados, vamos a identificar dos de los formatos más utilizados para intercambiar y almacenar datos: los archivos CSV o de valores separados por comas y los JSON o de objetos notación javascript.

### Archivos CSV

Son archivos de texto simple con extensión “.csv” donde la información está separada por comas ",". Se estructuran en un formato de tipo tabla usando filas y columnas, la información para cada fila se pone en un renglón diferente y los valores de cada columna están separados por una coma, se puede encontrar algunos que estén separados también por punto y coma ";" sin afectar su contenido.

Usualmente la primera fila se utiliza como encabezado para identificar los nombres da las columnas y los datos se almacenan a partir de la segunda fila. Se utilizan cuando los datos pueden ser almacenados en tablas simples que no necesitan estructuras complejas o anidadas. Por ejemplo:

ID_CONTACTO, NOMBRE, DEPARTAMENTO

325, “Ana”, “Instalaciones”

216, “Carlos”, “Audio”

Algunas de sus ventajas son:

fáciles de crear

fáciles de leer

compatibles con diversas herramientas tipo hojas de cálculo

requieren poco espacio de almacenamiento

pueden convertirse a formato JSON

recomendados para bases de datos pequeñas

Algunas desventajas que presentan son:

los datos se muestran tal cual son, cualquiera podría leerlos

no pueden contener objetos anidados como arreglos o listas

pueden tener problemas con algunos caracteres especiales que contengan comas, como el formato europeo del punto decimal, o con fechas

no almacenan información sobre el tipo de dato que contienen o el formato, lo más que llegan a contener es el nombre de la columna

pueden ser difíciles de escalar o integrar con otros

Este tipo de archivos se utilizan para importar o exportar datos de hojas de cálculo, almacenar datos en tablas simples, registros de actividades o interacciones, datos para visualizadores de inteligencia de negocios, por mencionar algunos.


### Archivos JSON

Son archivos de almacenamiento e intercambio de datos con extensión “.json” reconocidos por su formato de bajo tamaño y las facilidades para utilizar datos anidados o convertirlos a otros formatos.

Los archivos JSON se organizan en objetos delimitados por llaves “{ }” y arreglos delimitados por corchetes “[ ]” y pueden contener cadenas de caracteres, números, datos booleanos, otros arreglos y también otros objetos. Su estructura se denomina como clave-valor porque utiliza una clave para identificar el dato que será almacenado. Por ejemplo:

```
{

      “contacto”: “325”,

      “nombre”: “Ana”,

      “departamento”: [”Instalaciones”, “Tecnología”],

      “antiguedad”: 6

}
```


En el ejemplo anterior se muestra la estructura de “llave” : “valor” usando comillas “” para la llave y en caso que el valor sea una cadena de texto (string) también se usan dobles comillas, esta es la manera en la que json distingue si el valor es un número o es texto. Cada campo se separa por una coma y como puede verse en “departamento”, también es posible almacenar un arreglo de valores múltiples sin necesidad de crear otra clave.

Este tipo de estructura permite crear bases de datos jerárquicas donde los datos pueden ser anidados como un árbol donde exista una relación de niveles como la que se muestra a continuación:

```
{

      “contacto”: “325”,

      “nombre”: “Ana”,

      “departamento”: [“500”,”600”] [”Instalaciones”, “Tecnología”],

      “antiguedad”: 6

      “direccion”: {

                “casa”: { 

                          “calle”: “Miguel Hidalgo”,

                          “exterior”: “1810”,

                         “interior”: “9”

                         }

               “trabajo”: {

                       “calle”: “Benito Juarez”,

                      “exterior”: “1920”,

                      “interior”: “a”    

                } 

         }

}
```

| Características     | CSV                                                        | JSON                                                                                                        |
| :------------------ | :--------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------- |
| **Complejidad de datos** | Simples en formato tabla                                   | Complejos y en estructuras jerárquicas, anidando objetos y arreglos                                        |
| **Legibilidad** | Fácil para las personas en formato tabla, sin contexto para el tipo de variables que contienen | Auto-descriptiva y compatible con datos que necesitan representarse junto con las relaciones que existen entre ellos |
| **Tamaño** | Menor peso para almacenamiento y más fácil de procesar por su sencillez | Al incluir información estructural se traduce en archivos más grandes y su lectura puede usar más recursos dependiendo su complejidad |
| **Edición** | Fácil de editar en editores de texto tradicionales y hojas de cálculo | Requiere mayor atención debido a su sintaxis y estructura jerárquica                                        |
| **Compatibilidad** | Absoluta para hojas de cálculo, bases de datos y muchos lenguajes de programación | Ideal para intercambiar información entre "cliente-servidor" usando APIs y aplic                               |
| **Escalabilidad** | Ideal para tabulares grandes, limitada para estructuras complejas | Escalable para datos complejos, su eficiencia disminuye con bases de datos muy grandes                      |



Aquí podemos describir la estructura para la clave dirección con 2 ramificaciones, una para casa y otra para trabajo. Esta propiedad representa una de las principales fortalezas para los archivos json porque permite tener sub-datos dentro de los datos haciéndolos muy útiles para construir relaciones entre los datos que son mucho más fáciles de acceder y gestionar a diferentes niveles y usando menos recursos.

A continuación encontrarás un comparativo de las características más relevantes entre  los 2 formatos de salida de texto más comunes:
