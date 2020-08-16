---
layout: post
title: "Desarrollo de Software"
author: "Paolo Alvarez"
categories: journal
tags: [documentation,sample]
image: modu3.jpg
---

## Ciclo de vida y paradigmas de desarrollo de Software

El ciclo de vida del software, es el proceso que se sigue para construir, entregar y hacer evolucionar el software, desde la concepción de una idea hasta la entrega y retiro del sistema. Se definen las distintas fases intermedias que se requieren para validar el desarrollo de un software, es decir, para garantizar que el software cumpla los requisitos para la aplicación y verificación de los procedimientos de desarrollo, se asegura de que los métodos utilizados son apropiados.

![alt text](https://www.belatrixsf.com/blog/wp-content/uploads/2020/02/Software-Development-Life-Cycle.png "Lagrange Demo Image")

La ingeniería del software se vale de una serie de modelos que establecen y muestran las distintas etapas y estados por los que pasa un producto software, desde su concepción inicial, pasando por su desarrollo, puesta en marcha y posterior mantenimiento, hasta la retirada del producto. A estos modelos se les denomina “Modelos de ciclo de vida del software”. Un modelo de ciclo de vida de software es una vista de las actividades que ocurren durante el desarrollo de software, intenta determinar el orden de las etapas involucradas y los criterios de transición asociados entre estas etapas.

## Caracteristicas

Un modelo de vida del software:

* Describe las fases principales del desarrollo del software.
* Define las fases primarias esperadas de ser ejecutadas durante estas fases.
* Ayuda a administrar el progreso del desarrollo.
* Provee un espacio de trabajo para la definición de un detallado proceso de desarrollo de software.

Así, los modelos por una parte suministran una guía para los ingenieros de software con el fin de ordenar las diversas actividades técnicas en el proyecto, por otra parte suministran un marco para la administración del desarrollo y el mantenimiento, en el sentido en que permiten estimar recursos, definir puntos de control intermedios, monitorear el avance, etc.


## Modelo Cascada

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2e/El_modelo_de_desarrollo_en_cascada.svg/350px-El_modelo_de_desarrollo_en_cascada.svg.png "Lagrange Demo Image")


Este  es el más básico de todos los modelos, y sirve como bloque de construcción para los demás modelos de ciclo de vida. La visión del modelo cascada del desarrollo de software es muy simple; dice que el desarrollo de software puede ser a través de una secuencia simple de frases. Cada frase tienen un conjunto de metas bien definidas, y las actividades dentro de una fase contribuyen a la satisfacción de metas de la fase o quizás a una subsecuencia de metas de la fase. Las flechas muestran el flujo de información entre las fases. La flecha de avance muestra el flujo normal. Las flechas hacia atrás representan la retroalimentación.

**Caracteristicas del modelo cascada**

El modelo de ciclo de vida cascada, captura algunos principios básicos:

* Planear un proyecto antes de embarcarse en él.
* Definir el comportamiento extremo deseado del sistema antes de diseñar su arquitectura interna.
* Documentar los resultados de cada actividad.
* Diseñar un sistema antes de codificarlo.
* Testear un sistema después de construirlo.

Una de las contribuciones más importantes del modelo cascada es para los administradores, posibilitandoles avanzar en el desarrollo, aunque en una escala muy bruta.

Se recomienda utilizar para aquellos que disponen de todas las especificaciones del proyecto desde el principio, por ejemplo, los de reingeniería en sí (Proyectos complejos que se entienden bien desde el inicio).


## Modelo en Espiral

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/3/39/ModeloEspiral.svg/359px-ModeloEspiral.svg.png "Lagrange Demo Image")

La dimensión radial en la figura refleja costos acumulativos incurridos en el proyecto.

El modelo espiral de los procesos software es un modelo del ciclo de meta-vida. En este modelo, el esfuerzo de desarrollo es iterativo. Tan pronto como uno completa un esfuerzo de desarrollo, otro comienza. Además, en cada desarrollo ejecutado, puedes seguir estos cuatro pasos:

* Determinar qué quieres lograr.
* Determinar las rutas alternativas que puedes tomar para lograr estas metas.
* Por cada una, analizar los riesgos y resultados finales, y seleccionar la mejor.
* Segur la alternativa seleccionada en el segundo paso.
* Establecer que tienes terminado.

