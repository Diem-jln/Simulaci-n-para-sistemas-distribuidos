# Bitácora Unidad 1: Aleatoriedad
**Estudiante:** Diego Sebastian Molina Julian
**ID:** 000621964
**Curso:** Simulacion Para Sistemas Interactivos

---

##  Actividad 01: La aleatoriedad 
> *Reflexiones sobre los videos de Casey Reas, Refik Anadol, Tyler Hobbs.*

* **Reflexión principal:**
Al revisar el trabajo y la filosofía de artistas como Tyler Hobbs, Refik Anadol y  Casey Reas, me queda claro que en el arte generativo el concepto de aleatoriedad está muy lejos de ser considerado como caos o desorden. Más bien, se comprende mas como una **herramienta compositiva y principio generativo**.

De los eleemntos proporcionados, destacaria tres ideas fundamentales:

1. **La aleatoriedad controlada aporta naturalidad:** En sus ensayos, Hobbs nos deja claro que la aleatoriedad "uniforme" suele ser visualmente aburrida, ya que distribuye todo por igual y visualmente genera una textura muy parecida a la "estática" de una tele vieja. Lo verdaderamente fascinante ocurre cuando se aplica la *distribución de probabilidad no uniforme*. Ya que sesgar la aleatoriedad (haciendo que ciertos colores o tamaños sean más probables que otros), se puede imitar la variación orgánica que encontramos en areas naturales.

2. **El uso de código como medio expresivo:** Como nos muestra Reas, dibujar con código cambia los limites del artista. Ya no hablamos de pintar un cuadro estático con pintura, sino de diseñar y estableceer un **sistema de reglas**. La aleatoriedad se implanta en estas reglas, todo con la finalidad de que el sistema produzca resultados emergentes e impredecibles.

3. **Los datosy el azar algorítmico:** Anadol logra llevar estos sistemas a otra escala interactuando con multiples conjuntos de datos e incorporando inteligencia artificial. En sus obras, el uso de ruido algorítmico y variaciones fluidas permite que la información dura y estructurada adquiera formas líquidas y que se mantienen en constante mutación. 

Puedo concluir esta actividad diciendo que: el artista ya no crea la obra final, sino que el artista es quien crea el ecosistema que la produce. Y la aleatoriedad se convierte en el motor que da vida a cada ejecución de ese sistema, asegurando que aunque existan límites definidos, el resultado sea infinito.

---

## Actividad 02: Caminatas Aleatorias
> *Análisis del código Example 0.1: A Traditional Random Walk.*

* **Notas de análisis:**
  [Escribe aquí qué comprendiste sobre el funcionamiento básico del Random Walk tradicional.]




Al estudiar el código base del *Random Walk* tradicional, he podido identificar los siguientes conceptos clave sobre su funcionamiento y estructura:

1. **Estructura Orientada a Objetos (Clase Walker):** El código encapsula la lógica en una entidad o "agente". Este agente tiene un *estado* (su posición en el canvas con las variables `x` y `y`) y un *comportamiento* (las funciones para mostrarse `display()` y moverse `step()`). Esto hace que el código sea modular y escalable si quisiéramos agregar múltiples caminantes.
2. **Aleatoriedad Uniforme y Decisiones Discretas:** En la función `step()`, el caminante toma una decisión en cada fotograma sobre hacia dónde moverse (arriba, abajo, izquierda o derecha). Esto se logra generando un número aleatorio entero. Como la función de números aleatorios básica devuelve valores con una **distribución uniforme**, todas las direcciones tienen exactamente la misma probabilidad de ser elegidas (25% cada una, o un porcentaje igual si se incluyen las diagonales).
3. **El Comportamiento Emergente (Movimiento errático):** Visualmente, el resultado es una línea que traza un camino errático y tembloroso que recuerda al polvo flotando en el aire o al movimiento browniano. Una observación importante es que, como no hay ninguna tendencia o sesgo (todas las opciones son igual de probables), el caminante tiende a quedarse merodeando cerca de su punto de origen o de su posición actual durante mucho tiempo, sin lograr "viajar" grandes distancias de manera eficiente.

**Conclusión:** Este ejemplo demuestra cómo reglas de decisión muy simples y estrictamente probabilísticas, ejecutadas repetidamente en un bucle, generan un patrón visual impredecible que simula fenómenos básicos de la naturaleza.
---

## Actividad 03: Distribuciones de Probabilidad

### 1. Diferencia conceptual
* **Distribución Uniforme:** [Escribe tu definición en tus propias palabras].
* **Distribución No Uniforme:** [Escribe tu definición en tus propias palabras].

