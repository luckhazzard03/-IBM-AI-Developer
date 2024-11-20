#IngSoftware#Metodologías

## Método Waterfall
#waterfall


Al principio, cuando se coincidió el SDLC, implementó lo que se conoce somo método de cascada, Waterfall es un método secuencial de desarrollo de software en el que la salida de una fase es la entrada para la siguiente fase de ciclo. El desarrollo y el trabajo en la siguiente fase comienza solo después de la finalización de la fase anterior.

Toda la planificación, como la definición de los requisitos y el diseño arquitectónico, se realiza por adelantado. El cliente no suele ver el producto hasta que se encuentra en la fase de prueba.

En caso de una versión principal del producto, se repite el mismo proceso, lo que produce intervalos prolongados, como años, entre versiones.

![[Pasted image 20241023074526.png]]


## Método V      "V- shape model"
#ModeloV

El modelo en forma de V recibe este nombre porque las fases forman un V.

Las fases que descienden  por el lado izquierdo de la V se denominan "Verificación".
Luego subiendo por el lado de la V, esas fases se denominan "Validación".

El modelo en forma de V es como una cascada, ya que también es secuencial.
Cada fase de verificación corresponde a una fase de Validación, hay cuatro etapas que se producen a cada lado de la V. Por  la V se encuentra planificación, el diseño el sistema, el  diseño de la arquitectura y, luego, el diseño de los módulos., la parte inferior de la V es la fase de codificación y volviendo a subir por la V están las cuatro fases que corresponden a las fases que bajan por la V :

- Pruebas Unitarias
- Pruebas de integración 
- Pruebas del sistema
- Pruebas de aceptación 


![[Pasted image 20241023075201.png]]


Las pruebas se escriben durante las fases de verificación a la izquierda y se ejecutan durante las etapas de validación a la derecha ahora, el Modelo ágil es diferente.


## Método Agile
#MetodoAgil

Se centra en un proceso colaborativo de desarrollo de software a lo largo de varios ciclos cortos en lugar de un proceso lineal estrictamente vertical. Agile es lo que se denomina un enfoque iterativo del desarrollo, todavía se alinea con SDLC, pero cada fase es corta.

Los equipos trabajan en ciclos o sprints, que suelen durara de una a cuatro semanas, las pruebas unitarias se realizan en cada sprint para minimizar el riesgo de fracaso, en lugar de la etapa de mantenimiento del SDLC, la etapa final del sprint es una etapa de retroalimentación, al final de cada sprint, se publica un fragmento de código funcional en una reunión denominada demostración del sprint, en la que las partes interesadas pueden ver la nueva funcionalidad y proporcionar sus comentarios.

Después de la demostración del sprint, todo el proceso se repite para cada ciclo de sprint, Tras varios ciclos de sprints, se desarrolla un producto mínimo viables, o MVP, para que las partes interesadas puedan dar su opinión sobre el conjunto de funciones básicas



![[Pasted image 20241023080908.png]]

Los cuatro valores fundamentales del desarrolo ágil descritos en lo que se conoce como el "manifiesto ágil" 

![[Pasted image 20241025074916.png]]


### Sequential vs iterative

La principal diferencia entre los métodos SDLC tradicionales, como el modelo en  cascada y el modelo en forma de V, en comparación con el método Agile de desarrollo de software es que los primeros son secuenciales, los métodos SDLC tradicionales, como la cascada y la forma en  V, se centran en todo el producto que se esta desarrollando antes de solicitar la opinión de los clientes, mientras que AGILE SE CENTRA EN RÁFAGAS DE DESARROLO RÁPIDAS Y BREVES.  Cada método tiene sus ventajas y desventajas, aunque Agile es probablemente el método más utilizado en el desarrollo de software moderno.

En cuanto a las ventajas del método de cascada, es fácil de entender y seguir, cada etapa es discreta y está bien definida, lo que facilita que todos los miembros del equipo comprendan sus funciones, además, dado que la planificación se realiza por adelantado, es más fácil estimar  un presupuesto y asignar recursos que los métodos iterativos.

Dicho esto, la cascada carece de flexibilidad, dado que toda planificación se realiza por adelantado, si se cambia o se pasa por alto un requisito, ese cambio puede ser difícil de incorporar en una fecha posterior. 

Inevitablemente, se producen complicaciones imprevistas o la funcionalidad acordad cambia con respecto a lo que se había previsto inicialmente.


