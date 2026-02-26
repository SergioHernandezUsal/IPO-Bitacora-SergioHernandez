Sesión 2 — Anatomía de la Interacción y Análisis Forense

Fecha: 26/02/2026

En esta sesión analizamos la evolución de la interacción persona-ordenador y profundizamos en los principios fundamentales del diseño desde una perspectiva forense. Entendimos que muchos de los avances actuales tienen su origen en decisiones clave tomadas en Xerox PARC, donde la metáfora del escritorio permitió que los usuarios entendieran el sistema digital a través de objetos familiares como documentos y carpetas. No fue una decisión estética, sino una estrategia cognitiva para reducir la curva de aprendizaje.

A partir de ahí trabajamos el modelo de usabilidad de Alan Dix, estructurado en tres pilares: facilidad de aprendizaje, flexibilidad y solidez. La facilidad de aprendizaje depende de que la interfaz sea predecible, consistente y familiar. La flexibilidad se centra en quién tiene el control de la interacción y en permitir múltiples formas equivalentes de realizar una acción. La solidez se refiere a la capacidad del sistema para apoyar al usuario cuando comete errores, ofreciendo recuperación y feedback claro.

También analizamos los Golfos de Norman, que representan la distancia entre lo que el usuario quiere hacer y lo que el sistema permite o comunica. Cuando la interfaz no muestra claramente qué acción es posible o no explica bien el resultado de una acción, ese “abismo” se ensancha.


Field Report — Análisis Forense (Actividad)
<img width="766" height="508" alt="image" src="https://github.com/user-attachments/assets/109da009-cc01-4ed5-b0f3-5c07c6f95a4b" />

Sospechoso seleccionado: Spotify

Para la actividad propuesta analizamos la aplicación Spotify desde los pilares de Dix.
En cuanto a la facilidad de aprendizaje, algunas funciones importantes están ocultas tras menús secundarios (como la gestión de la cola o ciertas opciones avanzadas), lo que puede dificultar la predictibilidad para usuarios nuevos.
Respecto a la flexibilidad, Spotify permite interacción mediante clic (WIMP) y también mediante gestos o comandos de voz (NUI). Sin embargo, el algoritmo de recomendaciones reduce en ocasiones la sensación de control del usuario.
En relación con la solidez, la aplicación permite retroceder canciones y modificar listas, pero algunas acciones como eliminar playlists no son completamente visibles ni fácilmente recuperables desde la interfaz principal.

Comparativa WIMP vs NUI
La modalidad WIMP ofrece mayor claridad y recuperabilidad, ya que las opciones son visibles y el usuario puede corregir acciones manualmente.
La modalidad NUI es más rápida y natural, pero puede generar mayor incertidumbre cuando el sistema interpreta una acción de forma inesperada.

Golfos de Norman
Los Golfos se ensanchan cuando el usuario no entiende por qué se reproduce una canción distinta a la esperada o cuando no encuentra fácilmente una función. La falta de visibilidad en algunas acciones aumenta el Golfo de Evaluación.

La modalidad WIMP (clic y menú) ofrece mayor recuperabilidad.
Esto se debe a que Las opciones están visibles, se puede volver atrás manualmente, existe mayor control explícito sobre listas y reproducción, el historial es accesible.
En cambio, en modalidad NUI (gesto o voz), si el sistema interpreta mal una orden, puede ser menos evidente cómo corregirla rápidamente.


Acción Requerida — Decisión de diseño y Sintetizabilidad

En Rocket League, la repetición automática de los goles mejora la sintetizabilidad del sistema.
Después de cada gol, el juego muestra la jugada desde distintos ángulos, lo que permite entender claramente qué ha pasado y cómo se llegó al resultado. Esto ayuda a reconstruir la acción y relacionar las decisiones tomadas con el desenlace.
Gracias a esta función, el jugador comprende mejor el estado del partido y puede aprender de sus errores o aciertos.
