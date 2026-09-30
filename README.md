# 👨‍💻 Ander Lifeng Sola | Estudiante de Ingeniería Informática

Estudiante de Ingeniería Informática enfocado en el desarrollo de software estructurado, algoritmia y modelado de sistemas. Me interesa entender qué ocurre bajo las abstracciones: desde la gestión de memoria y el control de procesos en sistemas UNIX, hasta la simulación probabilística y la automatización en Python.

---

## 🧭 Áreas de Estudio e Interés

* ⚙️ **Sistemas y bajo nivel:** Comprensión del sistema operativo, gestión de procesos en entornos POSIX, control manual de memoria y llamadas al sistema.
* 🧩 **Algoritmia y estructuras de datos:** Implementación de estructuras dinámicas (TADs) desde cero, resolución mediante recursividad y optimización de búsquedas combinatorias con heurísticas.
* 🎲 **Modelado y simulación:** Representación de problemas reales mediante distribuciones estadísticas, matrices de probabilidad y cadenas de Markov.
* 🗄️ **Bases de datos y persistencia:** Modelado relacional, consultas analíticas avanzadas y extracción de datos mediante formatos estructurados como JSON y SQLite.

---

## 🛠️ Habilidades Técnicas

### 💻 Lenguajes y herramientas
* **C:** Lenguaje central para sistemas y algoritmia. Control directo de punteros, gestión dinámica de memoria (`malloc`, `free`), organización modular (`.c` y `.h`) y compilación con `Makefiles`.
* **Python:** Desarrollo de simuladores, resolución algorítmica, procesamiento de archivos de texto y automatización de tareas.
* **SQL (Oracle SQL / SQLite):** Definición de restricciones de integridad, diseño relacional, uniones de tablas y consultas de agregación (`GROUP BY`, `HAVING`).
* **Entorno de desarrollo:** Linux/UNIX, API POSIX, GCC, terminal y control de versiones con Git.

### 🧠 Conceptos de ingeniería y metodologías
* **Sistemas operativos:** Ciclo de vida de procesos (`fork`, `exec`, `waitpid`, gestión de huérfanos y zombis) y manejo de descriptores de ficheros frente a streams estándar.
* **Diseño algorítmico:** Búsqueda exhaustiva mediante Backtracking, optimización de restricciones con la heurística MRV (Minimum Remaining Values) y análisis de complejidad temporal.
* **Matemática computacional:** Cadenas de Markov, distribuciones de Poisson y Gauss, cálculo de probabilidad conjunta y muestreo aleatorio.
* **Arquitectura de software:** Separación estricta de responsabilidades (entrada de datos, lógica de dominio, persistencia e interfaz) y refactorización orientada a eliminar código duplicado.

---

## 🚀 Proyectos Destacados

### 🚗 Traffic Accident Simulator
* **Área:** Simulación estocástica y persistencia de datos (Python, SQLite, Pandas).
* **Descripción:** Sistema modular que proyecta la accidentalidad diaria a partir de variables demográficas, estacionales, meteorológicas y factores de riesgo concurrentes.
* **Detalles técnicos:** Implementación de cadenas de Markov para simular transiciones climáticas, muestreo aleatorio con distribución de Poisson y cálculo de valor esperado ponderado sobre matrices de riesgo. La arquitectura separa completamente la carga de contexto, la simulación física y la exportación de resultados.

### 🧩 Sudoku Solver & Validator
* **Área:** Algoritmos de búsqueda y optimización (Python).
* **Descripción:** Proyecto compuesto por un validador interactivo de movimientos (`SudokuPlay`) y un motor de resolución automática (`SudokuRecursive`).
* **Detalles técnicos:** Implementación de backtracking recursivo y posterior optimización con la heurística MRV (Minimum Remaining Values), seleccionando en cada paso la casilla con menor número de alternativas y reduciendo drásticamente las ramas del árbol de búsqueda.

### 📂 File Organizer
* **Área:** Herramientas CLI y gestión de archivos (Python).
* **Descripción:** Aplicación para escanear estructuras de carpetas, generar representaciones en texto plano para edición manual y reconstruir árboles de directorios.
* **Detalles técnicos:** Parsing de jerarquías por indentación, preservación de metadatos de archivos con `shutil.copy2` y resolución de duplicados mediante sufijos de desambiguación.

---

## 📚 Repositorios Académicos (Base Formativa)

* ⚙️ **Algoritmia (C):** Implementación de tipos abstractos de datos dinámicos (pilas, colas, bicolas, listas enlazadas) y recorridos recursivos en árboles binarios de búsqueda.
* 🐧 **Sistemas Operativos (C / POSIX):** Prácticas de programación concurrente, sincronización padre-hijo, gestión de señales y operaciones de entrada/salida de bajo nivel.
* 🏗️ **Estructuras de Datos (C):** Programas modulares automatizados con Makefiles, aplicando estructuras de datos a evaluadores de expresiones matemáticas y simulaciones de peajes.
* 🗄️ **Bases de Datos I (SQL):** Consultas avanzadas, álgebra relacional y diseño de esquemas en entornos Oracle.
* 🕹️ **Juegos de Lógica y Tablero (Python):** Batería de motores por consola (*2048*, *Conecta 4*, *Buscaminas*, *BlockBlast*, *Wordle*), centrados en transformaciones matriciales, vectores de dirección y normalización de movimientos.

---

## 🎯 Próximos Retos de Aprendizaje

* 🧪 **Pruebas automatizadas:** Incorporar tests unitarios sistemáticos (`pytest`, suites de prueba en C) para garantizar reproducibilidad algorítmica.
* 🧵 **Concurrencia avanzada:** Profundizar en hilos nativos (POSIX Threads), exclusión mutua mediante semáforos/mutexes y prevención de condiciones de carrera.
* ⚡ **Transición hacia C++:** Evolucionar la base estructurada de C hacia el paradigma orientado a objetos, gestión de recursos RAII y uso de la biblioteca estándar (STL).