Al igual que cascada, el modelo en forma de V es simple y fácil de usar. Es incluso más rígido que Waterfall, pero el  diseño de planes de prueba durante la fase de verificación ahorra un tiempo considerable durante las fases de codificación y validación, los inconvenientes también son similares a los Waterfall porque no se adapta fácilmente a los requisitos cambiantes.

Una vez que una aplicación se encuentra en la fase de prueba, es estremadamente difícil volver atrás y cambiar la funcionalidad.

E l desarrollo AGILE es diferente, ya que se basa en la investigación, la planificación y las pruebas continuas durante el desarrollo del producto.

Al agregar nuevas funciones a un proyecto, el desarrollo sigue pasando por las mismas fases que en SDLC tradicional, pero con AGILE, los requisitos nuevos y cambiantes se gestionan rápida y fácilmente porque la planificación se inicia al principio de cada ciclo de sprint, la mayoría de los recursos se gastan en la fase de construcción. Al final de cada ciclo, el equipo de control de calidad, las partes interesadas y el cliente disponen de un código funcional para comprobar si cumplen con los requisitos y se les anima a que envíen sus comentarios. A medida que los lenguajes y tecnologías de codificación se han desarrollado en los últimos años, ahora permiten el diseño modular, donde los desarrolladores pueden centrarse en fragmentos de código mas pequeños que se  integran fácilmente en el producto más grande. 
Estos pequeños fragmentos se pueden liberar para proporcionar el MVP.  


### VERSIONES DE SOFTWARE
#VersionSoftware

Las versiones de software nos dicen mucho sobre los programas y las aplicaciones.
Los usuarios pueden determinar qué versión de software utilizan y los desarrolladores pueden proporcionar información útil con los números de versión. Los números de versión del software varían en la longitud y significado; sin embargo, la mayoría de los números de versión siguen  un formato similar y representan información similar.

Los números de versión indican cuándo se lanzó el software, cuando se actualizo y si se realizaron cambios o parches menores en el software. 

El control de versiones de software es la forma en que los desarrolladores de software realizan un seguimiento del nuevo software, las actualizaciones y los parches de los programas y las aplicaciones. 

Los números de versión se pueden mostrar de varias maneras, los números de versión pueden ser cortos o largos, según el software y las preferencias del desarrollador, con 2, 3 conjuntos de números. Cada conjunto de números se divide por un punto.  La primera versión de una aplicación o programa puede tener el número de versión  1.0 para indicar que no hay actualizaciones, parches o correcciones del software.


Nota:  Una versión que aún esté en fase beta o en fase de prueba puede tener un número de versión inferior a 1, como 0.9.

Un programa o aplicación con muchas versiones y actualizaciones tendrá un número más largo, a veces 4 conjuntos de números diferentes dentro del número de versión.


El tercer conjunto de números, el punto 2, designa un cambio o actualización adicional. Qué significan estos números?  Algunos números de versión siguen el sistema de numeración semántica y tienen 4 partes separadas por un punto,  pero no todos los sistemas de numeración siguen este ejemplo de 4 partes.

En la numeración semántica, el primer número indica cambios importantes en el software, como una nueva versión.  El segundo número indica que se realizaron cambios menores en el software.
El tercer número del número de versión indica parches o correcciones de errores menores.

Por último, el cuarto número indica un número de construcción o una fecha de construcción  y puede indicar cambios menos significativos realizados. 
Los números de versión del software se identifican en la sección Acerca o Ayuda del software.

![[Pasted image 20241025094803.png]]





### PRUEBA DE SOFTWARE
#Testing

Las pruebas de software son la práctica de integrar los controles de calidad a lo largo del ciclo de desarrollo del software.

El propósito de las pruebas es  comprobar si el software cumple con los requisitos esperados y garantizar que el software esté libre de errores. 

Para probar el software, el equipo escribe" casos de prueba".
Estos casos de prueba se escriben para verificar la funcionalidad de una aplicación de software y garantizar que se cumplan los requisitos. 
Los casos de prueba se pueden escribir en diferentes etapas del SDLC y pueden variar según el tipo de prueba o el método utilizado para desarrollar el software, como Agile o Waterfall.
Un caso de prueba contiene:

- Pasos
- Entradas 
- Datos 
- Las salidas correspondientes esperadas. Independientemente del tipo de prueba o del método de desarrollo, los casos de prueba siempre deben escribirse una vez finalizados los requisitos. 

Las pruebas de software ayudan a evaluar el software para identificar si el producto se software cumple con los requisitos y está libre de errores.

