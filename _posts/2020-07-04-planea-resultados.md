---
layout: post
title:  "Medir para Educar: Evaluaciones PLANEA en México "
date:   2020-07-04 10:00:00 -0500
categories: educacion
subtitle: "¿Y cómo le va a la escuela de tus hijos, sobrinos o hermanos?"
background: '/img/posts/post01/header.jpg'
---

## Todo empezó con una pregunta

Hace unos meses algunos padres de familia pedimos una reunión con la maestra titular de una de mis hijas para platicar sobre varios temas, referentes al desempeño escolar, que nos tenían preocupados. Si bien se tocaron temas como la importancia, o no, del factor social en la educación, el valor de la reglas o la cantidad de tareas que se dejaban; lo que más me dejó intrigado fue la aseveración sobre la caída del nivel académico del colegio y el cómo otros colegios estaban dando mejor educación. Cuando pregunté acerca de los datos que respaldaban tal creencia resultó que no habían. O al menos eso creí. 

## Las pruebas PLANEA y ENLACE

Durante los años 2006 al 2013 en México se aplicó la prueba estandarizada ENLACE (Examenes Nacionales del Logro Académico en Centros Escolares) a todos los niños desde tercero de primaria hasta tercero de secundaria. Estas pruebas llevaban consigo algunos vicios y virtudes que fueron determinantes para que en 2015 se aplicara la nueva prueba PLANEA (Plan Nacional para la Evaluación de los Aprendizajes) que sustituía a la ENLACE. La PLANEA sólo se aplica, en educación básica, a niños de 6º de primaria y 3º de secundaria y según la SEP [^1] tiene las siguientes intenciones:

- *Informar a la sociedad sobre el estado que guarda la educación del país en términos del logro de aprendizaje de sus estudiantes de educación básica y media superior.*
- *Aportar a las autoridades educativas información relevante para el monitoreo, la planeación, programación y operación del sistema educativo y de sus centros escolares.*
- *Ofrecer información pertinente, oportuna y contextualizada a las escuelas y a los docentes, que ayude a mejorar sus prácticas de enseñanza y el aprendizaje de sus estudiantes.*
- *Contribuir al desarrollo de directrices para la mejora educativa con información relevante sobre los resultados educativos y los contextos en que tienen lugar.*

La misma SEP alienta[^2] a los padres de familia a usar los resultados de esta prueba para intentar responder las siguientes preguntas:

- *¿Qué apoyos podemos ofrecer para que los estudiantes logren los aprendizajes clave?*
- *¿Qué le hace falta a la escuela?*
- *¿Cómo podemos colaborar con la escuela?*


Las áreas que evalua son **Matemáticas** y **Lenguaje Y Comunicación**. En cada rubro se aplican 46 preguntas, dando un total de 92 reactivos, y los resultados de las pruebas agrupan a los alumnos en cuatro categorías:

- Con conocimiento **Insuficiente**
- Con conocimiento **Indispensable**
- Con conocimiento **Satisfactorio**
- Con conocimiento **Sobresaliente**

## Revisando el desempeño

Si se pregunta porqué como padre debería importarle este tipo de evaluaciones, podría mencionar el estudio[^3] del 2011 que sugiere que un mejor maestro de preescolar conlleva una mayor probabilidad de terminar la universidad  y de tener mayores ingresos a los 27 años, o el del 2014[^4], que indica que un docente con mayor "valor agregado" en cuarto de primaria aumenta, en promedio, el ingreso futuro del estudiante en alrededor de 39,000 dólares durante su vida adulta. Si bien estos estudios se llevaron a cabo en Estados Unidos, nos pueden dar una idea de la importancia de una buena educación desde edades tempranas.

