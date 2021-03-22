# CC5301  Introducción a la Criptografía Moderna, Otoño 2021
_(Actualizado el 2021-03-22, ver log de cambios al final)_

**Propósito:**

Aprender conceptos, técnicas y resultados del fascinante mundo de la Criptografía moderna :-)

**Profesor:** [Alejandro Hevia](http://www.dcc.uchile.cl/~ahevia/)
- Cátedras: Lunes y Miércoles 10:15am-11:30am (con break de 10min aprox.)
- **Horario Consultas profesor (via Discord): Lunes 4:30pm-5:30pm.** 
- Clases auxiliares: Viernes 10:15am-11:45am 
	- Auxiliares: Ilana Mergudich,.
	- Ayudantes: TBA (por anunciar)
- Sitio web oficial del curso: este y [ucursos](https://www.u-cursos.cl/ingenieria/2021/1/CC5301/1/)
- [Programa del curso](https://www.u-cursos.cl/ingenieria/2021/1/CC5301/1/datos_curso/bajar_programa?id=5225&556310443)

## Objetivo del curso 

Al finalizar el curso el alumno será capaz de:
* Razonar matemáticamente acerca de la seguridad algoritmos criptográficos tanto del tipo simétrico (clave privada) como del tipo asimétrico (clave púbica).
* Modelar y analizar formalmente algoritmos criptográficos basados en cifradores de bloque, funciones de hash y primitivas basadas en teoría de números, entre otros.
* Diseñar y evaluar soluciones criptográficas para problemas prácticos (confidencialidad, autentificación) presentes en redes de computadores.



## Metodología del Curso

El curso consiste en clases de cátedra más clases auxiliares ambas síncronas (vía zoom). El material docente, el cual incluye presentaciones de clases (anotadas) y pautas de auxiliares, y libros de material de lectura del curso, será publicado en ucursos. Para consultas al equipo docente y discusión de la materia pueden usar el foro de ucursos o escribirle directamente a los auxiliares.

El material para el curso será principalmente cubierto con las presentaciones de clases. 
Adicionalmente, habrá dos libros de referencias del curso:
- Jon Katz y Yehuda Lindell, _Introduction to Modern Cryptography, 
	Second Edition_. 
- Mihir Bellare y Phil Rogaway, _Introduction to Cryptography, Lecture Notes_. Apuntes de un curso en UCSD.

(Ver links en referencias abajo). 
Se espera que cada estudiante lea y estudie en forma independiente el o los capítulos correspondientes
  a la materia vista en clases. Ellos serán indicados en el calendario más abajo.

El curso está fuertemente basado en trabajo personal (mal que mal, es un curso electivo ;-) ). Se espera que los estudiantes: 
- asistan a las clases de cátedra y auxiliares, (y de ser posible pregunten vía audio o chat),
- lean los capítulos sugeridos de los libros clase a clase,
- interactúen (hagan preguntas) en el foro de estudiantes y chats (por ej. zoom en cátedras y auxiliares),
- resuelvan los problemas propuestos (dejados en clase), y
- resuelvan los problemas de las guías de problemas propuestos.

## Evaluaciones

El curso será completamente evaluado con 3 tareas obligatoria y una recuperativa, a resolver individualmente (ver política de colaboración más abajo).
Para resolver cada tarea tendrán 2-3 semanas, y su solución tendrá dos partes:
- la solución escrita (un PDF en latex o escrita a mano siempre que tenga letra legible y ordenada), y
- un video de a lo más 8 min explicando lo fundamental de su solución (esto NO es re-describir su solución, sino explicar brevemente la idea principal de cada solución, o con qué se inspiraron, o en base a qué problema o lo hicieron, o si no la entendieron completamente, qué si entendieron). **Importante:** Si no entrega video la nota de la evaluación sera 1.0. 

Se espera que cada estudiante **entienda bien su solución**. El equipo docente se reserva el derecho a *citar a entrevista personal (vía zoom)* a algunos estudiantes para que expliquen su solución de la tarea. Cuáles estudiantes serán citados será decidido arbitrariamente por el profesor o incluso escogidos al azar. Note que, el que Ud. sea llamadx _no significa que esté acusado de copia o nada_, simplemente es una manera de confirmar que cada estudiante entiende su solución. Si es llamado a entrevista, la nota final de la solución dependerá tanto de la explicación escrita como de la entrevista.

Habrá un control y un examen al final del curso, ambos online en forma síncrona, en la forma de una entrevista personal. El objetivo del control es simplemente saber si aprendió los contenidos cubiertos en el semestre, nada más. Se que lxs puede poner nerviosos la idea de una entrevista, pero realmente no queremos estresarlxs. ¿Cómo? El contenido a preguntar en el control estará limitado a las preguntas dadas en las tareas y a las preguntas de una guía de problemas que entregaremos un par de semanas antes del control. **Si han hecho las tareas y saben cómo resolver los problemas de la guía, entonces pasarán sin problemas el control. De hecho, si demuestra que Ud. hizo las tareas (que entiende lo que hizo) lo más probable es que su nota sea igual o mejor al promedio de sus tareas.**.  Y si pasan el control, es muy probable que se eximan del examen. De hecho, la única razón que deban dar el examen es que les vaya mal en el control (esto es, no puedan demostrar que pueden explicar la materia de las tareas) y por lo tanto el examen se transforma en una segunda oportunidad de demostrarlo. El examen cubrirá la misma materia que el control.

Tendremos una tarea extra opcional para recuperar la nota al final. El examen (eximidos con 5.0) será en forma síncrona, en la forma de una entrevista.

### Calendario Evaluaciones

* **Tarea 1 (T1)**: 

  - Fecha publicación: TBA.
  - Fecha de entrega: TBA.
  - Contenidos: Confidencialidad perfecta, PRFs, Encriptación Simétrica.

* **Tarea 2 (T2)**: 

  - Fecha publicación: TBA.
  - Fecha de entrega: TBA.
  - Contenidos: TBA.

* **Tarea 3 (T3)**: 
  
  - Fecha publicación: TBA.
  - Fecha de entrega: TBA.
  - Contenidos: TBA.

* **Tarea Rec (TR)**: (Puede reemplazar una tarea) 
  - Fecha publicación: TBA.
  - Fecha de entrega: TBA.
  - Contenidos: TBA.

* **Control 1 (C1)**:
  - Fecha publicación: TBA.
  - Fecha de entrega: TBA.
  - Contenidos: Casi toda la materia (excepto la última semana).

**Cálculo de nota NC:** La nota de control NC, se calculará como sigue. Primero se calcula PT como el promedio de las notas T1,T2,T3, luego que la peor nota de T1,T2, y T3 haya sido reemplazada con la nota de TR (siempre que ello beneficie al/a la estudiante). Luego, se calcula NC como el promedio de PT y C1.
  
**Examen y eximición:** Quienes obtengan NC sea menor a 5.0, deberán dar el exámen (EX). En dicho caso, la nota final del curso (NF) se calcula como el promedio ponderado 60% NC y 40% EX. De eximirse del examen, NF será igual a 50NC .

**Aprobación**: Debe tener NF mayor o igual a 4.0.

### Atrasos en Evaluaciones

Las evaluaciones tendrán una fecha y horario de entrega (típicamente 23:59hrs) pero se aceptarán atrasos de hasta 5 días siguiendo las siguientes reglas:

- Cada estudiante tendrá hasta un máximo de 9 días de atraso que puede usar libremente en las 3 tareas (T1, T2 y T3),
- No puede usar más de 5 días para cualquier tarea individual (para no atrasar las notas),
- Días de fin de semana y semanas de receso no cuentan en los días de atraso, y
- Una vez que el estudiante haya utilizado la totalidad de sus días de atraso, cualquier entrega que haga posterior a la fecha de entrega será calificada con nota 1.0. 
- Estos días de atraso NO se podrán aplicar a la tarea recuperativa (TR) pues los tiempos son más ajustados para la correción. 

## Politica de Colaboración

Para resolver las actividades evaluativas, pueden colaborar entre dos o más personas siempre que usen la política de _Whiteboard_ (o "pizarrón en blanco"), esto es
- Al juntarse, pueden compartir un pizarrón o editor donde ambxs escriban y discutan cómo resolver el problema, pero **nadie puede grabar ni tomar fotografías**.  
- Al terminar, se "borra" (se cierra), y luego de 30min, cada unx escribe/redacta su solución en forma individual.

Se prohibe buscar soluciones por Internet, o usar las soluciones de otra persona.
(En serio, no use soluciones encontradas en Internet, no sólo por un tema ético sino porque hay muchas equivocadas o que usan ideas o conceptos que vemos distinto en este curso).

Para más detalles o en caso de duda, preguntar a los auxiliares o al profe.

## Donde colaborar y preguntar

Existe un servidor de [Discord](https://discord.gg/bujVyNVK) para el curso (si el link expiró, preguntar en ucursos). Está disponible para contactar a los auxiliares, ayudantes y el profesor; además puede usarlo para colaborar si lo desea. Si no sabe usarlo, preguntar en el foro.

## Calendario

__(Actualizado 2021-03-17)__

Semana | Clase  | Tema                 | Contenidos        | Lecturas                       | Comentarios    
:----  | :----: | :--------------:     | :--------------   | :--------------                |  :---------
1      | 1      | Introducción         | Motivación        |  KL cap 1.1, 1.2, BR. Cap. 1 |  
       | 2      | Cifradores clásicos  | Cifradores históricos, ataques | KL cap 1.3, , BR Cap. 2, PT. Cap. 5 (probabilidades)|  
2      | 3      | Confidencialidad Perfecta  | Definición, One-Time Pad, Resultados   | KL Cap. 2,  |  | 
       | 4      |                      | (parte II), Limitaciones  | KL, Teo. 2.10 y Cap. 2.4 |


## Bibliografia
- **[KL]** J. Katz, Y. Lindell, **[Introduction to Modern Cryptography](http://www.cs.umd.edu/~jkatz/imc.html)**, 
	Second Edition, Chapman & Hall/CRC Press, 2007. 
	(En biblioteca y ucursos.). Ver la [errata](http://www.cs.umd.edu/~jkatz/imc/errata.pdf) y la sec. 4.6.3 [revisada](http://www.cs.umd.edu/~jkatz/imc/hash-erratum.pdf). 
- **[BR]** M. Bellare, P. Rogaway, **Introduction to Cryptography, Lecture Notes**, University of California San Diego, 2005.  
  	(En ucursos, disponible transparencias de versiones del curso para pregrado, y de postgrado). 
- **[SB]** V. Shoup and D. Boneh, **A Graduate Course in Cryptography**, 2017. Disponible online gratis.
- **[Smart]**, N. Smart, **Cryptography, An Introduction**, 2013. Disponible online gratis.
- **[Shoup]**, V. Shoup, **A Computational Introduction to Number Theory and Algebra**, 2008. Disponible online gratis.
- **[Katz]**, J. Katz, **Digital Signatures**, Springer, 2010, disponible desde la red de la FCFM o usando la VPN del CEC.
- **[Stinson]**, D. Stinson, **Cryptography, Theory and Practice**, Second edition, Editorial Cgapman and Hall/CRC, 2002
- **[MvOV]**, A. J. Menezes, P.C. van Oorschot, S. A. Vanstone, **Handbook of Applied Cryptography**, CRC press, 1997. Disponible online.
- **[PT]**, R. Pass, W. Tseng, **A Course in Discrete Structures**, lecture notes. 2011. [Disponible online](http://www.cs.cornell.edu/~rafael/discmath.pdf).

## Log de Cambios

- 2021-03-17: 11:56am: Se agregó hora de consulta del profe.
- 2021-03-19: 2:30pm: Cambio en el horario de consulta del profe (5pm en vez de 6pm).
- 2021-03-22: 3pm: Cambio en el horario de consulta del profe (4:30pm en vez de 5pm, sorry :-) );
- 2021-03-22: 5pm-11pm: Actualización del calendario y lecturas.
