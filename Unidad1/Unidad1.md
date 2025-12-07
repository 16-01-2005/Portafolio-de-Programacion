## 📘 UNIDAD 1 — Fundamentos de la Programación en C  

> 🧭 *Comprender los principios básicos de la programación estructurada en C y desarrollar el pensamiento lógico necesario para resolver problemas mediante algoritmos.*

---

### 🎯 **Objetivos de la Unidad**
- 💡 Comprender los conceptos básicos del lenguaje C.  
- 🧠 Desarrollar el pensamiento lógico y estructurado.  
- 🧮 Identificar los tipos de datos, variables y operadores en C.  
- 🔤 Manipular cadenas de caracteres utilizando funciones basicas de la biblioteca estándar `<string.h>`.  

---

### 🔤 Pseudocódigos

> 💬*El pseucódigo es el paso intermedio de un programa algorítmico, que se expresan mediante símbolos, y los lenguajes de programación. Siendo este un          método que nos ayudara a la programación y solución del algoritmo del programa.*

---

### 🧠 Driagrama de flujo

> 💬*Los diagramas de flujo son aquellas representaciones graficas que permiten la diagramación y el análisis de todos los aspectos relevante, dando de esta       manera los lineamientos para escribir de una manera clara y lógicas.*

---
### 🧩 **Temas Principales**
1. 🧾 **Introducción al lenguaje C**  
   - Características del lenguaje C.
   
      > 💬*Un algoritmo debe ser preciso, indicar el orden de cada paso de manera clara y sin ambigüedades.*
      
      > 💬*Un algoritmo debe estar definido, si se sigue el algoritmo varias veces con los mismos datos de entrada, los resultados obtenidos deben ser los       mismos.*
      
      > 💬*Un algoritmo debe ser finito, de tiempo finito, su ejecución debe concluir en algún momento.*
---
   - Estructura básica de un programa en C.

     <img width="404" height="124" alt="image" src="https://github.com/user-attachments/assets/f5a12fd2-709d-4e7d-97a9-705a850d6ced" />

   - Proceso de compilación y ejecución.

     <img width="404" height="124" alt="image" src="https://github.com/user-attachments/assets/40664f50-91fd-4f05-98a2-82cbc445dff9" />

   - Uso del entorno de desarrollo VS Code.

     <img width="408" height="375" alt="image" src="https://github.com/user-attachments/assets/f4d5ec1a-ac64-4db2-bb9a-d0a6e054900c" />


2. 🔢 **Tipos de datos y variables**  
   - Tipos de datos primitivos: `int`, `float`, `double`, `char`.
   
         1. int
         Representa números enteros. Es el tipo más común para contar, sumar o manejar valores sin decimales.

         2. float
         Sirve para números reales con punto decimal, pero con precisión moderada.

         3. double
         Es como el float, pero con mayor precisión. Se usa cuando los cálculos necesitan exactitud más alta.

         4. char
         Almacena un solo carácter, pero realmente guarda un número entero (código ASCII).
         Por eso 'A', 'b' o '9' son valores válidos.

   - Declaración e inicialización de variables.

         Declarar una variable en C es indicar su tipo y su nombre, por ejemplo:

         int edad;

         Inicializar es asignarle un valor por primera vez:

         edad = 20;

         También puedes declarar e inicializar en una sola línea:

         int edad = 20;

   - Constantes y uso de `#define`.

         Una constante es un valor que no cambia durante la ejecución del programa. Se usa cuando necesitas asegurar que un dato permanezca fijo.

         Constante con const:

         const int PI = 3.14;


         Aquí PI no puede modificarse en ninguna parte del código.

         Constante con #define:

         #define PI 3.14


Este método no crea una variable; el preprocesador reemplaza cada PI por 3.14 antes de compilar. Se usa para valores globales, mensajes, tamaños o configuraciones.

Diferencia esencial:
const crea una variable protegida.
#define hace un reemplazo textual antes de compilar.      

   - Reglas de nomenclatura en C.  

2. ⚙️ **Operadores y expresiones**  
   - Operadores aritméticos: `+`, `-`, `*`, `/`, `%`.  
   - Operadores relacionales: `==`, `!=`, `<`, `>`, `<=`, `>=`.  
   - Operadores lógicos: `&&`, `||`, `!`.  
   - Precedencia y asociación de operadores.  

