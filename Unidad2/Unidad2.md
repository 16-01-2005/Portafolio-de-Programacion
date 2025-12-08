# 📘 Unidad 2: Estructuras Algorítmicas de Control
> 📚 *Comprender los principios de las estructuras condicionales y repetitivas en C, desarrollando el pensamiento lógico necesario para controlar el flujo de los programas y resolver problemas mediante algoritmos*

---

## 🎯Objetivos de la unidad 
### 🎯Estructuras Algorítmicas Condicionales

- ✅ Condicional simple: Si … Entonces (if)
- 🔀 Condicional doble: Si … Entonces, Sino … (if-esle)
- 📂 Condicional múltiple: En caso de … (swich/case)
- 🧩 Anidamiento de condicionales

### 🎯Estructuras Algorítmicas Repetitivas

- 📖 Terminología básica
- 🔁 Para (for)
- 🔄 Mientras (while)
- ⏳ Hacer … Mientras (do-while)
- 🧩 Anidamiento de bucles

## 🧩 **Temas Principales**

- ### ✅ Condicional simple: Si … Entonces (if)

   > 📝 *El if es una estructura condicional simple.*
   
   > 🧾 *Es la forma más básica de tomar decisiones dentro de un programa: solo ejecuta un bloque de instrucciones si la condición se cumple.*
   
   > ✅ *Funciona como un guardia lógico:
     si la condición es verdadera, deja pasar el código;
     si es falsa, simplemente no hace nada.*


   > 💡*La condicional simple if en C permite ejecutar un bloque de código solo si se cumple una condición.*

      Estructura básica:
      if (condición) {
      // instrucciones a ejecutar si la condición es verdadera
      }

  
  ### ✅ Características:

   > 🗂️ *La condición se evalúa como verdadera (true) o falsa (false).*
   
   > 📎 *Si la condición es falsa, no se ejecuta nada.*
   
   > 📌 *Se usa cuando se necesita tomar una decisión única en el programa.*

  ### 🧠 Diagrama de Flujo

  <img width="507" height="333" alt="image" src="https://github.com/user-attachments/assets/5f21832d-493c-4584-b81d-bde5611f2791" />

  ### 📌 Codgio en C

  <img width="459" height="257" alt="image" src="https://github.com/user-attachments/assets/b8770256-fcdc-474e-a577-440fc2b44a06" />

---

- ### 🔀 Condicional doble: Si … Entonces, Sino … (if-esle)

   > 🏗️*El if-esle corresponde a una estructura condicional doble.*

   > 📖*En programación, la condicional doble es la que evalúa una condición y ejecuta un bloque si es verdadera, y otro bloque alternativo si es falsa.*
   
   > 🔀 *En C, esa estructura es if–else.*
   
   > 📖 *En palabras simples:
   si se cumple, hace algo;
   si no se cumple, hace otra cosa*
   
   >💡*La condicional doble if–else en C permite ejecutar un bloque de código si la condición se cumple y otro bloque alternativo si la condición es falsa.*

        Estructura básica:
        if (condición) {
           // instrucciones si la condición es verdadera
        } else {
        // instrucciones si la condición es falsa
        }

   ### ✅ Características:

   > 🔀 *Evalúa la condición como verdadera (true) o falsa (false).*

   > 🏗️ *Siempre ejecuta uno de los dos bloques, nunca ambos.*

   > 📖 *Se utiliza cuando el programa debe elegir entre dos acciones posibles.*


   ### 🧠 Diagrama de Flujo

   <img width="507" height="333" alt="image" src="https://github.com/user-attachments/assets/5e10ff84-1d2d-45f0-adb7-92e626bf9cf7" />

   ### 📌Codigo en C
  
  <img width="459" height="257" alt="image" src="https://github.com/user-attachments/assets/3dbdfef7-f098-40d3-854c-c6c1f8df31a8" />

  ---
  
- ### 📂 Condicional múltiple: En caso de … (swich/case)

   > ✅ *Swich/Case corresponde a una estructura condicional múltiple.*
      
   > ☑️ *Es el tipo de estructura que se usa cuando hay varias opciones posibles y el programa debe elegir una según el valor de una variable.*

   > 💡*La condicional múltiple switch–case en C permite seleccionar una acción entre varias opciones posibles según el valor de una variable.*
   
        Estructura básica:
        switch (variable) {
            case valor1:
                // instrucciones cuando variable == valor1
                break;
            case valor2:
                // instrucciones cuando variable == valor2
                break;
            ...
            default:
                // instrucciones si ningún caso coincide
        }

   ### ✅ Características:
   
   > 🔀 *Permite manejar varias alternativas sin usar múltiples if–else encadenados.*
   
   > 🏗️ *Evalúa una sola variable y compara su valor con diferentes casos.*
   
   > 🗂️ *Cada caso representa una opción específica y el break evita que el flujo siga a los demás casos.*
   
   > 📎 *El bloque default se ejecuta si no coincide ningún caso, funcionando como una opción por defecto.*

   ### 🧠 Diagrama de Flujo

   <img width="507" height="333" alt="image" src="https://github.com/user-attachments/assets/72b6c1e4-2967-4ecd-98d0-6da717c55a3c" />

   ### 📌Codigo en C
  
   <img width="650" height="450" alt="image" src="https://github.com/user-attachments/assets/666b7757-1c51-4e70-9aab-5b6caacc19f3" />

---
- ### 🧩 Anidamiento de condicionales

   >📝 *El anidamiento de condicionales ocurre cuando colocamos un if dentro de otro if, o cuando un else contiene otro if.*

   > 🧾 *Sirve para tomar decisiones más complejas, donde cada resultado abre la puerta a nuevas verificaciones. Es una estructura de decisiones en niveles, como       un árbol lógico.*

   >✅ *Funciona como una cadena de filtros:
   si la primera condición es verdadera, se evalúa la siguiente;
   si no es verdadera, el else puede contener otro if que establezca un camino alternativo.*

   >💡*El anidamiento permite manejar múltiples escenarios de forma ordenada, usando if dentro de if, y también else que contienen más condicionales.*

      Estructura básica:
      
      if (condición1) {
          if (condición2) {
              // instrucciones si ambas condiciones son verdaderas
          }
      } else {
          if (condición3) {
              // instrucciones si condición1 es falsa pero condición3 es verdadera
          }
      }

  ### ✅ Características:

   >🗂️ Permite evaluar decisiones en cadena, verificando condiciones más específicas según el resultado anterior.

   >📎 El else también puede contener otro if, creando rutas alternativas de evaluación.

   >📌 Se usa cuando el programa necesita explorar varios escenarios posibles dependiendo de múltiples condiciones


   ### 🧠 Diagrama de Flujo

   <img width="507" height="333" alt="image" src="https://github.com/user-attachments/assets/7ea19bc2-7a64-40ec-a29c-1c8f3aa36208" />

   ### 📌Codigo en C

   <img width="650" height="320" alt="image" src="https://github.com/user-attachments/assets/f7cfd34e-2d9b-4d21-bf3b-2981a7852bd1" />

























