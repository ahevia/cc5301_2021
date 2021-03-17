# CC5301  Introducción a la Criptografía Moderna, Otoño 2021
_(Work in progress!!! Actualizado el 2021-03-14)_

**Propósito:**

Discutir y aprender aspectos introductorios (y no tanto) de la Criptografía moderna.

**Profesor:** [Alejandro Hevia](http://www.dcc.uchile.cl/~ahevia/)
- Cátedras: Lunes y Miércoles 10:15am-11:30am (con break de 10min aprox.)
- **Horario Consultas profesor (via Discord): Lu 10am-11am, Vie 3pm-4pm.** (actualizado 2020-09-25-15:00)
- Clases auxiliares: Viernes 10:15am-11:45am 
	- Auxiliares: Ilana Mergudich,.
	- Ayudantes: TBA
- Sitio web oficial del curso: este y [ucursos](https://www.u-cursos.cl/ingenieria/2021/1/CC5301/1/)
- [Programa del curso](https://users.dcc.uchile.cl/~ahevia/cursos/2021/cc5301/programa.pdf)

## Objetivo del curso 

Al finalizar el curso el alumno será capaz de:
* Razonar matemáticamente acerca de la seguridad algoritmos criptográficos tanto del tipo simétrico (clave privada) como del tipo asimétrico (clave púbica).
* Modelar y analizar formalmente algoritmos criptográficos basados en cifradores de bloque, funciones de hash y primitivas basadas en teoría de números, entre otros.
* Diseñar y evaluar soluciones criptográficas para problemas prácticos (confidencialidad, autentificación) presentes en redes de computadores.



## Metodología del Curso

El curso consiste en clases de cátedra más clases auxiliares ambas síncronas (vía zoom). El material docente, el cual incluye presentaciones de clases (anotadas) y pautas de auxiliares, y libros de material de lectura del curso, será publicado en ucursos. Para consultas al equipo docente y discusión de la materia pueden usar el foro de ucursos o escribirle directamente a los auxiliares.

El libro de referencia del curso es el libro de Jon Katz y Yehuda Lindell, 
  _Introduction to Modern Cryptography, 
	Second Edition_. 
Se espera que el estudiante lea y estudie en forma independiente el o los capítulos correspondientes
  a la materia vista en clases.

El curso está fuertemente basado en trabajo personal. Se espera que los estudiantes: 
- asistan a las clases de cátedra y auxiliares, (y de ser posible pregunten vía audio o chat),
- lean los capítulos sugeridos de los libros clase a clase,
- interactúen (hagan preguntas) en el foro de estudiantes y chats (por ej. zoom en cátedras y auxiliares),
- resuelvan los problemas propuestos (dejados en clase), y
- resuelvan los problemas de las guías de problemas propuestos.

## Evaluaciones

El curso será completamente evaluado con 3 tareas obligatoria y una recuperativa, a resolver individualmente (ver polítiica de colaboración más abajo).
Para resolver cada tarea tendrán 2-3 semanas, y su solución tendrá dos partes:
- la solución escrita (un PDF en latex o escrita a mano siempre que tenga letra legible y ordenada), y
- un video de a lo más 8 min explicando lo fundamental de su solución (esto NO es re-describir su solución, sino explicar brevemente la idea principal de cada solución, o con qué se inspiraron, o en base a qué problema o lo hicieron, o si no la entendieron completamente, qué si entendieron). **Importante:** Si no entrega video la nota de la evaluación sera 1.0. 

Se espera que cada estudiante **entienda bien su solución**. El equipo docente se reserva el derecho a *citar a entrevista personal (vía zoom)* a algunos estudiantes para que expliquen su solución de la tarea. Cuáles estudiantes serán citados será decidido arbitrariamente por el profesor o incluso escogidos al azar. Note que, el que Ud. sea llamadx _no significa que esté acusado de copia o nada_, simplemente es una manera de confirmar que cada estudiante entiende su solución. Si es llamado a entrevista, la nota final de la solución dependerá tanto de la explicación escrita como de la entrevista.

Habrá un control al final del curso, síncrona, en la forma de una entrevista. XXXX

Tendremos una tarea extra opcional para recuperar la nota al final. El examen (eximidos con 5.0) será en forma síncrona, en la forma de una entrevista.

### Calendario Evaluaciones

* **Tarea 1 (T1)**: 

  - Fecha publicación: Lunes 28 de Sept.
  - Fecha de entrega: Miércoles 14 de Octubre.
  - Contenidos: AFD, AFND, ER, Lema Bombeo, GLC, AP.

* **Tarea 2 (T2)**: 

  - Fecha publicación: Lunes 26 de Oct.
  - Fecha de entrega: Miércoles 11 de Noviembre.
  - Contenidos: Teorema Bombeo LLC, MT, Cálculos con MTs, Variantes MT.

* **Tarea 3 (T3)**: 
  
  - Fecha publicación: Lunes 16 de Nov.
  - Fecha de entrega: Miércoles 9 de Diciembre.
  - Contenidos: Enumeradores, Tesis de Church-Turing, - Indecibilidad, Verificadores Polinomiales.

* **Tarea Rec (TR)**: (Puede reemplazar una tarea) 
  - Fecha publicación: Lunes 14 de Diciembre,
  - Fecha de entrega: Miércoles 23 de Diciembre.
  - Contenidos: NP Completitud, NP en la práctica.

* **Control 1 (C1)**:
  - Fecha publicación: Lunes 14 de Diciembre,
  - Fecha de entrega: Miércoles 23 de Diciembre.
  - Contenidos: casi todo
  
**Cálculo de nota NC:** La nota de control NC previa al examen, se calculará como el promedio de las notas T1,T2 y T3, luego que la peor nota de T1,T2, y T3 hayan sido reemplazada con la nota de TR (siempre que ello beneficie al/a la estudiante).

**Control:** XXX

**Examen y eximición:** Quienes obtengan NC sea menor a 5.0, deberán dar el exámen (EX). En dicho caso, la nota final del curso (NF) se calcula como el promedio ponderado 60% NC y 40% EX. De eximirse del examen, NF será igual a NC.

### Atrasos en Evaluaciones

Las evaluaciones tendrán una fecha y horario de entrega (típicamente 23:59hrs) pero se aceptarán atrasos hasta 5 días siguiendo las siguientes reglas:

- Cada estudiante tendrá hasta un máximo de 9 días de atraso que puede usar libremente en las 3 evaluaciones (E1,E2,y E3),
- No puede usar más de 5 días para cualquier evaluación individual (para no atrasar las notas),
- Días de fin de semana y semanas de receso no cuentan en los días de atraso, y
- Una vez que el estudiante haya utilizado la totalidad de sus días de atraso, cualquier entrega que haga posterior a la fecha de entrega será calificada con nota 1.0. 

Nota: Estos días de atraso NO se podrán aplicar a la tarea recuperativa (TR) pues los tiempos son más ajustados para la correción. 

## Politica de Colaboración

Para resolver las actividades evaluativas, pueden colaborar entre dos o más personas siempre que usen la política de _Whiteboard_ (o "pizarrón en blanco"), esto es
- Al juntarse, pueden compartir un pizarrón o editor donde ambxs escriban y discutan cómo resolver el problema, pero **nadie puede grabar ni tomar fotografías**.  
- Al terminar, se "borra" (se cierra), y luego de 30min, cada unx escribe/redacta su solución en forma individual.

Se prohibe buscar soluciones por Internet, o usar las soluciones de otra persona.
(En serio, no use soluciones encontradas en Internet, no sólo por un tema ético sino porque hay muchas equivocadas o que usan ideas o conceptos que vemos distinto en este curso).

Para más detalles o en caso de duda, preguntar a los auxiliares o al profe.

## Donde colaborar y preguntar

Existe un servidor de [Discord](https://discord.gg/V6G9c4Y) para el curso. Está disponible para contactar a los auxiliares, ayudantes y el profesor; además puede usarlo para colaborar si lo desea. Si no sabe usarlo, preguntar en el foro.

## Calendario

__(Actualizado 2021-03-17)__

Semana | Clase  | Tema                 | Contenidos        | Lecturas                       | Comentarios    
:----  | :----: | :--------------:     | :--------------   | :--------------                |  :---------
1      | 0      | Introducción         | Motivación        | Navarro Cap. 1, Sipser Cap. 0  |  
1      | 1      |                      | Conceptos Básicos | idem   |  
2      | 2      | Lenguajes Regulares (LR)  | Autómatas finitos (AF) determinísticos, operaciones y clausura  | Navarro Cap. 2.2, Sipser Cap. 1.1 |  
2      | 3      |                      | AF no deterministas, equivalencia | Navarro Cap. 2.3,2.5, Sipser Cap. 1.2, HMU: Cap. 4.4 (pag.155-165)  | 
3      | 4      |                      | Continuación clase pasada  |  | 
3      | 5      | Expresiones Regulares  | Pendiente clase pasada (Clausura usando no-determinismo), Expresiones Regulares  | Navarro Cap. 2.1; Sipser Cap. 1.2, 1.3 | 
4      | 6      |                      | ER Parte II (Equivalencia AF y ER), Props. Algorítmicas de LR.   | Navarro Cap. 2.3,2.4,2.6,2.9; Sipser Cap. 1.2, 1.3 | 
4      | 7      | Lema del Bombeo  | Enunciado y Ejemplo | Navarro Cap. 2.8; Sipser Cap. 1.4 | 
5      | 8      | Lenguajes Libres de Contexto (LLC)| Gramáticas Libres de Contexto (GLC)   | Navarro Cap. 3.1,3.2; Sipser Cap. 2.1  |
5      | 9      |                      | Autómatas de Pila (AP)  | Navarro Cap. 3.3; Sipser Cap. 2.1  | 
6      | 10     |                      | Equivalencia GLC y AP  | Navarro Cap. 3.4,3.5; Sipser Cap. 2.2  | 
6      | 11     |                      | Teorema de Bombeo, Props. Algorítmicas y Clausura LLC  | Navarro Cap. 3.6,3.7,3.8; Sipser Cap. 2.3  |
7      | 12     | Máquinas de Turing (MT)   | Intro, ejemplos, configuración, decidir vs. reconocer  | Navarro Cap. 4.1; Sipser Cap. 3.1  | 
7      | 12+    |                      | Continuación MT  | Navarro Cap. 4.1; Sipser Cap. 3.1
8      |        | (Paro) 
8      |        | (Paro)
9      | 13     |                      | Calculando con cadenas, aritméticos; Variantes de MT (MT con "stay")  | Navarro Cap. 4.2; Sipser Cap. 3.2  | 
9      | 13+    |                      | MT multicinta  | Navarro Cap. 4.4; Sipser Cap. 3.2  | 
10     | 14     |                      | MT no determinista (MTND), computar con MTND  | Navarro Cap. 4.5; Sipser Cap. 3.2  | 
10     | 15     |                      | Modelos alternativos, Tesis de Church-Turing, MT Universal  | Navarro Cap. 4.7; Sipser Cap. 3.2  | 
11     | 16     |                      | Enumeradores, Intro a Lenguajes decidibles e Indecidibles (prox. clase) |   Navarro Cap. 4.6; Sipser Cap. 3.2| 
11     | 17     | Computabilidad       | Lenguajes Decidibles, El problema de la aceptación (y de la detención), Lenguajes no decidibles | Navarro Cap. 5.1; Sipser Cap. 4.1,4.2  | 
12     |        | (feriado)            | | | 
12     | 18     |                      | Más lenguajes no decidibles, lenguajes no reconocibles, Teorema de Rice | Navarro Cap. 5.2,5.3; Sipser Cap. 5.1 (hasta pág. 220)  | 
12+    | 19+    | (Opcional)           | Reducciones de Mapeo | Sipser Cap. 5.3  | Material extra, se dará lectura opcional.
12+    | 19++   | (Opcional)           | Problema de Correspondencia de Post, Indecibilidad de Gramáticas Ambiguas | Navarro Cap. 5.4; Sipser Cap. 5.2  | Material extra, se dará lectura opcional.
13     | 20     | Complejidad          | Tiempo de una MT normal, relación con variantes, P y NP  | Navarro Cap. 6.1,6.2; Sipser Cap. 7.1,7.2  | 
13     | 21     |                      | NP y Verificadores Polinomiales  | Sipser Cap. 7.3  | 
14     | 22     |                      | NP Completitud (NPC) y SAT  | Navarro Cap. 6.3; Sipser Cap. 7.3 (hasta antes de Teo. 7.32) | 
14     | 23     |                      | SAT es NPC, 3SAT     | Navarro Cap. 6.4; Sipser Cap. 7.4 (304-311)  | 
14     | 24     |                      | Otros lenguajes NPC | Navarro Cap. 6.5; Sipser Cap. 7.4, 7.5  | 
14+    | 25     | Tópicos              | Decisión vs. Búsqueda                | (Pendiente)  | Opcional: Sujeto a disponibilidad de tiempo.
14+    | 26     |                      | NPC en la práctica, Clases de Complejidad probabilísticas, Complejidad de Espacio, Complejidad Cuántica | Navarro Cap. 6.6; (Pendiente)     | 
14+    | 27     |                      | Demostraciones Interactivas y Zero-Knowledge  | (Pendiente)     | Opcional: Sujeto a disponibilidad de tiempo.

## Bibliografia
- **[Sipser]** Michael Sipser, **Introduction to the Theory of Computation, 
	Third Edition*, 2013. Cengage Learning Press.
	(Ver ucursos.)
- **[Navarro]** Gonzalo Navarro, **Teoría de la Computación (Lenguajes Formales, Computabilidad y Complejidad), Apuntes y Ejercicios**, Universidad de Chile, Dic. 2018.  
  Disponible desde [la página del prof. Navarro](http://www.dcc.uchile.cl/~gnavarro/apunte.html). 
- **[HMU]** J. Hopcroft, R. Motwani, y J. Ullman. *Introduction to Automata Theory, Languages and Computation*. 3er edition, Addison-Wesley, 2007.
- **[LP]** H. Lewis y C. Papadimitrou. Elements of the Theory of Computation. Prentice-Hall, 1981.
