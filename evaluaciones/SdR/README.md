# Sesiones de requisitado

## ¿Por qué?

Una parte importante de los proyectos de software fracasa porque no se realiza adecuadamente la disciplina de requisitado, la puerta de entrada al desarrollo de una aplicación: se construye bien algo que no era lo que se necesitaba (Hofmann y Lehner, 2001; Verner et al., 2005).

Referencias:

- Hofmann, H. F., y Lehner, F. (2001). Requirements engineering as a success factor in software projects. *IEEE Software, 18*(4), 58-66.
- Verner, J., Cox, K., Bleistein, S., y Cerpa, N. (2005). Requirements engineering and software project success: an industrial survey in Australia and the U.S. *Australasian Journal of Information Systems, 13*(1).

## ¿Qué?

La actividad consiste en desarrollar con los alumnos la **disciplina de requisitado**:

> *La disciplina de requisitos es el flujo de trabajo cuyo principal propósito es dirigir el desarrollo hacia el sistema correcto describiendo los requisitos del sistema de tal forma que se alcance el acuerdo entre el cliente, usuarios y desarrolladores sobre lo que el sistema debería hacer*

## ¿Para qué?

- Mejorar la comprensión completa del proceso de desarrollo de una solución que utiliza el software como una de sus herramientas, ejercitando la disciplina mencionada.
- Contar con una serie de artefactos que dejen adecuada y formalmente descrita la necesidad del cliente, y que dejen abierta la puerta a una futura implementación, ya sea como TFG o como proyecto.

## ¿Cómo?

El cliente realiza dos tareas:

1. Contar su día a día, incluidos procesos y flujo de trabajo, *con el mayor detalle posible*. Este relato se relaciona lógicamente con la solución que se solicita en el punto siguiente.
2. Describir la solución que se desea obtener.

Dentro de la disciplina de requisitado, el punto 1 es el que con frecuencia se deja de lado o se menciona muy por encima como parte del punto 2 (o incluso no se menciona). Esto es un error: así como el cliente debe implicarse en la solución que se le desarrolla, el equipo que desarrolla (o, al menos, el que requisita) debe empaparse de la realidad del cliente: cómo trabaja, cómo funciona, qué problemas tiene y cómo los resuelve sin una solución que automatice el trabajo o con una que lo hace a medias.

Al describir el trabajo, el cliente se centra en los problemas que tiene y no en la solución que imagina: la solución se trabaja en la segunda sesión. No hace falta esforzarse por ordenar el relato: se cuenta tal como se vive.

## Documentos

Al final de la dinámica (es decir, a fin de cuatrimestre) existen dos documentos:

- **Modelo del dominio**, que describe la realidad actual del trabajo del cliente: las cosas que se manejan, cómo se relacionan y cómo cambian de estado a lo largo del proceso.
- **Casos de uso**, que describen lo que el cliente quiere hacer, automatizar o mejorar de esos procesos mediante la solución que se desarrollaría. Cada caso de uso se trabaja de forma completa: se identifica, se prioriza, se detalla paso a paso y se prototipa su pantalla, y el conjunto se estructura en un modelo coherente. Los prototipos son lo más fácil de revisar para el cliente: no hace falta saber de informática para decir "esta pantalla no es como trabajamos".

## Sesiones y fechas

La dinámica consta de dos sesiones de dos horas (como máximo) cada una y una defensa final en dos partes:

- **Sesión 1 (semana del 26 al 30 de octubre).** El cliente cuenta su trabajo como se lo contaría a una persona que se incorpora al día siguiente al equipo: sin presentación preparada, sin versión pulida, con las excepciones y los atajos que usa de verdad. El desorden natural de un relato real es parte del ejercicio: los alumnos deben preguntar, ordenar y descubrir lo que falta. Si es posible, se recomienda traer ejemplos reales (formularios, hojas de cálculo, correos) sin datos personales.
- **Entre sesiones.** El equipo de alumnos entrega al cliente el borrador de su modelo del dominio con una petición concreta. El cliente marca lo que no coincide con su realidad.
- **Sesión 2 (semana del 7 al 11 de diciembre).** Los alumnos presentan el modelo corregido y proponen casos de uso. El cliente valida, descarta y prioriza.
- **Defensa final (fecha por confirmar).** En su primera parte, los equipos defienden sus documentos ante el cliente durante 30 minutos y el cliente completa una rúbrica breve. En su segunda parte, la defensa continúa ante el profesor de la asignatura (ver Valoración).

