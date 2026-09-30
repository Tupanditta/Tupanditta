# 🐼 Tupanditta | Estudiante de Ingeniería Informática

Estudiante de Ingeniería Informática enfocado en el desarrollo de software estructurado, algoritmia y modelado de sistemas. Me interesa entender qué ocurre bajo las abstracciones del software: desde la gestión de memoria y el control de procesos en sistemas UNIX, hasta la simulación probabilística y la automatización práctica en Python.

Busco escribir código que no solo resuelva el problema, sino que mantenga una arquitectura limpia, modular y eficiente.

---

## 🧭 Áreas de Interés y Especialización

* ⚙️ **Sistemas y bajo nivel:** Comprensión del sistema operativo, ciclo de vida de procesos en entornos POSIX, gestión manual de memoria y llamadas al sistema.
* 🧩 **Algoritmia y estructuras de datos:** Implementación de estructuras dinámicas (TADs) desde cero, resolución mediante recursividad y optimización de búsquedas combinatorias mediante heurísticas.
* 🎲 **Modelado y simulación:** Representación de problemas reales mediante distribuciones estadísticas, matrices de probabilidad y cadenas de Markov.
* 🗄️ **Bases de datos y persistencia:** Modelado relacional, consultas analíticas avanzadas y manejo de datos estructurados con JSON y SQLite.

---

## 🛠️ Habilidades Técnicas

### 💻 Lenguajes y herramientas
* **C:** Lenguaje principal para sistemas y algoritmia. Manejo directo de punteros, control manual de memoria (`malloc`, `free`), organización modular (`.c` y `.h`) y compilación con `Makefiles`.
* **Python:** Desarrollo de simuladores, resolución algorítmica, procesamiento de archivos de texto y automatización de tareas.
* **SQL (Oracle SQL / SQLite):** Diseño relacional con restricciones de integridad, uniones de tablas y consultas de agregación (`GROUP BY`, `HAVING`).
* **Entorno de trabajo:** Linux/UNIX, API POSIX, GCC y trabajo continuo en terminal.

### 🧠 Conceptos y metodologías
* **Sistemas operativos:** Ciclo de vida de procesos (`fork`, `exec`, `waitpid`, control de procesos huérfanos y zombis) y manejo de descriptores de ficheros frente a streams estándar.
* **Diseño algorítmico:** Búsqueda exhaustiva mediante Backtracking, optimización de restricciones con la heurística MRV (Minimum Remaining Values) y análisis de complejidad temporal.
* **Matemática computacional:** Cadenas de Markov, distribuciones de Poisson y Gauss, cálculo de probabilidad conjunta y muestreo aleatorio.
* **Arquitectura de software:** Separación clara de responsabilidades (entrada de datos, lógica de dominio, persistencia e interfaz) y refactorización orientada a evitar código duplicado.

---

## 🚀 Proyectos Destacados

### 🚗 Traffic Accident Simulator
* **Área:** Simulación estocástica y persistencia de datos (Python, SQLite, Pandas).
* **Descripción:** Sistema modular que proyecta la accidentalidad diaria a partir de variables demográficas, estacionales, meteorológicas y factores de riesgo concurrentes.
* **Aspectos técnicos:** Implementación de cadenas de Markov para modelar transiciones climáticas, muestreo aleatorio con distribución de Poisson y cálculo de valor esperado ponderado sobre matrices de riesgo. La arquitectura desacopla por completo la carga de contexto, la simulación física y la exportación final a SQLite/JSON.

### 🧩 Sudoku Solver & Validator
* **Área:** Algoritmos de búsqueda y optimización (Python).
* **Descripción:** Herramienta compuesta por un validador interactivo de movimientos (`SudokuPlay`) y un motor de resolución automática (`SudokuRecursive`).
* **Aspectos técnicos:** Implementación de backtracking recursivo optimizado con la heurística **MRV (Minimum Remaining Values)**. Al seleccionar dinámicamente la casilla con menor número de opciones disponibles, se reduce la explosión combinatoria del árbol de búsqueda de miles de ramas a unas pocas decenas de iteraciones.

### 📂 File Organizer
* **Área:** Herramientas CLI y gestión de archivos (Python).
* **Descripción:** Aplicación para escanear estructuras de directorios, volcar la jerarquía a un archivo de texto editable y reconstruir la organización de carpetas en disco.
* **Aspectos técnicos:** Parsing de estructuras basado en niveles de indentación, preservación de metadatos mediante `shutil.copy2` y resolución automática de colisiones de nombres mediante sufijos de desambiguación.

---

## 📚 Base Académica y Repositorios

* ⚙️ **Algoritmia (C):** Implementación paso a paso de tipos abstractos de datos dinámicos (pilas, colas, bicolas, listas enlazadas) y recorridos recursivos en árboles binarios de búsqueda (BST).
* 🐧 **Sistemas Operativos (C / POSIX):** Prácticas de programación concurrente, sincronización entre procesos padre e hijo, manejo de señales y operaciones de E/S de bajo nivel.
* 🏗️ **Estructuras de Datos (C):** Construcción modular de proyectos con `Makefiles`, aplicando TADs a simulaciones de colas de tráfico y evaluadores de expresiones matemáticas con gestión estricta de memoria.
* 🗄️ **Bases de Datos I (SQL):** Modelado entidad-relación, integridad referencial y resolución de consultas analíticas sobre entornos Oracle.
* 🕹️ **Juegos de Lógica y Tablero (Python):** Colección de 6 motores por consola (*2048*, *Conecta 4*, *Buscaminas*, *BlockBlast*, *Wordle*), enfocados en transformaciones de matrices, vectores de desplazamiento `(df, dc)` y optimización de reglas.
