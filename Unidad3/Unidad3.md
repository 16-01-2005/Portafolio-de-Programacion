# 📘 Unidad 3: Programación Modular y Estructuras de Datos Estáticas

> 📚 **Descripción:** Comprender la importancia de dividir problemas complejos en subproblemas más pequeños (módulos) y manejar colecciones de datos del mismo tipo de manera eficiente en memoria.*

---

## 🎯 Objetivos de la unidad

### 📦 Programación Modular

* ✅Conceptos básicos de programación modular.
* 🧩Uso de módulos y funciones en la resolución de problemas.

### 🔹 Estructuras de Datos Estáticas

* 📊 Arreglos Unidimensionales (Vectores)
* ⬛ Arreglos Bidimensionales (Matrices)
* 📦 Arreglos Multidimensionales
* 🔤 Cadenas de caracteres (Strings)

---

## 🧩 Temas Principales
C
>📊 Arreglos Unidimensionales (Vectores)
>📝 Estructura de datos estática que almacena una secuencia de elementos del mismo tipo. 
>🧾 Se organizan contiguamente en la memoria bajo un único nombre. 
>✅ Funcionamiento: Como una fila de casilleros numerados. Para encontrar un dato, solo necesitas saber el número (índice). 
>💡 Uso: Agrupar datos relacionados (como calificaciones) sin declarar una variable para cada uno.

# Programación Modular

## 📦 Conceptos básicos de programación modular

La **programación modular** es una metodología que consiste en dividir un programa grande en partes más pequeñas llamadas **módulos**.  
Cada módulo se encarga de una tarea específica y funciona de manera independiente.

Este enfoque permite que el código sea más claro, organizado y fácil de mantener, evitando programas largos y difíciles de entender.

La idea principal es que cada módulo:
- Tenga una única responsabilidad
- Pueda reutilizarse en otros programas
- Pueda modificarse sin afectar todo el sistema

---

## 🧩 Uso de módulos y funciones en la resolución de problemas

Una **función** es un bloque de código que realiza una tarea concreta y puede ser reutilizado varias veces dentro del programa.  
Un **módulo** agrupa funciones relacionadas que trabajan sobre un mismo objetivo.

Al resolver un problema mediante módulos y funciones:
- El problema se divide en partes pequeñas
- Cada parte se resuelve de forma independiente
- El programa final es más fácil de entender y depurar

Este enfoque mejora la lógica del programa y permite desarrollar sistemas más grandes sin aumentar la complejidad.

---

## 🛠️ Ventajas de la programación modular

- Mejora la organización del código
- Facilita el mantenimiento y la corrección de errores
- Permite reutilizar funciones en otros proyectos
- Reduce la complejidad de programas grandes
- Facilita el trabajo en equipo


Estructura básica:
### 📊 Arreglos Unidimensionales (Vectores)

> **Definición:** Un vector es una estructura de datos **estática** que almacena una colección finita de elementos del mismo tipo (homogéneos) en posiciones de memoria **contiguas**.

#### 🧠 Concepto Lógico
Imagina un vector como una fila de casilleros numerados en un banco.
1.  **Nombre Único:** Toda la fila se llama igual (ej. `Calificaciones`).
2.  **Índice:** Para abrir un casillero específico, necesitas su número (posición).
3.  **Contenido:** Dentro de cada casillero hay un dato (valor).
   
C
int edades[10]; // Arreglo de 10 enteros
✅ Características:

🗂️ Homogeneidad: Todos los datos deben ser del mismo tipo (int, float, etc.).

📎 Índice: Se accede mediante una posición numérica, comenzando siempre desde 0.

📌 Tamaño Fijo: El tamaño se define al compilar y no puede cambiar.

🧠 Diagrama de Flujo

<img width="507" height="333" alt="image" src="https://github.com/user-attachments/assets/9923907a-9f0c-449c-bf74-ce64fa6cc483" />

📌 Codigo en C

<img width="459" height="257" alt="image" src="https://github.com/user-attachments/assets/5aa179ad-1f4d-4b17-99f5-bf311209ae72" />

