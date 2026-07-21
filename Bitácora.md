# Bitácora Unidad 1: Aleatoriedad 🎲
**Estudiante:** [Tu Nombre]
**Curso:** Simulación Computacional

---

## 📌 Actividad 01: La aleatoriedad en el arte generativo
> *Reflexiones sobre los videos de Casey Reas, Refik Anadol, Tyler Hobbs y los ensayos propuestos.*

* **Reflexión principal:**
  [Escribe aquí tus ideas sobre cómo la aleatoriedad deja de ser caos y se convierte en una herramienta compositiva según lo visto en los recursos.]

---

## 📌 Actividad 02: Caminatas Aleatorias
> *Análisis del código Example 0.1: A Traditional Random Walk.*

* **Notas de análisis:**
  [Escribe aquí qué comprendiste sobre el funcionamiento básico del Random Walk tradicional.]

---

## 📌 Actividad 03: Distribuciones de Probabilidad

### 1. Diferencia conceptual
* **Distribución Uniforme:** [Escribe tu definición en tus propias palabras].
* **Distribución No Uniforme:** [Escribe tu definición en tus propias palabras].

### 2. Implementación: Tendencia a la derecha
* **Enlace al sketch en p5.js:** [Inserta el link a tu código aquí]
* **Comentarios:** [Breve descripción de cómo modificaste el código para favorecer la derecha].

---

## 📌 Actividad 04: Distribución Normal
* **Enlace al sketch en p5.js:** [Inserta el link a tu código aquí]
* **Descripción de la visualización:**
  [Explica brevemente cómo visualizaste la campana de Gauss de una manera diferente a la del ejemplo base].

---

## 📌 Actividad 05: Distribución Personalizada (Lévy Flight)
* **Enlace al sketch en p5.js:** [Inserta el link a tu código aquí]
* **Resultados esperados:** [¿Qué esperabas ver en el canvas antes de programarlo?]
* **Justificación:** [Explica por qué usaste esta técnica y qué comportamiento visual lograste al combinar pasos cortos con saltos largos].

---

## 📌 Actividad 06: Ruido Perlin
* **Enlace al sketch en p5.js:** [Inserta el link a tu código aquí]
* **Resultados esperados:** [¿Qué esperabas ver con la transición suave del ruido Perlin?]
* **Justificación de la visualización:** [Explica por qué decidiste visualizar el ruido de esta manera en particular y no como un simple gráfico 1D].

---

## 🏆 Actividad 07: Reto de diseño - Navegar la incertidumbre
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

## 📌 Actividad 08: Evaluación
> *Espacio reservado para las notas de la presentación pública de la experiencia interactiva (Reto de Diseño).*
* **Feedback recibido:** [Espacio para anotar la retroalimentación del profesor y compañeros tras tu exposición].


# Bitácora de Simulación - Unidad 1: Aleatoriedad
**Desarrollado por:** [Tu Nombre / Usuario]

Esta es la documentación de mi proceso durante la primera unidad del curso de Simulación, donde exploramos cómo la aleatoriedad puede dejar de ser simplemente "ruido" para convertirse en una herramienta de diseño.

---

## Actividad 1 y 2: Referentes y la base de todo
Después de revisar el trabajo de gente como Casey Reas y Tyler Hobbs, me quedó dando vueltas la idea de que [escribe aquí algo que te llamó la atención, ej: la aleatoriedad controlada es lo que le da esa textura "orgánica" o natural a las obras, alejándolas de lo puramente matemático].

Sobre el **Random Walk tradicional** del Example 0.1, lo que entendí al analizar el código es que básicamente [explica en una línea cómo funciona, ej: el objeto decide en cada frame moverse un pixel en una de cuatro direcciones posibles, todo con la misma probabilidad].

---

## Actividad 3: Jugando con las probabilidades
Para mí, la diferencia clave entre una distribución uniforme y una no uniforme es que [explica con tus propias palabras, ej: en la uniforme todo tiene el mismo chance de salir, como un dado perfecto; en la no uniforme el dado está "cargado" hacia un resultado].

*   **Link a mi sketch (Tendencia a la derecha):** [Pega aquí el enlace de p5.js]
*   **Nota de desarrollo:** Para lograr este sesgo hacia la derecha en el código, modifiqué las probabilidades de la siguiente manera: [cuenta brevemente qué le cambiaste al if/else o al random].

---

## Actividad 4: Distribución Normal
*   **Link a mi sketch:** [Pega aquí el enlace de p5.js]

