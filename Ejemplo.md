 
#💾 Ejemplo 

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

<img width="458" height="336" alt="image" src="https://github.com/user-attachments/assets/71939629-10da-4ab4-9254-69ea7d3ed6a3" />´´´

🏠 [Unidad 1 ](Unidad1.md)
