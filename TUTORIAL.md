# Tutorial comparación de frameworks

> **TL;DR** <br>
> Propuesta para realizar una serie de screencast en que se desarrolle en paralelo una misma aplicación web con distintos frameworks js frontend

## Contexto

Actualmente existen muchos frameworks para el desarrollo frontend en comparación a años (o meses) atras, y constantemente están apareciendo más. Es por esto, que una de las preguntas más frecuentes entre quienes se inician en la programación con javascript, o incluso entre quienes ya tienen más experiencia, es ¿Qué framework aprender?¿Qué ventajas tiene uno sobre otro?
Es por esto, que existen una serie de comparaciones de frameworks, siendo las más populares las comparaciones entre [Angular](https://angularjs.org/) y [React](https://facebook.github.io/react/), sin embargo, pocas de estas comparaciones son _practicas_, en su mayoria se trata de comparaciones teoricas y a lo más tecnicas, pero que poco sirven para orientar a los novatos en su elección.
Pensando en lo anterior, y basado en el lema del [_aprender haciendo_](https://en.wikipedia.org/wiki/Experiential_learning), es que creo sería útil un tutorial practico de comparación de frameworks, y en este documento ordenaré mis ideas al respecto.

## Idea

En general, la idea es sencilla: desarrollar **la misma aplicación** con distintos frameworks. En cuanto a los detalles, hay que considerar lo siguiente:

* El seteo de los ambientes de desarrollo no debiese ser incluido en el tutorial, ya que no es parte integral del desarrollo en cada framework y depende principalmente de los gustos del programador.
* La aplicación debe ser simple, pero completa, para adaptarse a los requerimientos reales de un proyecto web, es decir, debiese incluir, por lo menos **manejo de rutas, manejo de estado y conecciones HTTP**
* Los recursos que no sean relativos al framework, deben ser comunes para cada una de las aplicaciones finales, es decir, los estilos, imagenes y la API HTTP que se consulte
* También es recomendable realizar una serie de test relativos a metricas de comparación de las aplicaciones. Estas metricas son: LOC (lineas de codigo), performance de algunas tareas por definir, numero de dependencias utilizadas, tamaño final en Kb de las aplicaciones, entre otras.

## Requisitos

La mayoria de los requisitos ya son evidentes:

* Una API (y un servidor para alojarla), debidamente documentada y configurada (sin problema con CORS, por ejemplo)
* Hojas de estilo comunes (CSS), puede ser algun framework como Bootstrap o Materialize
* Un repositorio para cada proyecto
* El detalle del seteo de ambiente de desarrollo*

_* Si bien se menciono que este seteo no va incluido en los screencast, es necesario incluir algún pequeño instructivo, probablemente en el README de cada proyecto final, con las consideraciones de configuracion_

## Pasos a seguir

1. Discutir sobre la propuesta y llegar a un concenso común.
2. Una vez aceptada, encontrar voluntarios: 1 por cada framework y a lo menos 1 para configurar recursos comunes.
3. Diseñar la aplicación a desarrollar. Debe ser diseñada de tal manera, que el producto final de cada framework sea equivalente para un usuario final.
3. Crear una aplnificación. Lo ideal sería dividir la aplicación a desarrollar en etapas y por cada etapa, cada desarrollador entregar un screencast del hito desarrollado. Las etapas y la entrega de los videos no debiese demorar más de una o dos semanas entre cada una.
4. Una vez recibidos todos los videos, se deben editar para dejarlos juntos y liberar por cada etapa, un unico video con los detalles de la implementación en cada framework.
5. Cuando hayan concluido todas las etapas, se debiese incluir en un ultimo video el resultado de cada uno de los test anteriormente definidos.




