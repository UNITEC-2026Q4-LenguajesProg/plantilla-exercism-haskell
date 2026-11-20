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

📋 Instrucciones de Configuración y Entrega

Para que tu código sea evaluado correctamente, resolverás los ejercicios en Exercism y subirás tus soluciones aprobadas directamente a este repositorio generado por Classroom 50. Sigue estos pasos al pie de la letra:

⚠️ IMPORTANTE (Actualización): NO configures GitHub Syncer en Exercism. Debido a las políticas de permisos de la organización en GitHub, la sincronización automática está bloqueada para repositorios de clase. La entrega se realizará manualmente mediante git push.

Paso 1: Configurar Exercism y la CLI local

Crea una cuenta en Exercism y únete al track de Haskell.

Instala la interfaz de línea de comandos (CLI) de Exercism en tu computadora y configúrala con tu token personal (exercism configure --token=TU_TOKEN).

Asegúrate de tener instalado el compilador de Haskell (GHC) y sus herramientas (se recomienda instalar mediante GHCup).

Paso 2: Clonar tu repositorio de entrega (Classroom 50)

Clona este repositorio en tu computadora:

git clone <URL-de-este-repositorio>
cd <nombre-de-la-carpeta-del-repositorio>


Dentro de este repositorio, crea una carpeta por cada ejercicio que resuelvas para mantener tu entrega ordenada. Por ejemplo:

├── README.md
├── hello-world/
│   └── HelloWorld.hs
├── leap/
│   └── LeapYear.hs
└── ...


(Opcional recomendado) Agrega el enlace a tu perfil público de Exercism en un archivo llamado PERFIL.txt o al final de este README.md para facilitar la verificación de tus ejercicios aprobados.

Paso 3: Flujo de Trabajo por Ejercicio

Por cada ejercicio indicado en la rúbrica, deberás realizar el siguiente proceso:

Descargar el ejercicio mediante la terminal:

exercism download --exercise=[nombre] --track=haskell


Escribir tu solución en el archivo .hs correspondiente (usualmente ubicado dentro de la carpeta src/).

Validar localmente que tu código compile y pase todas las pruebas unitarias.

Enviar tu solución a Exercism:

exercism submit src/[Archivo].hs


Verificar aprobación: Entra a la página web de Exercism y confirma que tu solución haya sido aprobada (todas las pruebas en verde).

Subir la solución a Classroom 50: Copia tu archivo .hs aprobado dentro de la carpeta correspondiente en tu repositorio local de Classroom 50 y súbelo a la rama principal (main):

git add .
git commit -m "Solución ejercicio: [nombre]"
git push origin main


💡 Recomendaciones para la Entrega

Realiza un commit independiente por cada ejercicio completado para conservar un historial claro de tu avance.

Verifica directamente en GitHub (en tu navegador) que tus archivos .hs aparezcan correctamente en la rama main antes de la fecha límite.

No modifiques la configuración (Settings) del repositorio.

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
