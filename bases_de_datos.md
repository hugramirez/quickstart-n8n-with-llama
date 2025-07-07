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
 