No quería hacer la típica visualización de la campana de Gauss o los círculos amontonados en el centro. En su lugar, decidí representarlo usando [describe qué elementos visuales usaste: ej. líneas de opacidad variable, tamaño de geometrías, etc.]. El resultado hace que lo normal (el centro) se vea [describe cómo se ve] y los extremos (las colas) casi desaparezcan.

---

## Actividad 5 y 6: Lévy Flight y el Ruido Perlin
*   **Sketch Lévy Flight:** [Enlace]
*   **Sketch Ruido Perlin:** [Enlace]

**Sobre Lévy Flight:** Lo integré a mi sketch de [menciona el sketch base]. Quería ver cómo los saltos largos rompían la monotonía. El efecto final me gustó porque [explica por qué te gusta visualmente, ej: se ve como si el agente estuviera buscando comida y de repente cambiara de zona].

**Sobre el Ruido Perlin:** El `random()` puro es demasiado caótico, así que usé Perlin noise para generar un movimiento mucho más suave. Decidí visualizarlo mediante [explica tu idea, ej: curvas que parecen un mapa topográfico]. Elegí este camino porque quería probar cómo los valores consecutivos afectaban el color y no solo la posición.

---

## 🚀 Actividad 7: Reto Final - "Navegar la incertidumbre"
*   **Link al proyecto final (9:16):** [Pega aquí tu enlace]

### Traducción de los conceptos al código
Para este festival, el objetivo era traducir cinco momentos abstractos en reglas de comportamiento visual. Así fue como lo abordé:

1.  **Posibilidad:** Lo representé haciendo que al inicio [explica qué pasa en pantalla, ej: las partículas se esparzan en 360 grados].
2.  **Tendencia:** Usé [nombra la técnica, ej: una distribución no uniforme] para que, poco a poco, el sistema se empiece a inclinar hacia [dirección o comportamiento].
3.  **Normalidad:** La mayor parte del tiempo, los elementos se mantienen [explica el estado de calma o repetición], logrando esto mediante la distribución normal.
4.  **Excepción:** Programé un evento de muy baja probabilidad (usando la lógica del Lévy Flight) que provoca que [cuenta qué locura pasa de repente en la pantalla].
5.  **Influencia:** Cuando el usuario interactúa (por ejemplo, al mover el mouse), las reglas cambian: [explica cómo alteras las probabilidades sin controlar directamente a dónde va todo].

### Proceso de desarrollo (El detrás de cámaras)
Para armar esto, combiné principalmente 3 cosas: [Nombra los 3 conceptos que elegiste, ej: Random Walk, Ruido Perlin y Distribución Normal].

*   **Problemas técnicos:** Me trabé bastante intentando que [cuenta un bug, ej: el ruido Perlin no se saliera de la pantalla]. Lo terminé resolviendo [cuenta cómo lo arreglaste].
*   **Decisiones de diseño:** Inicialmente iba a usar [algo que descartaste], pero me di cuenta de que ensuciaba mucho la pantalla, así que opté por algo más minimalista.
*   *(Opcional: Deja aquí un par de capturas de pantalla de versiones previas que se veían mal o raras para mostrar el progreso).*

### Uso de herramientas de IA
Durante el desarrollo, usé [ChatGPT / Claude / Copilot] específicamente para preguntarle cómo [ej: optimizar el arreglo de partículas para que el sketch no se pusiera lento]. El código que me sugirió lo tuve que adaptar, modificando [menciona qué le cambiaste para que encajara con tu estilo].

---

### Autoevaluación (Para la sesión presencial - Actividad 08)
Dejo aquí mi tabla de valoración para discutirla en clase:

| Criterio a evaluar | Estado | Mi argumento / Evidencia |
| :--- | :--- | :--- |
| **Encargo completo** (Están los 5 momentos en 1 sistema) | Cumplo / No Cumplo | [Escribe en qué parte de la pantalla o código ocurre] |
| **Simulación con intención** (Uso al menos 3 conceptos) | Cumplo / No Cumplo | [Menciona los 3 conceptos integrados] |
| **Interacción significativa** (Modifico probabilidades, no solo colores. Funciona solo) | Cumplo / No Cumplo | [Explica cómo se ve afectado el sistema con la interacción] |
| **Prototipo funcional** (Sin errores en formato 9:16) | Cumplo / No Cumplo | [El proyecto corre fluido en el link compartido] |
| **Proceso documentado** | Cumplo / No Cumplo | [Esta bitácora es mi evidencia] |
