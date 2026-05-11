</div>

## Unidad 1

### 1.  Definición de Proposición
        
Una proposición es una oración o enunciado que tiene la propiedad de ser verdadero (V) o falso (F), pero nunca ambos a la vez.

Es proposición: "El número 4 es par" (V), "Quito es la capital de Francia" (F).

No es proposición: Las preguntas, órdenes o exclamaciones ("¡Hola!", "¿Cómo estás?", "Limpia tu cuarto"), ya que no se pueden calificar como verdaderas o falsas.

### 2. Tipos de ProposicionesSimples (Atómicas): 

No tienen conectores. Expresan una sola idea.

Ejemplo: 

p: "El cielo es azul".

Compuestas (Moleculares): Se forman uniendo dos o más proposiciones simples mediante conectores lógicos.

Ejemplo: "El cielo es azul y hoy es lunes".

### 3. Conectores Lógicos
Los conectores son los operadores que permiten combinar proposiciones simples.

| Conector | Nombre | Símbolo | Significado |
| :--- | :--- | :---: | :--- |
| **Negación** | No | $\neg$ | Invierte el valor de verdad. |
| **Conjunción** | Y | $\land$ | Verdadero solo si ambos son V. |
| **Disyunción** | O | $\lor$ | Verdadero si al menos uno es V. |
| **Condicional** | Implicación | $\to$ | Falso solo si el antecedente es V y el consecuente es F. |
| **Bicondicional** | Doble implicación | $\leftrightarrow$ | Verdadero si ambos tienen el mismo valor. |

---

### 4. Explicación de Tablas de Verdad
Las tablas de verdad permiten analizar todas las combinaciones posibles de valores para determinar la validez de una proposición compuesta.

**Fórmula de filas:** $2^n$ (donde $n$ es el número de proposiciones variables).

#### Resumen de resultados:
*   **Tautología:** El resultado final es siempre **Verdadero**.
*   **Contradicción:** El resultado final es siempre **Falso**.
*   **Contingencia:** El resultado final tiene valores **Verdaderos y Falsos**.

---

---

### 5. Principales Leyes Lógicas (Equivalencias)
Estas reglas permiten simplificar expresiones lógicas complejas:

<img width="522" height="418" alt="image" src="https://github.com/user-attachments/assets/99cad698-1fbd-4c7e-b46d-9db3eb5495a9" />

---

### 6. Reglas de Inferencia
Son esquemas lógicos que permiten obtener conclusiones válidas a partir de premisas dadas.

#### Modus Tollendo Tollens (MTT)
Si una implicación es cierta y su consecuente es falso, entonces el antecedente es necesariamente falso.


p → q

¬q

------
∴ ¬p

---
#### Silogismo Hipotético (SH)
Si una primera proposición implica una segunda, y la segunda implica una tercera, entonces la primera implica la tercera.


p → q

q → r

------
∴ p → r

---

#### Silogismo Disyuntivo (SD)
Si se tiene una disyunción de dos elementos y se niega uno de ellos, el otro debe ser verdadero.

p ∨ q

¬p

------
∴ q

---
# 🧠 Ejercicio Aplicado: El Dilema del Estudiante
# 4. 🔍 Reflexión personal
Responder:

- ¿Qué fue lo más difícil de entender?
  
Lo más complejo fue la simplificación de expresiones usando leyes lógicas. A diferencia de las tablas de verdad, que siguen un proceso mecánico, la simplificación requiere identificar qué ley aplicar en el momento exacto (como las Leyes de De Morgan o la Distributividad). A veces, el camino para llegar a la expresión más mínima no es evidente y requiere mucha práctica para reconocer los patrones.

- ¿Qué tema comprendí mejor?
  
  El tema que comprendí con mayor claridad fue el de compuertas lógicas. Me resultó muy intuitivo visualizar cómo los conectores lógicos ($\wedge, \vee, \neg$) se transforman en elementos físicos o circuitos que permiten o bloquean el paso de una señal. Relacionar la teoría de la verdad con el funcionamiento técnico de una compuerta (AND, OR, NOT) facilitó mucho mi aprendizaje.
  
- ¿Cómo puedo aplicar la lógica en mi carrera?
  
Como estudiante de Ingeniería en Ciencias de la Computación, la lógica es la base fundamental de todo lo que hago. La puedo aplicar en:

- Desarrollo de Software: Al escribir algoritmos y estructuras condicionales (if, else, while), donde una mala interpretación de una condición lógica puede generar errores en el programa.

- Optimización de Código: Utilizando las leyes lógicas para simplificar condiciones complejas, logrando que el código sea más limpio y eficiente.

- Arquitectura de Computadores: En el diseño de circuitos digitales y sistemas embebidos, donde las compuertas lógicas determinan el procesamiento de la información a nivel de hardware.

- Base de Datos: Al realizar consultas complejas (SQL), donde el uso correcto de los operadores lógicos es vital para filtrar la información de manera precisa.


