<!--hide-->
# Clasificación de Cartas con Algoritmo de Burbujas
<!--endhide-->

La clasificación se considera un concepto importante en muchos lenguajes de programación, ya que nos ayuda a ubicar elementos de una manera más rápida y sencilla.

El algoritmo de clasificación de burbujas es uno de los más fáciles de aprender y ese es el primero que se enseña normalmente. Aquí hay una explicación de 5 minutos sobre cómo funciona el algoritmo de burbuja:
[https://www.youtube.com/watch?v=xli_FI7CuzA](https://www.youtube.com/watch?v=xli_FI7CuzA)

<how-to-start>
    
## 🌱  Cómo iniciar este proyecto

No clones este repositorio porque usaremos una plantilla diferente.  

Recomendamos abrir el `vanillajs boilerplate`, utilizando una herramienta de aprovisionamiento como [Codespaces](https://4geeks.com/es/lesson/tutorial-de-github-codespaces) (recomendado) o [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod). Alternativamente, puedes clonar el repositorio de [GitHub](https://4geeks.com/es/how-to/como-clonar-un-repositorio-de-github) en tu computadora local utilizando el comando `git clone`.  

Este es el repositorio que necesitas abrir o clonar:  

```sh
$ git clone https://github.com/4GeeksAcademy/vanillajs-hello
```

💡 Importante: recuerda crear un nuevo repositorio, actualizar el control remoto (`git remote set-url origin <tu nueva url>`) y cargar el código en tu nuevo repositorio usando `add`, `commit` y `push`.

</how-to-start>

## Instrucciones

1. Crea una función que genere una lista de cartas al azar.
1. Permite que el usuario especifique cuántas tarjetas aleatorias debe generar el sitio web utilizando una entrada de texto.
2. Agrega un botón de "sorteo" que, al hacer clic, hace que esas tarjetas en el sitio web sean hermosas.
3. Agrega un botón de "clasificación" que ordene las tarjetas usando el algoritmo de clasificación `bubble`.
4. Guarda todos los cambios difíciles de realizar al ordenar la lista de tarjetas en una nueva matriz.
5. Muestra el registro completo de cambios uno encima del otro.

Esta es una animación de cómo debería verse su aplicación:

![Bubble Sorting Cards on a website](https://raw.githubusercontent.com/breatheco-de/exercise-sorting-cards-with-bubble/master/preview.gif)

Pista:

1. La estrategia primero, nadie comienza a codificar la solución antes de tener una estrategia clara.
2. Apégate a tu estrategia, olvídate del stackoverflow para la estrategia.
3. Divide y conquista, intenta separar el ejercicio en ejercicios más pequeños, por ejemplo:
    - Crea el CSS y HTML codificados antes de intentar que sea dinámico, eso te dará una idea clara de qué código HTML necesitas construir con su algoritmo.
    - Primero genera un array de tarjetas aleatorias, asegúrese de que se está generando correctamente (utilizando la consola.log) antes de intentar procesarla en el sitio web.
    - Crea una función solo para crear el HTML de UNA tarjeta y luego reutilícela para renderizar todo.
