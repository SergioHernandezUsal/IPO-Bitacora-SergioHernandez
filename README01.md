# IPO-Bitacora-SergioHernandez S1

Sesión 1 — Análisis Forense de la Interfaz

Fecha: 19/02/2026

CONCEPTOS CLAVE:
En esta sesión trabajamos la idea central de que “la interfaz es el sistema”, es decir, para el usuario no existe el algoritmo ni la arquitectura interna, solo la interfaz visible .

También vimos:

  Impacto del mal diseño: puede afectar a la productividad, seguridad e incluso a procesos críticos.
  ROI de la usabilidad: invertir en diseño no es un gasto, sino una inversión.
  Visibilidad: si el usuario no puede ver el estado del sistema, no existe.
  Affordance (comprensión intuitiva): los objetos deben “decir” cómo se usan.
  Mapeo natural: relación lógica entre control y efecto.
  Concepto de hombre-máquina: la interacción como diálogo (ejemplo del volante como interfaz).

Además analizamos cómo las campañas de Apple (1984 y 2014) mostraban la tecnología como algo accesible, doméstico y humano, marcando el cambio de paradigma de sistemas centrados en la máquina a sistemas centrados en las personas.

CACERIA DE ERRORES:
EXPEDIENTE B — Sobrecarga en la Carretera
<img width="827" height="464" alt="image" src="https://github.com/user-attachments/assets/936e3ba0-9075-4074-9fcf-0055a72e3836" />


1- EL DIAGNÓSTICO

El diseño falla porque viola el principio de Seguridad y Atención Dividida. Un conductor a 120 km/h no puede procesar la alta densidad de texto, menús complejos, información secundaria irrelevante...
También hay problemas de legibilidad, tiempo de respuesta cognitivo, mapeo entre volante y pantalla

2- POSIBLE SOLUCIÓN
![WhatsApp Image 2026-02-26 at 11 16 02](https://github.com/user-attachments/assets/64efc7b0-2ac5-4454-a9e7-a5e8d62f92c9)

En este rediseño he aplicado principios de diseño centrado en el usuario pensando en un contexto de conducción a alta velocidad, donde la atención visual es limitada y la seguridad es prioritaria.
El problema del diseño original era la sobrecarga de información y la necesidad de dedicar demasiado tiempo a leer la pantalla. Esto viola el principio de seguridad y aumenta la atención dividida.

-Reducción de carga cognitiva:
He simplificado la interfaz mostrando únicamente tres emisoras visibles (FM1, FM2, FM3), con opciones grandes y claras.
Esto permite:
Lectura rápida en menos de un segundo.
Identificación inmediata de las opciones.
Menor esfuerzo cognitivo.
Además, se evita mostrar todos los menús simultáneamente. En su lugar, se indica mediante puntos inferiores que existen más páginas, reduciendo la saturación visual.

-Jerarquía visual clara
La pantalla está organizada de forma estructurada:
Título superior ("Radio") que contextualiza la tarea.
Opciones centrales grandes (zona de interacción principal).
Indicador inferior de navegación secundaria.

Esto facilita un recorrido visual predecible y evita movimientos oculares erráticos.

-Mapeo natural con el volante
El diseño está pensado para funcionar principalmente mediante los controles del volante.
El conductor puede cambiar de emisora con botones físicos sin necesidad de interactuar directamente con la pantalla.
Esto mejora:
El mapeo entre acción y resultado.
La seguridad.
La ergonomía.

-Minimalismo contextual
Solo se muestra información relevante para la tarea actual (radio).
No se incluyen:
Listas largas.
Texto innecesario.
Información secundaria no relacionada.

Este enfoque sigue el principio de que en conducción menos es más.


REFLEXIÓN PERSONAL:
Este ejercicio me ha hecho entender que el problema del diseño original no era estético, sino cognitivo.
No se trata de que la interfaz sea “bonita”, sino de que respete las limitaciones humanas en un contexto concreto.
