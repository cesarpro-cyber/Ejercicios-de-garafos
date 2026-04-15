# Proyecto: Recorridos BFS y DFS en Grafos

## 📌 Descripción
Este proyecto implementa dos representaciones de grafos en **Java**:
1. **Listas de adyacencia** (`GrafoLista`)
2. **Matriz de adyacencia** (`GrafoMatriz`)

Ambas estructuras permiten realizar recorridos clásicos:
- **BFS (Búsqueda en Anchura)** usando una cola (`Queue`).
- **DFS (Búsqueda en Profundidad)** usando recursividad o pila (`Stack`).

El programa principal (`Main`) instancia ambos grafos, agrega las aristas y ejecuta los recorridos.

---

## 📂 Estructura del proyecto
/src
├── GrafoLista.java
├── GrafoMatriz.java
└── Main.java
---

## ⚙️ Requisitos técnicos
- Java 8 o superior.
- Compilador `javac` y máquina virtual `java`.

---

## ▶️ Ejecución

1. Compilar todas las clases:
   ```bash
   javac GrafoLista.java GrafoMatriz.java Main.java
   java Main

   BFS (Lista): A B C D E F
DFS (Lista): A B D F C E

BFS (Matriz): A B C D E F G
DFS (Matriz): A B D F C E G
