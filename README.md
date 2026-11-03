# 💻 Tarea: Programación Funcional en Haskell (Exercism)

**Institución:** Universidad Tecnológica Centroamericana (UNITEC)  
**Clase:** Lenguajes de Programación  
**Docente:** Ing. Jose Isaac Orellana Velasquez  
**Semestre/Periodo:** 2 / Q4 2026  
**Fecha límite de entrega:** Miércoles, 09 de Diciembre de 2026  

---

## 🎯 Propósito de la Asignación
Esta tarea tiene como objetivo principal poner en práctica los conceptos del paradigma funcional y entender la lógica de programación a un bajo nivel. Utilizaremos el lenguaje **Haskell** y la plataforma educativa **Exercism** para desarrollar soluciones guiadas por pruebas (TDD - Test Driven Development).

---

## ⚙️ Instrucciones de Configuración y Entrega

Para asegurar que tu código se evalúe correctamente, debes enlazar tu perfil de Exercism con este repositorio generado por Classroom 50. Sigue estos pasos al pie de la letra:

### Paso 1: Configurar Exercism y la CLI local
1. Crea una cuenta en [Exercism](https://exercism.org/) y únete al track de **Haskell**.
2. Instala la interfaz de línea de comandos (CLI) de Exercism en tu computadora y configúrala con tu token personal.
3. Asegúrate de tener instalado el compilador de Haskell (GHC).

### Paso 2: Configurar GitHub Syncer (Obligatorio)
1. En Exercism, navega a **Settings > Integrations > GitHub Syncer**.
2. Autoriza el acceso a tu cuenta de GitHub.
3. Selecciona **este repositorio** (el que Classroom 50 acaba de crear para ti) como el destino de sincronización.
4. ⚠️ **MUY IMPORTANTE:** Configura el sincronizador para que guarde los cambios mediante **Commits directos** a la rama principal (`main` o `master`), **NO** mediante Pull Requests.

### Paso 3: Flujo de Trabajo
Por cada ejercicio de la rúbrica, deberás:
1. Descargarlo mediante la terminal: `exercism download --exercise=[nombre] --track=haskell`
2. Escribir tu solución en el archivo `.hs` correspondiente.
3. Validar localmente que pase las pruebas unitarias.
4. Enviarlo a la plataforma: `exercism submit src/[Archivo].hs`. Al ser aprobado, Exercism subirá automáticamente el código a este repositorio.

---

## 📋 Rúbrica y Ejercicios Requeridos (Total: 629 Puntos)

Debes completar los siguientes **22 ejercicios**. No se validarán entregas parciales de un ejercicio.

### 1. Introduction (225 Puntos)
| Ejercicio | Concepto a Evaluar | Puntos |
| :--- | :--- | :--- |
| `hello-world` | Configuración de entorno local. | 28 |
| `leap` | Operadores lógicos y condicionales. | 28 |
| `space-age` | Tipos de datos algebraicos y *pattern matching*. | 28 |
| `pangram` | Funciones de alto orden básicas. | 28 |
| `bob` | Manejo de cadenas y guardas lógicas. | 28 |
| `darts` | Operaciones matemáticas y condicionales. | 28 |
| `yacht` | Lógica mediante *pattern matching* exhaustivo. | 28 |
| `nucleotide-count`| Mapeo y conteo de elementos en listas. | 29 |

### 2. Recursion (304 Puntos)
| Ejercicio | Concepto a Evaluar | Puntos |
| :--- | :--- | :--- |
| `collatz-conjecture`| Recursividad básica y contadores. | 43 |
| `rna-transcription` | Procesamiento recursivo elemento a elemento. | 43 |
| `diamond` | Recursividad espacial y generación simétrica. | 43 |
| `anagram` | Recursividad y comprensión de listas. | 43 |
| `phone-number` | Limpieza y validación de datos. | 44 |
| `binary-search` | Recursividad algorítmica (divide y vencerás). | 44 |
| `robot-simulator` | Plegado recursivo de estado. | 44 |

### 3. Functional Structures (20 Puntos)
| Ejercicio | Concepto a Evaluar | Puntos |
| :--- | :--- | :--- |
| `list-ops` | Recrear map, filter, foldl, foldr desde cero. | 7 |
| `custom-set` | Creación de conjuntos (Sets) inmutables. | 7 |
| `matrix` | Análisis y transposición de listas de listas. | 6 |

### 4. Memorization and DP (80 Puntos)
| Ejercicio | Concepto a Evaluar | Puntos |
| :--- | :--- | :--- |
| `pascals-triangle` | Secuencias, combinatoria y *zipping*. | 20 |
| `change` | Algoritmo clásico de vuelto (DP puro). | 20 |
| `sieve` | Optimización (Criba de Eratóstenes). | 20 |
| `knapsack` | Problema de la mochila (DP y optimización). | 20 |

---

## 🛡️ Políticas de Originalidad y Evaluación

* **Análisis de Similitud:** El código de este repositorio será procesado automáticamente por herramientas de detección de similitud de código (como MOSS). Copiar estructuras de árboles sintácticos (aunque se cambien nombres de variables o comentarios) será detectado.
* **Defensa de Código:** El docente se reserva el derecho de solicitar a cualquier estudiante que dibuje en papel el modelo de ejecución (*stack machine*) o el caso base de sus funciones recursivas. Si el estudiante no puede explicar a bajo nivel cómo funciona la solución entregada, se anulará la calificación.
* **Historial de Iteraciones:** El aprendizaje guiado por pruebas requiere refactorización. Entregas con una única iteración perfecta para todos los problemas de forma consecutiva serán sujetas a revisión exhaustiva. ¡Documenten su progreso!