Los tipos de pruebas se pueden clasificar ampliamente en tres categorías: 
- Pruebas funcionales 
- Pruebas no funcionales 
- Pruebas de Regresión 

Pruebas funcionales generalmente implican pruebas de caja negra, que son un método de prueba sin tener en cuenta el código fuente o la estructura interna.
Las pruebas funcionales solo se refieren a las entradas y salidas correspondientes del sistema bajo la prueba, también denominado SUT. Se basa completamente en los requisitos funcionales.

Definir los términos pruebas funcionales, pruebas no funcionales y pruebas de regresión y comparar , contrastar los niveles de pruebas típicos. 

Las pruebas de software son la práctica de integrar los controles de calidad a lo largo del ciclo.

Comprobar si el software cumple con los requisitos esperados y garantizar que el software esté libre de errores. Para probar el software, el equipo escribe "casos de prueba".
Estos casos de prueba se escriben para verificar la funcionalidad de una aplicación de software y garantizar que se cumplan los requisitos. 

Los casos de prueba se pueden escribir en diferentes etapas del SDLC y pueden variar según el 
tipo de prueba o el método utilizado para desarrollar el software, como Agile o Waterfall.

Las pruebas funcionales prueban el SUT para asegurarse de que cumple con los requisitos funcionalidades.  

![[Pasted image 20241025104307.png]]

Las pruebas funcionales garantizan que, cuando se producen errores de usuario o casos extremos de entrada,  el software gestiona esas excepciones sin problemas al mostrar los mensajes de error adecuados.




Las pruebas no funcionales incluyen probar la aplicación para determinar atributos como el rendimiento, seguridad, escalabilidad y la disponibilidad.

![[Pasted image 20241025104709.png]]

Las pruebas no funcionales comprueban si el comportamiento no funcional del SUT funciona correctamente. Las pruebas no funcionales deben responder a preguntas como las siguientes:

- Cómo se comporta la aplicación bajo estrés?
- Qué ocurre cuando muchos usuarios inician al mismo tiempo?
- Las instrucciones de los documentos y manuales de usuario son los coherentes con el comportamiento de la aplicación ?
- La aplicación se comporta de manera similar en diferentes sistemas operativos?
- Cómo gestiona la aplicación la recuperación ante desastres?
- Que tan segura es la aplicación?

## Pruebas de regresión

También denominadas pruebas de mantenimiento, confirman que un cambio reciente en la aplicación, como la corrección de un error, no afecta negativamente a las funciones ya existente.

Las pruebas de regresión deben realizarse cuando se ha producido un cambio en los requisitos o cuando se han corregido los defectos.

Para realizar pruebas de regresión, se deben seleccionar todos o algunos de los casos de prueba para compararlos con la aplicación. La selección y priorización de los casos de las pruebas de regresión pueden ser difíciles y pueden depender de varios factores.


Las razones más comunes para la selección de  casos de pruebas de regresión incluyen los casos que tiene casos frecuentes,  contienen funciones de uso frecuente, contienen funciones con cambios recientes o son casos de prueba complejos, casos límite y casos de prueba exitosos o fallidos al azar.

### Niveles de las pruebas "Testing levels"

Hay 4 niveles de prueba:

- Unitarias
- Integración 
- Sistema
- Aceptación 

cada nivel se produce en un momento diferente en el SDLC. Hay 4 NIVELES diferentes  para reducir la cantidad de tiempo decicado a las pruebas el evitar la superposición. 



#### Pruebas unitarias

Las pruebas unitarias se refieren a las que verifican la funcionalidad de una sección especifica del código, generalmente a nivel de función, lo lleva a cabo el desarrollador o ingeniero de software durante la fase de desarrollo del ciclo de vida del desarrollo del software. 

estas tienen como objetivo eliminar los errores de construcción antes de que el código se integre con otros módulos, las pruebas unitarias tienen como objetivo aumentar la calidad del software resultante, así como la eficiencia del proceso de desarrollo general.


#### Pruebas de integración 

Buscan identificar errores cuando se combinan dos o más módulos de código independientes más pequeños, estos son otro tipo de pruebas de caja negra.

Antes de las pruebas de integración, los módulos de código más pequeños e independientes que han superado las pruebas unitarias se incorporan a la aplicación de software más grande.

Una vez que los módulos se hayan integrado, se pueden realizar las pruebas de integración. La pruebas de integración revelan los errores que se producen cuando esas unidades de código más pequeñas interactúan entre sí.

