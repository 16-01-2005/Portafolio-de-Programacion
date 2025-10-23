## 📘 UNIDAD 1 — Fundamentos de la Programación en C  

> 🧭 *Comprender los principios básicos de la programación estructurada en C y desarrollar el pensamiento lógico necesario para resolver problemas mediante algoritmos.*

---

### 🎯 **Objetivos de la Unidad**
- 💡 Comprender los conceptos básicos del lenguaje C.  
- 🧠 Desarrollar el pensamiento lógico y estructurado.  
- 🧮 Identificar los tipos de datos, variables y operadores en C.  
- 🔤 Manipular cadenas de caracteres utilizando funciones de la biblioteca estándar `<string.h>`.  

---

### 🧩 **Temas Principales**
1. 🧾 **Introducción al lenguaje C**  
   - Historia y características del lenguaje.  
   - Estructura básica de un programa en C.  
   - Proceso de compilación y ejecución.  
   - Uso del entorno de desarrollo (por ejemplo, Code::Blocks, Dev-C++ o VS Code).  

2. 🔢 **Tipos de datos y variables**  
   - Tipos de datos primitivos: `int`, `float`, `double`, `char`.  
   - Declaración e inicialización de variables.  
   - Constantes y uso de `#define`.  
   - Reglas de nomenclatura en C.  

3. ⚙️ **Operadores y expresiones**  
   - Operadores aritméticos: `+`, `-`, `*`, `/`, `%`.  
   - Operadores relacionales: `==`, `!=`, `<`, `>`, `<=`, `>=`.  
   - Operadores lógicos: `&&`, `||`, `!`.  
   - Precedencia y asociación de operadores.  

4. 🔤 **Estructura de cadenas en C**  
   - Declaración de cadenas: uso de arreglos de tipo `char`.  
   - Inicialización de cadenas y el carácter nulo `'\0'`.  
   - Lectura y escritura de cadenas: `scanf()`, `gets()`, `fgets()`, `printf()`, `puts()`.  
   - Concatenación, copia y comparación con funciones:  
     - `strcpy()`, `strcat()`, `strcmp()`, `strlen()`, `strstr()`.  
   - Ejemplo simple:  
     ```c
     #include <stdio.h>
     #include <string.h>

     int main() {
         char nombre[50];
         printf("Ingrese su nombre: ");
         fgets(nombre, sizeof(nombre), stdin);

         printf("Longitud del nombre: %lu\n", strlen(nombre));
         printf("¡Hola, %s!\n", nombre);

         return 0;
     }
     ```

---

### 🧰 **Actividades de Aprendizaje**
- 📝 Escribir programas básicos que lean y muestren cadenas.  
- 🔡 Aplicar funciones de `<string.h>` para analizar y modificar texto.  
- ⚙️ Crear ejercicios que combinen variables, operadores y cadenas.  
- 🗂️ Documentar los resultados de ejecución con capturas de pantalla.  

---

### 🧠 **Reflexión Personal**
> 💬 *Durante esta unidad comprendí la estructura lógica del lenguaje C y su precisión en el manejo de datos. Manipular cadenas me ayudó a entender cómo C gestiona la memoria y los caracteres de forma controlada.*  

---

### 🧾 **Evidencias**
- 📄 Capturas de pantalla de programas compilados y ejecutados.  
- 📘 Resumen de las funciones más usadas de `<string.h>`.  
- 🧮 Ejemplos de código con explicación línea por línea.  

---

🏠 [Portafolio](index.md)

