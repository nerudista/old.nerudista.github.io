---
layout: post
title:  "Mi Facebook con @tacosdedatos"
date:   2020-07-04 10:00:00 -0500
categories: colaboraciones
subtitle: "Una vistazo a mi data en Facebook"
background: '/img/colaboraciones/post02/header.png'
---

## Dueño de mis datos

_Los datos son el nuevo petróleo_ es una de las frases más comunes en los últimos años. Hay muchas aristas que se pueden debatir de ese punto pero hay una que creo comparten: alguien los puso ahí, sin darse cuenta, para que cualquiera pueda extraerlos y sacarles jugo.

Durante años fui ávido usuario de redes sociales y nunca tuve reparo en compartir fotos, videos, opiniones y cosas personales que hoy preferiría no haber subido. He dado de baja varias de mis cuentas pero no me fui sin haber extraído la información que las empresas tenían de mí.

Tal fue el caso de Facebook.

## Text Mining en mí mismo

Este proyecto nació después de haber tomado un curso de Text Mining con un gran experto de R: [Manuel Toral](https://twitter.com/jmtoralc). Durante un mes trabajamos desde los principios básicos, como la _tokenización_ de los _corpus_, hasta cosas no tan básicas como _Latent Dirichlet Allocation_. En ese tiempo minamos datos de páginas de internet, tuits y  notas periodísticas. Sin embargo, quería llevarlo un paso más allá teniéndome como sujeto de prueba.

Gracias a que el siempre generoso [@tacosdedatos](https://twitter.com/tacosdedatos) me ofreció un espacio en su blog, decidí utilizar la información que tenía guardada de Facebook para aplicar lo que vi en el curso de Minería de Texto. Si no conocen su [página](https://tacosdedatos.com/), es hora de darse una vuelta. Gente muy buena escribe ahí con la finalidad de compartir su conocimiento con la gente que está empezando en estos temas. 

El resultado fueron no [uno](https://tacosdedatos.com/Dueno-de-mis-Datos-Facebook), ni [dos](https://tacosdedatos.com/Dueno-de-mis-Datos-Facebook) sino [tres](https://tacosdedatos.com/Dueno-de-mis-Datos-Facebook-Parte-III) artículos con el paso a paso de cada análisis y gráfica que hice y de la preparación de los datos que como se sabe bien, es lo que más tiempo lleva.

Si se dan una vuelta por esas colaboraciones, podrán encontrar cosas como:

Si era más negativo en mis posts o en los comentarios que hacía en los posts de otras personas.

![afinn](/img/colaboraciones/post02/afinn.png)


Una _wordcloud_ con las palabras que más utilicé durante mis 8 años en la red.

![wordcloud](/img/colaboraciones/post02/wordcloud_quanteda.png)


Otra _wordcloud_ pero diferenciando las palabras negativas y positivas más recurrentes:

![comparacion_cloud](/img/colaboraciones/post02/comparacion_cloud.png)

O los tópicos más comunes con sus palabras más relevantes:

![prob_topico](/img/colaboraciones/post02/prob_topico.png)

Por si fuera poco en la [segunda parte ](https://tacosdedatos.com/Dueno-de-mis-Datos-Facebook-Parte-II)de la serie escribí acerca de la importancia de las guías de estilo para visualización y ocupé la del [Urban Institute](http://urbaninstitute.github.io/graphics-styleguide/) para las gráficas que construí.

En la serie está compartido el código que usé en cada fase del proyecto. Espero les sea de utilidad para nerudear sus datos.

Hasta la próxima.