Las pruebas de integración revelan deficiencias en la comunicación con un modulo nuevo junto con otros módulos hardware externo existentes. Las pruebas de integración descubren situaciones en las que se desarrollan errores debido a la diferente lógica de programación entre los módulos, por ejemplo. Además durante el desarrollo de los requisitos cambian y el módulo no se somete a pruebas unitarias completas. Un manejo deficiente de las excepciones puede causar problemas cuando los módulos se integran entre sí. 

Las pruebas del sistema se realizan después de las pruebas de integración y se llevan a cabo en un sistema completo e integrado para evaluar el Cumplimiento del sistema con los requisitos especificados.  Valida el sistema como un producto de software completo.   

Las pruebas del sistema son funcionales y no funcionales, las pruebas del sistema se realizan en un entorno de ensayo, que se debe ser similar al  entorno de producción.


![[Pasted image 20241025113328.png]]



#### Pruebas de aceptación  "Acceptance testing"

Son pruebas formales con respecto a las necesidades, los requisitos y los Usuarios, clientes y otras partes interesadas. las pruebas de aceptación generalmente las realizan el cliente.

Durante la etapa de mantenimiento del SDLC. 



# DOCUMENTACIÓN DEL SOFTWARE
#Documentación 

![[Pasted image 20241025122333.png]]

La documentación de software es información sobre el software que describe el producto  y como utilizarlo. Puede ser escrita vídeo o activos gráficos asociados con el desarrollo y uso de un producto de software. L documentación puede estar en cualquier de estos tres formatos. 
La documentación es un aspecto esencial de la ingeniería de software aplicable en todas las fases del SDLC. 
La documentación  de software puede escribirse para diferentes tipos de audiencias - como usuarios finales, desarrolladores de software, ingenieros de control de calidad, administradores de sistemas y otras partes interesadas. 


La documentación  puede dividirse en dos categorías, de producto y de proceso, la documentación de producto se refiere a al funcionalidad del producto, mientras que la documentación de proceso describe como complementar un tarea.

La documentación de proceso debe proporcionar los requisitos para la implementación de calidad de un proceso de negocio.


### TIPOS DE DOCUMENTACIO DE PRODUCTOS;
- Requerimientos 
- Diseño
- Técnica
- Garantía de calidad
- Documentación de usuario
La *documentación de requisitos* se redacta durante la fase de planificación del SDLC y esta destinada al equipo de desarrollo, incluidos los desarrolladores, arquitectos y personal de garantía de calidad.

La documentación de requisitos describe las características y funcionalidades esperadas del sistema de software.

Incluyen las especificaciones de requisitos del software, las especificaciones de requisitos del sistema y las especificaciones de aceptación del Usuario.

La *documentación de diseño* la escriben los arquitectos del software y el equipo de desarrollo para explicar  cómo se construirá el software para cumplir los requisitos. Consta de documentos de diseño tanto conceptuales como técnicos.

La *documentación técnica* incluye comentarios escritos en el código para ayudar a otros desarrolladores a leer el código y comprender su comportamiento. También puede incluir documentos de trabajo que explican a leer el código y comprender su comportamiento. También puede incluir documentos de trabajo que explican  como funciona el código y documentos que registran las ideas y pensamientos de los ingenieros durante la implementación del proyecto.

La *documentación de aseguramiento* de la calidad incluye todos los documentos que pertenecen a la estrategia, el progreso y las métricas de un equipo de pruebas. Los tipos de Documentación de pruebas incluyen planes de pruebas, datos de pruebas, escenarios de pruebas, casos de pruebas, estrategias de pruebas y matrices de trazabilidad. Las matrices de trazabilidad relacionan los casos de prueba con sus requisitos.

La documentación de usuario está destinada a los usuarios finales y explica cómo utilizar el software o les ayuda a instalar o solucionar problemas del sistema.  la documentación del usuario final incluye preguntas frecuentes, guías de instalación y ayuda, tutoriales y manuales de usuario.

Los procedimientos normalizados de trabajo, denominados PNT, suelen acompañar a la documentación de procesos, la documentación de procesos ofrece una visión general de un proceso, pero los PNT son muy detallados. Los PNT SON DOCUMENTACIÓN escrita que explica paso a paso cómo llevar a cabo una tarea común, aunque compleja, especifica de una organización.

Un repositorio de código es algo común para un ingeniero de software. 
Sin embargo, una organización puede tener pasos específicos a seguir para conseguir que el código se fusione en la rama principal.

La documentación del PNT explica esos pasos con detalle. los PNT pueden adoptar la forma de un diagrama de flujo u esquema jerárquico, o instrucciones paso a paso. 