Las fechas son ajustables ante cualquier inconveniente.

Se sugiere acudir a las sesiones con "refuerzos": si asiste una persona que trabaje en el mismo tema y pueda aportar un punto de vista adicional, extra o incluso disruptivo, el resultado mejora.

## Comunicación y revisión

Los equipos son los interlocutores del cliente: lo contactan, acuerdan con él cómo comunicarse y llevan el registro de lo tratado. Tras la primera sesión puede pactarse con los equipos un contacto adicional si hace falta, en el formato que el cliente prefiera: correo electrónico, reuniones, videollamada, etc. Lo esencial es que repercuta lo menos posible en las actividades del cliente. Se puede proponer a los equipos una jornada (o unas horas) de inmersión en el lugar de trabajo, si la discreción de las labores desarrolladas lo permite.

El canal de trabajo por defecto es el repositorio de GitHub del equipo: las dudas y validaciones se plantean como issues o discussions que mencionan al cliente, quien responde allí (requiere una cuenta gratuita de GitHub). Si el cliente prefiere otro canal (correo, Teams u otro), lo indica al equipo, que archiva lo tratado y lo referencia desde el repositorio.

Los equipos ofrecen al cliente todo lo que producen (modelo del dominio, casos de uso, detalle y prototipos) en un formato legible sin conocimientos técnicos, con una petición concreta y una sugerencia de por dónde empezar. El cliente decide qué necesita revisar para dar por válido el proyecto, y el equipo deja constancia de lo que se revisó y de lo que no. La aportación más valiosa del cliente es marcar lo que no coincide con su realidad.

Si en algún momento surge una dificultad (de disponibilidad, de comprensión o de otro tipo), debe comunicarse cuanto antes al equipo o al profesor responsable: hablar a tiempo es la mejor forma de resolverla.

En esta dinámica, los clientes son clientes y los alumnos son ingenieros de requisitos, tal como se ha explicado con claridad a los alumnos. Es una dinámica con la que se encontrarán en su día a día profesional, por lo que cuanto más cercana a la realidad, mejor.

## Valoración

### Primera parte

La defensa final es la tercera cita: los equipos exponen ante el cliente durante 30 minutos y, al terminar, el cliente completa una rúbrica breve de cuatro ítems:

1. La exposición refleja cómo trabaja realmente el cliente.
2. Las preguntas de las sesiones fueron pertinentes.
3. Los casos de uso resuelven un problema real del cliente.
4. Qué se escapó.

La valoración del cliente la pondera el profesor junto a la evaluación de los artefactos, pero no fija la nota por sí sola. El cuarto ítem es información para mejorar y no una penalización.

El ejercicio permite también aprender de los clientes. Se valora cómo se ha desarrollado la relación (si el cliente contó su trabajo tal como es, aportó material real, respondió a las preguntas y revisó lo que se le pidió), pero esto no supone una nota: sirve para mejorar la dinámica y ajustar el peso de la valoración del cliente sobre los equipos.

### Segunda parte

La defensa continúa, ahora con el profesor de la asignatura, quien evalúa la idoneidad de lo presentado en función de la [rúbrica de evaluación de la actividad](rubrica.md). Para aprobar la actividad, el equipo debe superar la evaluación del profesor, que pondera la valoración del cliente.

## Confidencialidad

Los documentos de los equipos pueden ser públicos y lo que el cliente comparta con ellos (incluidos los datos institucionales o la firma de sus mensajes) puede quedar reflejado. El cliente decide qué contar: si hay datos o cifras internas que prefiere no exponer, debe indicarlo al equipo, que las generalizará o las omitirá.

## Ejemplos

Algunos ejemplos de lo obtenido en otros cursos:

- [DocuTrace](https://github.com/TheMoys/24-25-IdSw1-SDR/tree/d7d30d5b40e67b17296fbe88394ef1b14931567e) - aplicación en línea diseñada para la gestión documental dentro de una universidad. Su objetivo principal es permitir a los administradores y trabajadores gestionar y acceder a documentos de manera segura y trazable.
- [JorGestor](https://github.com/martinlopez7/25-26-IdSw1-SdR) - sistema para generar exámenes personalizados y asignárselos a cada alumno mediante una clave única.
- [Guías docentes](https://github.com/natiicruuz/24-25-IdSw1-SDR) - sistema gestor de guías docentes.