3. 🔤 **Estructura de cadenas en C**  
   - Declaración de cadenas: uso de arreglos de tipo `char`.  
   - Inicialización de cadenas y el carácter nulo `'\0'`.  
   - Lectura y escritura de cadenas: `scanf()`, `gets()`, `fgets()`, `printf()`, `puts()`.  
---

### 🧰 **Actividades de Aprendizaje**
- 📝 Escribir programas básicos que lean y escriban cadenas.  
- 🔡 Aplicar funciones de `<string.h>` para analizar y modificar texto.  
- ⚙️ Crear ejercicios que combinen variables, operadores y cadenas.  

### ⚙️ACD - Aprendizaje Contacto con el Docente 
- 🔗 [ACD](Aprendizaje.md)
  
### 🧰 APE - Aprendizaje Práctico Experimental
- 🗂️ [Juegos de Aprendizaje Práctico Experimental](Experimental.md)

- APE1. Primer acercamiento a la construcción de algoritmos con estructuras secuenciales en pseudocódigo
   - 🗂️ [APE 1.](APE1.pdf)
- APE2. Del diseño del algoritmo con estructuras secuenciales a la construcción del programa
   - 🗂️ [APE 2.](APE2.pdf)
- Debugging Challenge: “Cazadores de Bugs” 
   - 🗂️ [Cazadores de bugs](Bugs.pdf)

### 🧰 AA - Aprendizaje Autónomo 
- AA 1. Herramientras digital para pseudocódigo y digrama de flujo
   - 🗂️ [Tarea 1](Tarea1pdf)
- AA 2. Instalación de lenguages de programación
   - 🗂️ [Tarea 2](Tarea2.pdf)


---

### 🧠 **Reflexión Personal**
<p align="justify">
💬 <i>Durante esta unidad comprendí la estructura del lenguaje C y su procesamiento de datos. También aprendí a organizar mis ideas de forma más estructurada, lo que facilitó el proceso de programación. El trabajo con cadenas me ayudó a entender cómo C gestiona la memoria y los caracteres de manera eficiente y controlada, reforzando mi capacidad para desarrollar programas más estables y optimizados.</i>
</p>


---
### 🧠 **Conclusiones**
<p align="justify">
💬 <i>El desarrollo de algoritmos y su implementación en el lenguaje C constituyen la base para lograr soluciones eficaces a los problemas computacionales. Los algoritmos permiten estructurar el pensamiento lógico, dividir un problema complejo en pasos claros y definir procesos precisos que una computadora puede ejecutar. Al utilizar el lenguaje C, estos algoritmos se transforman en soluciones funcionales, optimizadas y de alto rendimiento, gracias a su cercanía al hardware y al control detallado de la memoria y los recursos del sistema.</i>
</p>

<p align="justify">
💬 <i>Las herramientas de programación, como los entornos de desarrollo, depuradores y compiladores, complementan el proceso de creación y facilitan la detección de errores, la optimización del código y el análisis del flujo lógico de ejecución. El uso combinado de algoritmos y herramientas fortalece la capacidad del programador para razonar de manera estructurada, eficiente y creativa, fomentando un pensamiento computacional sólido y aplicable a cualquier área de la informática.</i>
</p>


---

### 🧾 **Evidencias**
- 📄 Capturas de pantalla de programas compilados y ejecutados.
- 🧮 Ejemplo de un código con explicación línea por línea.

[Ejemplo 1](Ejemplo.md) [Ejemplo 2](Ejemplo2.md)
### 💾 **Repositorio con todos los archivos del portafolio**
- 📄 Acceso completo a los materiales, prácticas y proyectos desarrollados durante el curso.

   - https://drive.google.com/drive/folders/1h-xeqlYcn4PQkfEFcYy5ox6T9bdCMFsK
- 🗂️ Crear seudocodigos en pseint y diagrama de flujo

   - https://drive.google.com/drive/folders/1OpWlRFN7Fy5rCB5rr4fL5B_j8_B08o3g
---

🏠 [Portafolio](portafolio.md)

