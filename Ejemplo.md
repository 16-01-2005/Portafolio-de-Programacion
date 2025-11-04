# 🧠 *Ejemplo 1*

### 🧩 **El ejercicio consiste en ingresar las coordenadas de dos puntos en el plano, (x₁, y₁) y (x₂, y₂), y calcular la distancia entre ellos utilizando la fórmula: d = √((x₂ - x₁)² + (y₂ - y₁)²). Finalmente, el programa muestra en pantalla la distancia obtenida entre ambos puntos.**

#### ✅ Pseudocodigo
    Algoritmo Distancia_Entre_Puntos
    
    Definir x1, y1, x2, y2, distancia Como Real

    // Se ingresan las primeras coordenadas
    Escribir "Ingrese las primeras coordenadas (x1 y1):"
    Leer x1, y1

    // Se ingresan las segundas coordenadas
    Escribir "Ingrese las segundas coordenadas (x2 y2):"
    Leer x2, y2

    // Se realiza la operación para calcular la distancia con la formula d= RAIZ((x2 - x1)^2 + (y2 - y1)^2)
    distancia <- RAIZ((x2 - x1)^2 + (y2 - y1)^2)

    // Se muestra el resultado
    Escribir "La distancia entre los puntos (", x1, " ; ", y1, ") y (", x2, " ; ", y2, ") es: ", distancia
    
    FinAlgoritmo

#### ✅ Diagrama de flujo
   <img width="522" height="700" alt="image" src="https://github.com/user-attachments/assets/22a3f7ce-9f54-4930-a331-4a25839d0f1c" />

#### ✅ Pruebas de Escritorio
| Puntos x1 y1 | Puntos x2 y2 | d=√((x_2-x_1)²+(y_2-y_1)²)         | Imprime |
|--------------|--------------|------------------------------------|---------|
| 36.78 86.45  | 25.36 42.17  | d=√((25.36-36.78)²+(42.17-86.45)²) |45.73    |   
| 45 78        | 26.4 27      | d=√((26.4-45)²+(27-78)²)           |54.29    | 
| 178.45 467.55| 134 698.7    | d=√((134-178.45)²+(698.7-467.55)²) |226.55   | 


#### ✅ Codigo en C
    #include <stdio.h>  
    //Se ingresa la libreria para que se pueda hacer funciones matematicas mas complejas
    #include <math.h> 
    
    int main(){

    //Se definen las variables reales
    float x1, y1, x2, y2, distancia;

    //Se ingresa las primeras coordenadas 
    printf("Ingrese las primeras coordenadas (x1 y1)");
    // Se leen las primeras coordenadas
    scanf("%f %f", &x1, &y1);
    //Se ingresa las segundas coordenadas 
    printf("Ingrese las segundas coordenadas (x2 y2)");
    // Se leen las segundas coordenadas
    scanf("%f %f", &x2, &y2);
    
    //Se realiza la operacion para encontrar distancia que es con la siguiente formula d=√((x_2-x_1)²+(y_2-y_1)²)
    distancia = sqrt(pow((x2 - x1), 2.0) + pow((y2 - y1), 2.0));
    
    //Se escribe la distancia entre los dos puntos 
    printf("La distancia que entre los dos puntos (%.2f ; %.2f) y (%.2f ; %.2f) es : %.2f", x1, y1, x2, y2, distancia);

    return 0;
    }

#### ✅ Ejecución del Programa
<img width="938" height="336" alt="image" src="https://github.com/user-attachments/assets/71939629-10da-4ab4-9254-69ea7d3ed6a3" />


🛠️ [Ejemplo 2 ](Ejemplo2.md)
🏠 [Unidad 1 ](Unidad1.md)