Los resultados de las pruebas PLANEA se encuentran en la página de la SEP[^5], donde se pueden consultar resultados por escuela o hasta por alumno, o también en portales como [Mejora Tu Escuela](http://www.mejoratuescuela.org/) que incluso crea un ranking y tiene herramientas para comparar por escuela.

Sin embargo, esas herramientas no me dejaban ver gráficamente el desempeño del colegio respecto a los demás en el municipio. O si este se comporta mejor respecto a otros en el estado.

Es por esto que decidí construir una aplicación que me permitiera ver el desempeño de todas las escuelas de una manera diferente.

## Las agradables, y las muy desagradables, sorpresas

Por cosas de la vida mis hijas asisten a colegios en diferentes alcaldías de la Ciudad de México. Si quisiera que fueran en la misma, ¿cuál deberìa ser?. ¿En qué alcaldía hay, en promedio, mejor educación?

Tomando un par de alcaldías, por ejemplo Azcapotzalco y Miguel Hidalgo, puedo ver como en la primera:

![img1](/img/posts/post01/Azcapo.png)

- Hay un gran número de escuelas con alumnos calificados con conocimiento **Insuficiente** mayor al 25%, incluso mayor al 50%. Es decir, hay escuelas donde la mitad de los niños no tienen los conocimientos básicos en Matemáticas. En cierta forma, en balde asistieron a la escuela.
- El grueso de los colegios está por abajo del 40% en el porcentaje de alumnos como **Sobresalientes** 
- El top 10 de escuelas (marcado en azul) prácticamente no tienen alumnos con nivel **Insuficiente** y el nivel de alumnos con **Sobresaliente** es de entre el 50% y el 100%.
- Hay algunas escuelas fuera del top 10 que tambien alcanzan niveles mayores al 40% de alumnos calificados con conocimiento **Sobresaliente**.


Por otro lado, en Miguel Hidalgo

![img2](/img/posts/post01/MH.png)

- El número de escuelas con alumnos calificados con conocimiento **Insuficiente** también es muy alto. Hay una escuela que tiene el 100% de alumnos bajo ese rubro.
- El grueso de los colegios está por abajo del 40% en el porcentaje de alumnos como **Sobresalientes**  aunque existen algunos colegios, fuera del top 10, que también están por arriba de ese porcentaje. Se puede ver en las líneas grises que acompañan a las azules.
- El top 10 de escuelas (marcado en azul) tampoco tienen muchos alumnos con nivel **Insuficiente** y el nivel de alumnos con **Sobresaliente** es de entre el 50% y el 100%.

![img3](/img/posts/post01/tabla_azca.png)

¿Pero qué pasaría si decidiera moverme de ciudad, por ejemplo, a San Cristobal de las Casas, Oaxaca o Puebla? 

En San Cristobal de las Casas hay muchas menos opciones de educación primaria e incluso las mejores escuelas tienen un alto porcentaje de alumnos con calificación **Insuficiente** y un porcentaje muy bajo en calificación **Sobresaliente**.

![img3](/img/posts/post01/San_Cristobal.png)


En la pestaña "Tabla de Datos" están los resultados en **Matemáticas** y **Lenguaje y Comunicación** de cada escuela. También están los rankings municipales y estatales. De ahí se observa que la mejor escuela en San Cristobal de las Casas es la 91 en todo Chiapas y en ninguno de los mejores cinco colegios hay alguno que tenga más del 30% de alumnos dentro del rango Sobresaliente.

![img3](/img/posts/post01/San_Cristobal_Tabla.png)


Si la educación de mis hijas fuera un factor determinante para escoger donde vivir, probablemente ese municipio no sería una buena opción para mí.

## ¿Y la escuela de mis hijos/sobrinos/nietos/hermanos?

La aplicación está construida para que cualquiera pueda hacer uso de ella. Incluso se puede buscar directamente la escuela dentro de la tabla de datos. 

![search](/img/posts/post01/Search.png)


La aplicación se encuentra en el siguiente enlace:

[https://nerudista.shinyapps.io/Planea_resultados/](https://nerudista.shinyapps.io/Planea_resultados/)


Una vez dentro hay tres opciones que se deben escoger:

- Entidad Federativa
- Municipio
- Nivel (Primaria o Secundaria)

Del lado derecho se pintan dos gráficas y una tabla de datos. Una de las gráficas muestra los resultados en **Matemáticas** y la otra en **Lenguaje y Comunicación**. La tabla, como se revisó anteriormente, arroja los resultados y los rankings de cada escuela.

Los invito a usar la aplicación y a conocer los resultados de las escuelas de su gente cercana para que puedan acercarse y hacer las sugerencias que consideren oportunas. La educación es la principal heramienta que tenemos para mejorar la movilidad social. 

 

---------------------------------------------
[^1]: http://planea.sep.gob.mx/content/general/docs/2015/PlaneaFasciculo_1.pdf
[^2]: http://planea.sep.gob.mx/content/general/docs/2015/PlaneaFasciculo_4.pdf
[^3]: https://www.nber.org/papers/w16381
[^4]: https://www.nber.org/papers/w19424
[^5]: http://www.mejoratuescuela.org/