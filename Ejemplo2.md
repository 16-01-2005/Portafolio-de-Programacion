# Ejemplo 2 
### *El problema nos pide calcular la comisión de la venta de un asesor que realiza ventas de carros, se calcula con la siguiete formula comsion = (venta *4 )/ 100 y tambien se ingresa cual es total de la venta, al final se imprime la comisión de la venta y cual es el total de la venta*
    	Algoritmo calculoComision

    	// Se declaran las variables reales
    	Definir comision, venta Como Real

    	// Se pide que se ingrese el precio del vehículo
	    Escribir "Ingrese el precio del vehículo: "
	    Leer venta
	
	    // Se calcula la comisión (venta * 4) / 100
	    comision <- (venta * 4) / 100
	
	    // Se calcula la venta después de la comisión
	    venta <- venta - comision
	
	    // Se imprimen los resultados
	    Escribir "La comisión de la venta es: ", comision
	    Escribir "La venta después de la comisión es: ", venta
	
		FinAlgoritmo


<img width="510" height="689" alt="image" src="https://github.com/user-attachments/assets/6c234b3e-55ed-474b-949b-0f28f72d92f4" />

| Precio Vehiculo| Comsion | Venta Final |
|----------------|---------|-------------|
| Dato 1     | Dato 2     | Dato 3     |
| Dato A     | Dato B     | Dato C     |



		#include <stdio.h>
		
		int main(){
		
		//Se ingresa las variables flotantes (Reales)
		float comision, venta;
		
		//Se pide que se ingrese el precio del vehiculo
		printf("Ingrese el precio del vehiculo: \n");
		//Se lee el precio del vehiculo
		scanf("%f", &venta);
		
		//Se realiza la formula para poder sacar la comision (venta * 4) / 100
		comision = (venta * 4) / 100;
		//Se calcula la venta con la formula venta - comision
		venta = venta - comision;
		
		//Se imprime la comsion y la venta
		printf("La comision de la venta es: %.2f", comision);
		printf("La venta es de: %.2f", venta);
		
		return 0;
		}

<img width="718" height="287" alt="image" src="https://github.com/user-attachments/assets/3d90fde0-c14d-4d70-8358-5603d80f32e8" />


🏠 [Unidad 1 ](Unidad1.md)