La documentación, en cualquiera de sus formas, debe mantenerse actualizada. Tomemos por ejemplo 
los manuales de usuario en línea.

Si la interfaz de usuario de una aplicación basada en la nube cambia, la documentación en línea que la acompaña, debe actualizarse en consecuencia. Las empresas deben asegurarse de que asignan recursos para este paso.  
En lo que respecta al desarrollo de software y el SDLC, la actualización de la documentación tiene lugar durante las fase de mantenimiento . Idealmente, la documentación también debe revisarse periódicamente para garantizar su exactitud.  


#### Funciones en los proyectos de ingeniería de software
#FuncionesProyectos

Existen varios roles comunes en un proyecto de desarrollo de software. Y estos roles pueden tener nombres diferentes dependiendo del enfoque que se utilice, como Agile o cascada. A veces diferentes empresas tienen nombres distintos para puestos similares. Pero no todos los proyectos tendrán  todos estos roles. 
 - Director de proyecto o scrum master, parte interesada
 - Arquitecto de sistemas o de software , diseñador de UX



![[Pasted image 20241025154156.png]]


![[Pasted image 20241025154455.png]]


![[Pasted image 20241025154527.png]]

![[Pasted image 20241025154616.png]]


![[Pasted image 20241025154731.png]]

![[Pasted image 20241025154753.png]]


![[Pasted image 20241025154853.png]]


![[Pasted image 20241025154923.png]]

![[Pasted image 20241025154958.png]]


![[Pasted image 20241025155246.png]]


![[Pasted image 20241025160615.png]]


![[Pasted image 20241025160633.png]]

![[Pasted image 20241025160645.png]]

- La ingeniería de software es la aplicación de principios científicos al diseño y la creación de software.
    
- Las responsabilidades de un ingeniero de software incluyen el diseño, la creación y el mantenimiento de sistemas de software.
    
- El uso del SDLC puede mejorar la eficiencia y reducir los riesgos al:
    
- permitiendo que los miembros del equipo sepan en qué deben trabajar y cuándo
    
- facilitando la comunicación entre el cliente, otras partes interesadas y el equipo de desarrollo
    
- dejando que las partes interesadas sepan dónde encajan en ese proceso y
    
- haciendo saber a los equipos multidisciplinares cuándo han completado sus tareas para que el desarrollo pueda pasar a la siguiente fase.
    
- Los procesos habituales de ingeniería de software son la recopilación de requisitos, el diseño, la codificación, las pruebas, la liberación y la documentación.
    
- El proceso de recopilación de requisitos implica la identificación de las partes interesadas, el establecimiento de metas y objetivos, la obtención de requisitos de las partes interesadas, la documentación de los requisitos, el análisis, la priorización y la confirmación de los requisitos.
    
- Una SRS es un documento que captura las funcionalidades que debe realizar el software y también establece puntos de referencia o niveles de servicio para su rendimiento.
    
- Una URS es un subconjunto de la SRS que detalla los requisitos de especificación del usuario.
    
- El SysRS contiene la misma información que un SRS, pero además puede incluir capacidades del sistema, interfaces y características del usuario, requisitos políticos, requisitos normativos, requisitos de personal, requisitos de rendimiento, requisitos de seguridad y criterios de aceptación del sistema.
    
- La cascada, el modelo en forma de V y el ágil son metodologías diferentes para implementar el ciclo de vida del desarrollo de software.
    
- Las pruebas funcionales se ocupan de las entradas y las salidas correspondientes del sistema sometido a prueba, las pruebas no funcionales comprueban atributos como el rendimiento, la seguridad, la escalabilidad y la disponibilidad. Mientras que las pruebas de regresión confirman que un cambio reciente en la aplicación, como una corrección de errores, no afecta negativamente a la funcionalidad ya existente.
    
- Los tipos de documentación incluyen los requisitos, el diseño, la técnica, la garantía de calidad y la del usuario.
    
- Hay muchas funciones diferentes implicadas en un proyecto de ingeniería de software. Algunos de ellos son el director del proyecto o scrum master, las partes interesadas, el arquitecto de sistemas o de software, el diseñador de UX, el desarrollador de software, el probador o ingeniero de QA, el ingeniero de fiabilidad del sitio u Ops, el director o propietario del producto y el redactor técnico o desarrollador de información.
![[Pasted image 20241025161616.png]]


![[Pasted image 20241025161626.png]]

![[Pasted image 20241025161636.png]]
