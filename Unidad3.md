# ARBOLES Y GRAFOS 

Este repositorio reúne de manera organizada, clara y estructurada los conceptos teóricos fundamentales, comparaciones críticas

---

## 1. ¿Qué es un Grafo? (La Estructura General)

Un **grafo** G es una estructura matemática y computacional compuesta por un conjunto de elementos llamados **vértices** (o nodos) y conexiones que los unen, denominadas **aristas** (o arcos). 

Se define formalmente como:
G = (V, E)

Donde:
*   V es el conjunto de vértices ($V \neq \emptyset$).
*   E es el conjunto de aristas ($E \subseteq \{\{u, v\} \mid u, v \in V, u \neq v\}$ en el caso no dirigido).

### Clasificaciones Clave:
*   **Dirigidos (Digrafos):** Las aristas tienen un sentido específico (flechas). Si hay una arista del nodo $u$ al nodo $v$, se representa con el par ordenado $(u, v)$ y la relación de dirección es asimétrica.
*   **No Dirigidos:** Las aristas representan relaciones simétricas bidireccionales. Se expresan como el conjunto no ordenado $\{u, v\}$.
*   **Ponderados (o valorados):** Cada arista tiene asociado un valor numérico (peso, distancia, costo de viaje, etc.).
*   **Cíclicos vs. Acíclicos:** Un grafo es cíclico si contiene al menos un ciclo (un camino que empieza y termina en el mismo nodo sin repetir aristas).

---

## 2. ¿Qué es un Árbol? (El Caso Especial)

Un **árbol** es una variación restringida de un grafo. Formalmente, un árbol es un grafo no dirigido que cumple de manera simultánea con dos condiciones estrictas:
1.  **Es Conexo:** Hay un camino para conectar cualquier par de vértices.
2.  **Es Acíclico:** No tiene ningún ciclo.

### Propiedades Fundamentales:
*   **Aristas:** Si un árbol posee un total de $N$ nodos, siempre tendrá exactamente $N - 1$ aristas.
*   **Caminos Únicos:** Existe exactamente un único camino simple entre cualquier par de nodos de un árbol.
*   **Estructura Jerárquica:** Cuando a un árbol se le designa un nodo inicial especial llamado **Raíz**, se comporta como una estructura jerárquica con relaciones definidas de **Padre-Hijo**, nodos internos y nodos finales (**Hojas**).

---

## 3. Tabla Comparativa Directa: Árbol vs. Grafo

| Característica | Árbol (Tree) | Grafo (Graph) |
| :--- | :--- | :--- |
| **Jerarquía** | Estructura estrictamente jerárquica (padre-hijo). | Red no jerárquica de relaciones arbitrarias. |
| **Caminos Únicos** | Existe **un único camino** entre cualquier par de nodos. | Pueden existir múltiples caminos o ninguno. |
| **Ciclos** | **Nunca** tiene ciclos (Estrictamente acíclico). | Puede ser cíclico o acíclico (ej. DAG). |
| **Nodo Raíz** | Tiene un único nodo raíz definido. | No existe el concepto de nodo raíz. |
| **Fórmula de Aristas** | Si posee $N$ nodos, siempre tiene $N - 1$ aristas. | El número de aristas es independiente de sus nodos. |
| **Recorrido** | Pre-orden, In-orden, Post-orden. | Búsqueda en Anchura (BFS) y en Profundidad (DFS). |

---
