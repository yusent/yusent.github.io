---
title: El espejo de cristal
subtitle: Reglas, emergencia y el "yo" en los sistemas formales
date: 2026-05-08
series: geb
description: "Notas sobre los primeros capítulos de Gödel, Escher, Bach: el acertijo MU, el sistema mg y el momento en que unas reglas inertes empiezan a parecer que tienen sentido."
---

En los primeros capítulos de *Gödel, Escher, Bach*, Hofstadter toma la lógica simbólica y la vuelve un juego en el que se puede perder. El Sistema MIU y el Sistema mg sirven para dejar planteada una pregunta que también aparece al escribir programas. ¿En qué momento un conjunto de reglas inertes empieza a parecer que posee sentido, o incluso algo parecido a una consciencia?

El MIU se deja mirar como una máquina de estados: cada cadena es una configuración, cada regla una transición. El acertijo pide producir `MU` a partir de `MI` con cuatro reglas:

1. Si la cadena termina en `I`, se le puede agregar una `U` al final. De `MI` sale `MIU`.
2. Se puede duplicar todo lo que va después de la `M`. De `MIU` sale `MIUIU`.
3. Tres `I` seguidas pueden sustituirse por una `U`. De `MIIII` sale `MUI` o `MIU`.
4. Dos `U` seguidas pueden eliminarse. De `MUUI` sale `MI`.

Quien se queda en el modo mecánico duplica y sustituye, y esa búsqueda puede no acabar. El modo inteligente es el que sale del sistema. Desde fuera se ve un invariante. No es la paridad de las `I`, el que sean pares o impares, sino el resto de dividir su número entre 3: se conserva en 1 o en 2, y no llega a 0.

$$n(I) \not\equiv 0 \pmod 3$$

Se parte de `MI`, una sola `I`, resto 1. La regla que duplica lo que sigue a la `M` lleva ese resto de 1 a 2, y una duplicación nueva lo devuelve a 1. Sustituir tres `I` seguidas por una `U` resta un múltiplo de 3, así que el resto no se mueve. Las otras dos reglas no tocan las `I`. `MU` tendría cero `I`, y cero es múltiplo de 3. Ninguna derivación entra ahí. La prueba no consiste en buscar durante más tiempo. Consiste en mirar el algoritmo con una aritmética que el sistema no contiene, fuera del tiempo en que las reglas se ejecutan. Esa mirada es una autorreferencia modesta, y basta para cambiar el problema de naturaleza.

En el capítulo II, el Sistema mg desplaza la pregunta del alcance al significado. La cadena `--m---g-----` se comporta como 2 + 3 = 5, pero las letras no guardan la suma en su interior. Lo que hay es un isomorfismo. Quien la lee proyecta sobre el sistema formal una estructura que ya conocía, y solo entonces los símbolos parecen decir algo.

De ahí la sensación que Wigner llamó la irrazonable eficacia de la matemática. Un sistema inventado para obedecer reglas termina, a menudo, por ser el espejo de una ley que el mundo todavía no nos había mostrado. A veces el formalismo existe primero. El fenómeno físico que le da un significado activo llega después, y encuentra el mapa ya dibujado.

La conexión con el Juego de la Vida de Conway se me hizo inevitable. Al lado del MIU, rígido y cerrado por un invariante, el autómata de Conway enseña el otro extremo: una complejidad que parece viva, salida de una regla mínima. La celda atiende a la densidad de sus vecinas. De esa cuenta nacen gliders y naves, y también construcciones capaces de calcular. La regla no dice que haya que moverse, ni reproducirse, ni procesar información. Esas conductas aparecen cuando la cuadrícula lleva suficiente tiempo iterando.

Si un sistema tan parco genera estructuras que se desplazan y que computan, la hipótesis de Hofstadter se vuelve más hospitalaria. La conciencia sería un isomorfismo de alto nivel. Debajo siguen interacciones materiales. En cierto pliegue, el sistema procesa información sobre su propio estado, un bucle extraño, y de ese cierre sale la ilusión de un yo puesto en el centro.

Escher ilumina el mismo borde. La figura corresponde al teorema, el fondo a lo que el sistema no alcanza, y ese espacio negativo le da a la verdad visible su contorno. Un sistema formal lo bastante enredado puede dejar de reconocerse como manipulación de símbolos y contarse a sí mismo una historia hecha de intenciones. Somos el resultado de unas cuantas reglas que, tras muchísimas iteraciones, han aprendido a preguntarse por qué existen.