---
### ⬛ Arreglos Bidimensionales (Matrices)
📝 Estructura que organiza datos en dos dimensiones: filas y columnas. 
🧾 Conocidos comúnmente como matrices o tablas. 
🔀 Funcionamiento: Similar a una hoja de cálculo o una sala de cine (Fila F, Asiento 5). 
💡 Uso: Ideales para tableros de juego, mapas o relaciones matemáticas.

Estructura básica:

C
int tablero[3][3];
✅ Características:

🔀 Acceso: Se usa la sintaxis matriz[i][j].

🏗️ Memoria: Se guardan linealmente en memoria, fila tras fila.

📖 Recorrido: Usualmente requiere dos ciclos for anidados.

🧠 Diagrama de Flujo

<img width="507" height="333" alt="image" src="https://github.com/user-attachments/assets/8cfa3680-3cf7-4f96-8844-1b4e87cd61ff" />

📌 Codigo en C

<img width="459" height="257" alt="image" src="https://github.com/user-attachments/assets/0d64fe6c-77be-445f-a008-b7dda726b18a" />

---

### 📦 Arreglos Multidimensionales
✅ : Arreglos con tres o más dimensiones. 
☑️ Es una extensión lógica de las matrices. 
💡 Analogía: Si una matriz es una hoja, un arreglo 3D es un libro (muchas hojas), o un edificio.

Estructura básica:

C
int cubo[3][3][3];
✅ Características:

🔀 Requiere un índice por cada dimensión.

🏗️ El consumo de memoria crece exponencialmente.

🗂️ Requiere alta abstracción lógica.

🧠 Diagrama de Flujo

<img width="507" height="333" alt="image" src="https://github.com/user-attachments/assets/0e096622-4aa1-4079-ac3c-462c9029a771" />

📌 Codigo en C

<img width="459" height="257" alt="image" src="https://github.com/user-attachments/assets/c2628068-5253-4180-9eec-5dbad6c0a28d" />

---

### 🔤 Cadenas o Strings
✅ En C, es un arreglo de caracteres (char) diseñado para almacenar texto. 
☑️ No existe un tipo primitivo "String", es un arreglo especial. 
💡 Funcionamiento: Es como un collar de cuentas (letras) que siempre termina con un "nudo" especial invisible: el carácter nulo \0.

Estructura básica:

C
char saludo[] = "Hola";
✅ Características:

🔀 Terminador Nulo: Debe terminar con \0 para indicar el fin del texto.

🏗️ Manipulación: Se usan funciones de la librería <string.h>.

🗂️ Cuidado: No se pueden asignar con = después de la declaración.

📌 Codigo en C

<img width="459" height="257" alt="image" src="https://github.com/user-attachments/assets/4badd846-7804-44eb-a797-3bbba5e04ce9" />

---

### ⚠️ Principales Dificultades

> ✔️ Mi mayor dificultad es olvidar que los arreglos inician en 0. 

> ✔️ Me cuesta visualizar arreglos de más de 2 dimensiones.

> ✔️  A veces confundo el paso por valor y por referencia.
> 
### 🌀 Reflexión crítica

> *🗂️ La transición a estructuras de datos y modularidad marca un antes y un después en mi lógica. Entiendo que dividir un problema en funciones hace que sea más fácil de resolver y mantener. Reconozco que dominar los arreglos es fundamental para bases de datos futuras. Necesito practicar más el 'dibujar' el problema en papel antes de codificar.*


## ⚙️ACD - Aprendizaje Contacto con el Docente

- ACD 1. Proyecto Académico Integrador
- ACD 2. Control de aprendizaje sobre python
   - 🔗 [ACD 2](ACD2.md)
- ACD 3. Control de aprendizaje sobre modularidad y estructura de datos.
   - 🔗 [ACD 3](ACD3.md)

## 🧰 APE - Aprendizaje Práctico Experimental

- APE 1. Construcción de funciones y procedimientos en un lenguaje de programación
   - 🗂️ [APE 1.](Teoríadelaprogramación.pdf)


## 🧰 AA - Aprendizaje Autónomo 
- AA 1. Curso Fundamentos de Python 1. Computación UNL
   - 🗂️ [Tarea 1](Python_Essentials_1_certificate_ricardo-ochoa-unl-edu-ec_f202b6e2-a485-4f87-a2b9-81b814eae487.pdf)

[Portafolio](portafolio.md)