### 2. Implementación: Tendencia a la derecha
* **Enlace al sketch en p5.js:** [Inserta el link a tu código aquí]
* **Comentarios:** [Breve descripción de cómo modificaste el código para favorecer la derecha].

---

## Actividad 04: Distribución Normal
* **Enlace al sketch en p5.js:** [Inserta el link a tu código aquí]
* **Descripción de la visualización:**
  [Explica brevemente cómo visualizaste la campana de Gauss de una manera diferente a la del ejemplo base].

---

## Actividad 05: Distribución Personalizada (Lévy Flight)
* **Enlace al sketch en p5.js:** [Inserta el link a tu código aquí]
* **Resultados esperados:** [¿Qué esperabas ver en el canvas antes de programarlo?]
* **Justificación:** [Explica por qué usaste esta técnica y qué comportamiento visual lograste al combinar pasos cortos con saltos largos].

---

## Actividad 06: Ruido Perlin
* **Enlace al sketch en p5.js:** [Inserta el link a tu código aquí]
* **Resultados esperados:** [¿Qué esperabas ver con la transición suave del ruido Perlin?]
* **Justificación de la visualización:** [Explica por qué decidiste visualizar el ruido de esta manera en particular y no como un simple gráfico 1D].

---

##  Actividad 07: Reto de diseño - Navegar la incertidumbre
> *Diseño de una experiencia generativa en tiempo real (Formato 9:16) para un festival de ciencia.*

### 1. Enlace al Prototipo Final
* 🔗 **[Link a mi experiencia generativa en p5.js]**

### 2. Intención Conceptual
> *¿Cómo tradujiste cada concepto a reglas visuales y de comportamiento?*
* **Posibilidad:** [Explica cómo lograste que todas las direcciones parezcan posibles].
* **Tendencia:** [Explica cómo se construye visualmente una dirección a partir de pequeñas preferencias].
* **Normalidad:** [Explica cómo lograste que la mayoría de recorridos permanezcan cerca de lo habitual].
* **Excepción:** [Explica qué evento improbable programaste para descubrir un territorio nuevo].
* **Influencia (Interacción):** [Explica cómo la presencia/interacción del visitante modifica las reglas/probabilidades sin controlar el sistema].

### 3. Proceso de Desarrollo
* **Conceptos técnicos integrados:** [Menciona los 3 o más que usaste: Random Walk, Ruido Perlin, Normal, Lévy, etc.]
* **Experimentos y versiones intermedias:** 
  * [Sube capturas de pantalla de versiones previas aquí o describe los intentos fallidos].
* **Decisiones tomadas y alternativas descartadas:**
  * [Escribe por qué elegiste un camino visual o matemático y por qué descartaste otro].
* **Dificultades y soluciones:**
  * [Menciona los bugs o problemas lógicos que enfrentaste y cómo los resolviste].

### 4. Uso de IA Generativa
* **Prompt/Uso:** [Ej: Le pedí a ChatGPT que me explicara cómo mapear el ruido Perlin a un sistema de partículas].
* **Cambios realizados:** [Explica qué ajustaste del código que te dio la IA para adaptarlo a tu propio estilo y necesidades].

### 5. Tabla de Autoevaluación
> *Completa marcando con una "X" la casilla correspondiente y escribiendo la evidencia.*

| Criterio | Cumplo | No cumplo | Evidencia |
| :--- | :---: | :---: | :--- |
| **Encargo completo:** interpreto los cinco momentos dentro de un mismo sistema visual. | [ ] | [ ] | [Explica en qué parte del código o canvas se ven los 5 momentos integrados] |
| **Simulación con intención:** utilizo al menos tres conceptos de la unidad para comunicar las ideas del encargo. | [ ] | [ ] | [Menciona las 3 técnicas usadas y cómo aportan a la idea] |
| **Interacción significativa:** la interacción modifica el comportamiento o las probabilidades del sistema, que también funciona sin intervención. | [ ] | [ ] | [Describe qué tecla o acción del mouse altera la probabilidad y qué pasa cuando no se hace nada] |
| **Prototipo funcional:** la experiencia puede ejecutarse y recorrerse completa sin errores que impidan comprenderla. | [ ] | [ ] | [Confirma que el enlace funciona a pantalla completa en 9:16] |
| **Proceso documentado:** la bitácora evidencia avances, decisiones, dificultades, soluciones, uso de IA y enlace al prototipo. | [ ] | [ ] | [Todo este documento de GitHub sirve de evidencia] |

---

## Actividad 08: Evaluación
> *Espacio reservado para las notas de la presentación pública de la experiencia interactiva (Reto de Diseño).*
* **Feedback recibido:** [Espacio para anotar la retroalimentación del profesor y compañeros tras tu exposición].


