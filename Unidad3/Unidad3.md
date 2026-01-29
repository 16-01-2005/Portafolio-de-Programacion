# 📘 Unidad 3: Programación Modular y Estructuras de Datos Estáticas

> 📚 **Descripción:** Comprender la importancia de dividir problemas complejos en subproblemas más pequeños (módulos) y manejar colecciones de datos del mismo tipo de manera eficiente en memoria.

---

## 🎯 Objetivos de la unidad

### 📦 Programación Modular

* ✅ Concepto de "Divide y Vencerás"
* 🧩 Definición y uso de Funciones/Módulos
* 🔄 Paso de parámetros y retorno de valores

### 🔹 Estructuras de Datos Estáticas

* 📊 Arreglos Unidimensionales (Vectores)
* ⬛ Arreglos Bidimensionales (Matrices)
* 📦 Arreglos Multidimensionales
* 🔤 Cadenas de caracteres (Strings)

---

## 🧩 Temas Principales

### 📦 Programación Modular: Conceptos y Uso

📝 **El if es una estructura condicional simple.**
🧾 La programación modular es una técnica de diseño de software que divide un programa grande en bloques independientes llamados módulos o funciones.
✅ **Analogía:** Funciona como una **fábrica de automóviles**: en lugar de que una sola persona construya todo el coche, hay departamentos especializados (módulos) que se encargan del motor, las ruedas y la pintura.
💡 **Nota:** La programación modular permite reutilizar código, facilitar la lectura y simplificar el mantenimiento.
        
🗂️ Abstracción: Permite concentrarse en qué hace una función sin preocuparse por cómo lo hace.

📎 Reutilización: Escribes el código una vez y lo llamas cuantas veces quieras.

📌 Mantenibilidad: Si hay un error, solo corriges el módulo afectado.

🧠 Diagrama de Flujo

📌 Codigo en C

📊 Arreglos Unidimensionales (Vectores)
📝 Definición: Estructura de datos estática que almacena una secuencia de elementos del mismo tipo. 🧾 Se organizan contiguamente en la memoria bajo un único nombre. ✅ Funcionamiento: Como una fila de casilleros numerados. Para encontrar un dato, solo necesitas saber el número (índice). 💡 Uso: Agrupar datos relacionados (como calificaciones) sin declarar una variable para cada uno.

Estructura básica:

C
int edades[10]; // Arreglo de 10 enteros
✅ Características:

🗂️ Homogeneidad: Todos los datos deben ser del mismo tipo (int, float, etc.).

📎 Índice: Se accede mediante una posición numérica, comenzando siempre desde 0.

📌 Tamaño Fijo: El tamaño se define al compilar y no puede cambiar.

🧠 Diagrama de Flujo

📌 Codigo en C

⬛ Arreglos Bidimensionales (Matrices)
📝 Definición: Estructura que organiza datos en dos dimensiones: filas y columnas. 🧾 Conocidos comúnmente como matrices o tablas. 🔀 Funcionamiento: Similar a una hoja de cálculo o una sala de cine (Fila F, Asiento 5). 💡 Uso: Ideales para tableros de juego, mapas o relaciones matemáticas.

Estructura básica:

C
int tablero[3][3];
✅ Características:

🔀 Acceso: Se usa la sintaxis matriz[i][j].

🏗️ Memoria: Se guardan linealmente en memoria, fila tras fila.

📖 Recorrido: Usualmente requiere dos ciclos for anidados.

🧠 Diagrama de Flujo

📌 Codigo en C

📦 Arreglos Multidimensionales
✅ Definición: Arreglos con tres o más dimensiones. ☑️ Es una extensión lógica de las matrices. 💡 Analogía: Si una matriz es una hoja, un arreglo 3D es un libro (muchas hojas), o un edificio.

Estructura básica:

C
int cubo[3][3][3];
✅ Características:

🔀 Requiere un índice por cada dimensión.

🏗️ El consumo de memoria crece exponencialmente.

🗂️ Requiere alta abstracción lógica.

🧠 Diagrama de Flujo

📌 Codigo en C

🔤 Cadenas o Strings
✅ Definición: En C, es un arreglo de caracteres (char) diseñado para almacenar texto. ☑️ No existe un tipo primitivo "String", es un arreglo especial. 💡 Funcionamiento: Es como un collar de cuentas (letras) que siempre termina con un "nudo" especial invisible: el carácter nulo \0.

Estructura básica:

C
char saludo[] = "Hola";
✅ Características:

🔀 Terminador Nulo: Debe terminar con \0 para indicar el fin del texto.

🏗️ Manipulación: Se usan funciones de la librería <string.h>.

🗂️ Cuidado: No se pueden asignar con = después de la declaración.

🧠 Diagrama de Flujo

📌 Codigo en C

🧩 Ejercicio en Java
📌 Proyecto: Sistema de Gestión de Notas Estudiantiles 🎓. Realicé un pequeño sistema de gestión de notas estudiantiles en Java. El programa utiliza Programación Modular para separar la lógica. Utiliza un arreglo unidimensional para los nombres de los alumnos y una matriz para sus calificaciones. El sistema calcula el promedio automáticamente pasando los arreglos como parámetros.

🧠 Diagrama de Flujo

📌 Codigo en Java

⚠️ Verificación
⚠️ Principales Dificultades
✔️ Indices (Off-by-one): Mi mayor dificultad es olvidar que los arreglos inician en 0. ✔️ Visualización: Me cuesta visualizar arreglos de más de 2 dimensiones. ✔️ Parámetros: A veces confundo el paso por valor y por referencia.

🌀 Reflexión crítica
🗂️ La transición a estructuras de datos y modularidad marca un antes y un después en mi lógica. Entiendo que dividir un problema en funciones hace que sea más fácil de resolver y mantener. Reconozco que dominar los arreglos es fundamental para bases de datos futuras. Necesito practicar más el 'dibujar' el problema en papel antes de codificar.