**El modelo espiral captura algunos principios básicos:**

* Decidir qué problema se quiere resolver antes de viajar a resolverlo.
* Examinar tus múltiples alternativas de acción y elegir una de las más convenientes.
* Evaluar que tienes hecho y que tienes que haber aprendido después de hacer algo.
* No ser tan ingenuo para pensar que el sistema que estas construyendo será “El” sistema que el cliente necesita.
* Conocer (comprender) los niveles de riesgo, que tendrás que tolerar.

El modelo espiral no es una alternativa del modelo cascada, ellos son completamente compatibles.

 El sistema es muy utilizado en proyectos grandes y complejos como puede ser, por ejemplo, la creación de un Sistema operativo.


## Modelo Incremental

![alt text](https://www.researchgate.net/profile/Alejandro_Aldas_Alarcon/publication/326571456/figure/fig6/AS:651789682614280@1532410178239/Figura-10-Modelo-de-proceso-incremental-Fuente.png "Lagrange Demo Image")

Desarrollo iterativo y creciente (o incremental) es un proceso de desarrollo de software, creado en respuesta a las debilidades del modelo tradicional  de cascada.

La idea principal detrás del mejoramiento iterativo, es desarrollar un sistema de programas de manera incremental, permitiéndole al desarrollador sacar ventaja de lo que se ha aprendido a lo largo del desarrollo anterior, incrementando, versiones entregables del sistema. El aprendizaje viene de dos vertientes: el desarrollo del sistema, y su uso (mientras sea posible).

Los pasos claves en el proceso son comenzar con una implementación simple de los requerimientos del sistema, e iterativamente mejorar la secuencia evolutiva de versiones hasta que el sistema completo este implementado. En cada iteración, se realizan cambios en el diseño y se agregan nuevas funcionalidades y capacidades del sistema.

**Caracteristicas**

Usando analisis y mediciones como guias para el proceso de mejora es una diferencia mayor entre las mejoras iterativas y el desarrollo rapido de aplicaciones, principalmente por dos razones:

* Provee de soporte para determinar la efectividad de los procesos y de la calidad del producto.
* Permite estudiar y despues mejorar y ajustar el proceso para el ambiente en particular.

Estas mediciones y actividades de analisis pueden ser añadidas a los metodos de desarrollo rapido existentes.

El modelo incremental se aplica cuando en un proyecto tenemos un tiempo límite y no disponemos del personal suficiente para que nuestro propósito sea implementado completamente.

## Modelo Prototipo

![alt text](https://sites.google.com/site/is11801/_/rsrc/1239160607222/contenido/modelos-de-proceso-evolutivo/prototipos.jpg "Lagrange Demo Image")

El modelo de prototipos, en ingeniería de software, pertenece a los modelos de desarrollo evolutivo. El prototipo debe ser construido en poco tiempo, usando los programas adecuados y no se debe utilizar muchos recursos. El diseño rápido se centra en  una representación de aquellos aspectos del software que serán visibles para el cliente o el usuario final.

 Este diseño conduce a la construcción de un prototipo el cual es evaluado por el cliente para una retroalimentación; gracias a esta se refinan los requisitos del software que se desarrollara. La interacción ocurre cuando el prototipo se ajusta para satisfacer las necesidades del cliente. Esto permite que al mismo tiempo el desarrollador entienda mejor lo que se debe hacer y el cliente vea resultados a corto plazo.

 **Etapas**

* Plan rápido
* Modelado, diseño rápido.
* Construcción del prototipo
* Desarrollo, entrega y retroalimentación
* Comunicación

Este modelo es adecuado cuando se desea desarrollar programas didácticos computarizados de una manera mas abierta de modo que el cliente en este caso los profesores realicen los refinamientos o las  aportaciones necesarias.

## Modelo basado en componentes

![alt text](https://matriarm.files.wordpress.com/2009/12/untitled2.jpg "Lagrange Demo Image")

El modelo de desarrollo basado en componentes conduce a la reutilización del software, y la reutilización proporciona beneficios a los ingenieros de software. Según estudios de reutilización, QSM Asocciate, Inc. Informa que el ensamblaje de componentes lleva a una reducción del 70% el ciclo de desarrollo un 84% del coste del proyecto y un índice de productividad del 26.2. No hay duda que el ensamblaje de componentes proporciona ventajas significativas para los ingenieros de software.

El proceso unificado de desarrollo de software representa un número de modelos de desarrollo basado en componentes que han sido propuestos en la industria. El lenguaje de modelo unificado define los componentes. Utilizando una combinación del desarrollo incremental e interactivo, el proceso unificado define la función del sistema aplicando un enfoque basado en escenarios. 

**Caracteristicas**

* Evolutivo por naturaleza
* Exige un enfoque iterativo
* Notación de componentes
* Diagrama de componentes
* Interfaces
* Componentes y nodos
* Restricciones


## Modelo de desarrollo agil

![alt text](https://comunidad.iebschool.com/metodologiasagiles/files/2015/05/metodologias-agiles.jpg "Lagrange Demo Image")

Las metodologías ágiles son métodos de desarrollo de software en los que las necesidades y soluciones evolucionan a través de una colaboración estrecha entre equipos multidisciplinarios. Se caracterizan por enfatizar la comunicación frente a la documentación, por el desarrollo evolutivo y por su flexibilidad.

Estas metodologías surgen a principios del 2001 en respuesta a los modelos de proceso clásicos ya existentes. La aparición de procesos ágiles se debe al hecho de haber encontrado estos supuestos clave en desarrollos precedentes:

* Es difícil predecir qué requisitos persistirán y cuales cambiarán, así como las prioridades del cliente.
* El diseño y el desarrollo de software están intercalados. Por ello se realizarán conjuntamente, probando el diseño a medida que se crea, pues es complicado predecir cuánto diseño es necesario antes de llegar a implementarlo.
* El análisis, el diseño y la implementación no son predecibles desde el punto de vista de la planificación.todologías Agiles

**El proceso ágil requiere una serie de características sobre el equipo de desarrollo:**

* Competencia técnica
* Enfoque común: entregar al cliente un incremento dentro del plazo
* Colaboración entre todos los participantes
* Autonomía para la toma de decisiones
* Capacidad de resolución de problemas confusos
* Confianza y respeto mutuo en el equipo
* Organización propia

**Existe una denominada Alianza Ágil que define los siguientes 12 principios para toda metodología ágil:**

**1.**Satisfacer al cliente con entregas tempranas y continuas de software valioso.
**2.**Los requisitos cambiantes son bienvenidos, incluso en fases tardías del desarrollo.
**3.**Entregar con frecuencia software funcionando, -de dos semanas a dos meses,- cuanto antes se haga mejor.
**4.**El cliente y los desarrolladores deben trabajar juntos a diario a lo largo del proyecto.
**5.**Individuos motivados. Darles el ambiente y el soporte que necesitan, y confiar en ellos para obtener el trabajo realizado.
**6.**El método más eficiente y efectivo de transmitir información hacia y dentro del equipo es la conversación cara a cara.
**7.**El software en funcionamiento es la medida principal de progreso.
**8.**El desarrollo debe ser sostenible. Los participantes deben ser capaces de mantener un paso constante de manera indefinida.
**9.**Atención continua a la excelencia técnica y a un buen diseño.
**10.**La simplicidad es esencial, maximizando el avance del trabajo no realizado.
**11.**Las mejores arquitecturas, los mejores requisitos y los mejores diseños emergen de equipos auto-organizados.
**12.**A intervalos regulares el equipo refleja la forma en que se puede volver más efectivo, entonces su comportamiento se ajusta y adecua en concordancia.

**Algunas de las técnicas basadas en la metodología de desarrollo ágil más populares:**

* Extreme Programming
* Scrum
* Dynamic Systems Development Method (DSDM)
* Proceso Unificado Ágil (Agile Unified Process)
* Desarrollo Adaptativo de Software (Adaptive software development)
* Modelado Ágil (Agile Modeling)

![alt text](https://www.bravent.net/wp-content/uploads/2016/06/metodologias-agiles.jpg "Lagrange Demo Image")

## Modelo de desarrollo orientado a objetos

![alt text](https://image.slidesharecdn.com/anlisis-final-100825163628-phpapp01/95/desarrollo-de-software-orienta-a-objetos-6-728.jpg?cb=1282754285 "Lagrange Demo Image")

En los requerimientos del flujo de trabajo como objetivo principal es mantener un acuerdo
entre los clientes, usuarios y desarrolladores sobre lo que debe hacer la herramienta
(software a implementar), definir los límites (delimitar) del sistema, proveer una base para
la planificación del contenido técnico de las iteraciones, proveer una base para la
estimación del costo y tiempo del desarrollo de la herramienta. 

Definir una interfaz de usuario para la herramienta, enfocándose en las actividades y
Objetos de los usuarios. Todo ello para mejorar el desarrollo de las actividades en cualquier
ámbito tecnológico, social y cristiano.

Como resultado de las actividades de este flujo de trabajo, se desarrolla el documento
visión, el modelo de los casos de uso, los casos de uso que en conjunto describen la
herramienta a desarrollar. También se construye un glosario y un prototipo de la interfaz de
usuario.

La información en una organización no siempre es fácil de obtener, más bien es un
proceso lento y costoso, que exige tiempo y dedicación por parte del analista de sistemas y
los usuarios.

Las fases de búsqueda de información en cualquier proyecto, suelen ser grandes
consumidoras de tiempo, y el éxito de los resultados depende en gran medida de la calidad
de la información.
Es muy común que la información requerida no se encuentre escrita, o inclusive que ésta
no se conozca. Esto hace necesaria la interacción del analista con las personas del negocio
para identificar y/o generar la información faltante.

**Aprenderemos a capturar requerimientos a partir de:**

**El modelo de negocio**

Procesos, actores, trabajadores y workflows del negocio.

**Técnicas de recopilación de información**

Entrevistas, trabajo grupal

**Análisis de la documentación obtenida**

Formularios, reportes

**Análisis del modelo del negocio**

La principal fuente de captación de los requerimientos funcionales son los procesos del
negocio en él encontraremos elementos de información importantes:

* Las funciones derivadas de las actividades a automatizar.
* Los roles que van a interactuar con el sistema.
* Los recursos que se usan en el negocio y de cuyo estudio podremos más adelante
* identificar las clases del sistema.

**Técnicas y fuentes para la recopilación de datos**

Existen diversas fuentes que nos proporcionan los datos suficientes para recopilar los datos
necesarios entre ellos tenemos:
Técnicas, cuestionarios, entrevistas, sondeos, encuestas, collage, dibujos y diagramas,
tablas de organización, descripción de puestos, manuales operativos y la representación
física de las organizaciones.


## Modelo de desarrollo (Reutilización)

![alt text](https://lh5.googleusercontent.com/proxy/bCvoz5LUAoeEyaFdH5dKlaFatSiDyDfVvGgM09oGz57SUhcKHQ8SY5V3KQVwJ4P3PZnMAAS5ae-q9sAKqEzfHwU-GrqxEyMI7SALGLa5a4cEw6DsEqVE8Sr6s0z8e0AhcqREShx1Jw0FqEiC8dsIFAoTZpj-9puzSw3qY0Brahv6omIaj3WFvtkU1Y0CeZ5QRcVzlOSoS-uz7AggqjkAqiyXLBVpdKuNVXy5VBeGCg=w1200-h630-p-k-no-nu "Lagrange Demo Image")

Es el proceso de creación de sistemas de software a partir de un software existente, en lugar de tener que rediseñar desde el principio.
En los años 60, se construyeron bibliotecas de subrutinas científicas reutilizables con un dominio de aplicación limitado, en la actualidad se crean componentes comunes a varios procesos con el fin de poder utilizarlos en la construcción de software.
Podemos definirla como el empleo de elementos de software u otros de nivel superior, creados en desarrollo anteriores, para de este modo reducir los tiempos y simplificar el desarrollo del software, mejorando la calidad y reduciendo su costo.

**Elementos que intervienen en la reutilización**

* Especificaciones de requerimientos previamente concebidas
* Diseños previamente definidos (Estructuras de datos, algoritmos, etc.)
* Código probado y depurado con anterioridad
* Planes y casos de prueba previamente utilizados
* Personal cualificado (aprovechamiento de la experiencia de los ingenieros de un proyecto a otro)
* Paquetes de software de propósito general

**Conceptos de reutilización de software**

La reutilización de software aparece como una alternativa para desarrollar aplicaciones y sistemas SW de un manera más eficiente, productiva y rápida. La idea es reutilizar elementos y componentes SW en lugar de tener que desarrollarlos desde un principio.

* Surge formalmente de 1968
* La idea principal era producir componentes de software como si de componentes eléctricos se tratara.
* El objetivo es reutilizar lo existente sin tener que volver a rediseñarlo desde el principio.


## Desarrollo de metodos formales de software

![alt text](https://1.bp.blogspot.com/-o9WhrBCvXtE/UYWiT-cJ7BI/AAAAAAAAACE/k_ZgtvdB_5M/s1600/metodos+formales.jpg "Lagrange Demo Image")

Los métodos formales surgieron como puntos de vista analíticos con los que es posible verificar el desarrollo de sistemas mediante la lógica y las matemáticas, lo que aporta grandes ventajas para mejorar la calidad de los programas y por tanto la Ingeniería de Software.

En este campo del conocimiento, la especificación formal es una de las más importantes fases del ciclo de vida, labor que requiere mucho cuidado ya que su función es garantizar que tanto el funcionamiento como el desempeño del programa sean correctos, bajo cualquier situación. 

En el futuro, los métodos formales deberían estar presentes como principios esenciales en el desarrollo de software, ya que se convierten en la base para aplicar las técnicas de prueba y, dado su principio matemático, en potencialmente automatizables. 

En Ingeniería de Software, un método formal es un proceso que se aplica para desarrollar programas, y que explota el poder de la notación y de las pruebas matemáticas. Además, los requisitos, la especificación y el sistema completo deben validarse con las necesidades del mundo real (Kuhn et al., 2002). 

**En la Ingeniería de Software los métodos formales se utilizan para:**

* Las políticas de los requisitos. En un sistema seguro se convierten en las principales propiedades de seguridad que éste debe conservar -el modelo de políticas de seguridad formal-, como confidencialidad o integridad de datos.

* La especificación. Es una descripción matemática basada en el comportamiento del sistema, que utiliza tablas de estado o lógica matemática. No describe normalmente al software de bajo nivel, pero sí su respuesta a eventos y entradas, de tal forma que es posible establecer sus propiedades críticas.

* Las pruebas de correspondencia entre la especificación y los requisitos. Es necesario demostrar que el sistema, tal como se describe en la especificación, establece y conserva las propiedades de las políticas de los requisitos. Si están en notación formal se pueden diseñar pruebas rigurosas manuales o automáticas.

* Las pruebas de correspondencia entre el código fuente y la especificación. Aunque muchas técnicas formales se crearon inicialmente para probar la correctitud del código, pocas veces se logra debido al tiempo y costo implicados, pero pueden aplicarse a los componentes críticos del sistema.

* Pruebas de correspondencia entre el código máquina y el código fuente. Este tipo de pruebas raramente se aplica debido al costo, y a la alta confiabilidad de los compiladores modernos.

Por tanto, los métodos formales en la Ingeniería de Software son técnicas matemáticamente rigurosas que se utilizan para describir las propiedades del sistema, y proporcionan marcos de referencia para especificarlo, desarrollarlo y verificarlo de forma sistemática, en lugar de hacerlo ad hoc (Jones et al., 2006).

## Conclusión 

Luego de ver algunos de los modelos de ciclo de vida más utilizados surge la pregunta con la respuesta más codiciada: ¿qué modelo de ciclo de vida elegir? Sabemos que ninguno predomina sobre los otros. Por ello, debemos elegir el modelo que mejor se adapte al proyecto que desarrollemos. Podemos analizar, para guiarnos en nuestra elección, la complejidad del problema, el tiempo que disponeos para hacer la entrega final, o si el usuario o cliente desea entregas parciales, la comunicación que existe entre el equipo de desarrollo y el usuario y, por último, que certeza ( o incertidumbre) tenemos de que los requerimientos dados por el usuario son correctos y completos.