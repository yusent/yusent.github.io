---
title: El vértigo de la autorreferencia
subtitle: Un ouroboros entre código, arte y lógica
date: 2026-03-26
series: geb
description: "Notas sobre la introducción de Gödel, Escher, Bach: bucles extraños, programas que se imprimen a sí mismos y lo que la lógica no alcanza a ver."
---

Gödel, Escher y Bach parecen hablar idiomas distintos, pero en la introducción del libro Hofstadter encuentra en los tres un mismo fenómeno, al que llama *bucle extraño*. Ocurre cuando, al subir o bajar por los niveles de un sistema, uno se encuentra de vuelta en el punto de partida.

Bach lo hizo con un canon que parece subir de tono sin detenerse nunca. Escher dibujó escaleras por las que se asciende sin parar y que aun así no llevan a ningún lado. Gödel construyó una afirmación matemática que habla de sí misma, y con ella demostró que las matemáticas siempre tendrán verdades que no pueden probarse.

## Un autor soñado por su personaje

Para entender el bucle me sirve un ejercicio de pensamiento basado en dos de los principios herméticos.

El primero es el mentalismo, "todo es mente". Imaginemos a un escritor que crea un personaje. Para ese personaje, la mente del escritor es su universo entero, su Dios. El segundo es la correspondencia, "como es arriba, es abajo": ese personaje escribe a su vez una historia sobre otro personaje, que escribe la suya, y así sucesivamente, como en un fractal.

El giro llega si el último personaje de la cadena es quien termina imaginando al autor original. Con eso se cierra un bucle extraño de *N* niveles y la jerarquía se enreda. ¿Quién es el soñador y quién es el sueño? Escher capturó esta idea en *Manos dibujando*, donde dos manos se dibujan la una a la otra y desaparece la distinción entre creador y creado.

## Programas que se escriben a sí mismos

En el software existen objetos que tienen esta misma magia. Un *quine* es un programa diseñado con un solo propósito, que es imprimir su propio código. No calcula nada. Existe como un reflejo perfecto de sí mismo.

Hay una versión extrema, el [quine ouroboros](https://github.com/mame/quine-relay): un programa en un lenguaje genera un programa en otro lenguaje, que genera uno en un tercero, y tras 128 pasos por 128 lenguajes distintos regresa al código original. Es la versión digital del *Canon per Tonos* de Bach, que tras seis modulaciones regresa a la tonalidad inicial, pero una octava más arriba.

El bucle también puede salir mal. Cuando un programa entra en una recursión que no tiene salida ocurre un *stack overflow*, un desbordamiento de pila. Imaginemos una biblioteca donde para entender un libro hay que leer otro, y ese otro manda a uno más. Si la cadena no termina, tarde o temprano se acaba el espacio en la mesa para los libros abiertos. Ese colapso de memoria es el vértigo de la máquina, el momento en que su "mente" finita se topa con un proceso infinito.

## Los lentes de la lógica

Gödel demostró que la demostrabilidad es más débil que la verdad. Hay cosas ciertas que las reglas de un sistema simplemente no pueden alcanzar.

Me gusta pensar en la lógica como un par de lentes. Durante siglos usamos el lente euclidiano y creímos que dos líneas paralelas nunca se cruzan, porque era lo lógico. Al cambiarlo por uno no euclidiano descubrimos que sí pueden cruzarse. La "realidad" cambió porque cambiamos las bases.

Las experiencias psicodélicas sugieren algo parecido sobre nosotros mismos. Lo que llamamos lógica sería una construcción de nuestra estructura cerebral, y al alterar esa arquitectura los lentes habituales se rompen. Quizás el determinismo que buscamos en el cosmos, la respuesta a la materia oscura o al caos cuántico, esté ahí, y nuestra computadora biológica no tenga el software necesario para procesarlo sin usar la probabilidad como muleta.

## ¿Quién programa a quién?

Si una inteligencia artificial logra modificarse a sí misma, aparece la paradoja del barco de Teseo. Si reemplazamos todas las piezas de un barco, ¿sigue siendo el mismo barco? Si la IA cambia su propia lógica, ¿es la misma entidad o una nueva?

Hay una versión todavía más interesante. Cuando nosotros modificamos una IA porque su comportamiento nos dio ideas nuevas, ¿no es la IA la que nos está usando para actualizarse? Entramos en lo que Hofstadter llama una *jerarquía enredada*, donde el usuario y la herramienta se programan mutuamente.

Bach, Escher y Gödel invitan a ver la inteligencia como algo más que seguir reglas. Incluye la capacidad de "saltar fuera" del sistema para cuestionarlo. El subtítulo del libro en español es *Un Eterno y Grácil Bucle*, y al final todos somos parte de él, intentando entender el código que nos escribe mientras nosotros mismos intentamos escribirlo.
