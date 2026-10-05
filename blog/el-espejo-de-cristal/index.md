---
title: El espejo de cristal
subtitle: Reglas, emergencia y el "yo" en los sistemas formales
date: 2026-05-08
series: geb
description: "Notas sobre los primeros capítulos de Gödel, Escher, Bach: el acertijo MU, el sistema mg y el punto en que unos símbolos parecen decir algo."
---

En los primeros capítulos de *Gödel, Escher, Bach*, Hofstadter vuelve jugable un sistema formal. El Sistema MIU y el Sistema mg plantean una duda que quien programa ya conoce. Llega un punto en que una lista de sustituciones deja de sentirse inerte, y los símbolos parecen decir algo.

El MIU es un sistema de reescritura. También cabe verlo como máquina de estados, con la cadena como estado y la regla como transición. Se empieza en MI y hay que llegar a MU con cuatro reglas:

1. Si la cadena termina en I, se le puede agregar una U al final. De MI sale MIU.
2. Se puede duplicar todo lo que va después de la M. De MIU sale MIUIU.
3. Tres I seguidas pueden sustituirse por una U. De MIIII sale MUI o MIU.
4. Dos U seguidas pueden eliminarse. De MUUI sale MI.

El modo mecánico duplica y sustituye, y puede seguir así mucho rato. Hace falta pararse en otro sitio y buscar una propiedad que las transiciones conservan.

El número de I nunca es múltiplo de 3. MI trae una, así que al dividir entre 3 el resto es 1. La regla que duplica lo que va después de la M pasa ese resto de 1 a 2 y, si se vuelve a duplicar, de 2 otra vez a 1. Sustituir tres I seguidas por una U deja el resto igual. Las otras dos reglas no tocan las I. MU tiene cero I, y cero sí es múltiplo de 3. Ninguna derivación llega.

$$n(I) \not\equiv 0 \pmod 3$$

La cuenta es aritmética de afuera. El sistema no la contiene. Saltar fuera, como lo llama el libro, es hablar del algoritmo en lugar de ejecutarlo.

En el capítulo II el Sistema mg separa el símbolo del sentido. La cadena `--m---g-----` se comporta como 2 + 3 = 5. Las letras hacen de marcadores. La suma aparece porque hay un isomorfismo entre los teoremas del sistema y las sumas verdaderas. Quien lee la cadena proyecta sobre ella una estructura que ya conocía.

Wigner llamó a ese encaje la irrazonable eficacia de la matemática. Un juego armado para obedecer reglas termina coincidiendo con una operación del mundo. A veces el formalismo existe primero, y el fenómeno que lo vuelve legible llega después.

Al leer esto pensé en el Juego de la Vida de Conway. El MIU es estrecho. Cuatro reglas, y un imposible que se demuestra desde fuera. La Vida mira cuántas de las ocho vecinas están vivas. De esa cuenta salen gliders, y también patrones capaces de calcular. La regla solo habla de vecinas. El glider hay que verlo en la cuadrícula.

Hofstadter lleva el mismo hilo hasta la consciencia, con los bucles extraños. Hay configuraciones que procesan información sobre su propio estado. En ese pliegue aparece lo que llamamos un yo. En su vocabulario sería un isomorfismo de nivel alto. La descripción corta del sistema se porta como un agente. Debajo siguen los símbolos.

Escher lo muestra con la figura y el fondo. Hofstadter pasa esa pareja a los teoremas y a lo que queda fuera del sistema. En el MIU, MU está en el fondo y marca el borde.

De estos capítulos me quedó una distinción que uso. Ejecutar las reglas es una cosa. Describir lo que ninguna secuencia alcanza es otra, y con esa descripción se ve por qué MU no aparece. Para el yo, Hofstadter pide una distancia del mismo tipo, solo que a otra escala.
