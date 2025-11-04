# 🧠 *Ejemplo 2* 
#### 📝 Problema
### 🧩 **El problema solicita calcular la comisión obtenida por un asesor de ventas de automóviles. La comisión se determina mediante la fórmula: comisión = (venta × 4) / 100. En el programa, el usuario ingresa el valor total de la venta, y posteriormente se calcula la comisión correspondiente. Finalmente, se muestran en pantalla tanto el monto de la comisión como el total de la venta realizada.**

#### ✅ Pseudocodigo 
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


#### ✅ Diagrama de Flujo
<img width="510" height="689" alt="image" src="https://github.com/user-attachments/assets/6c234b3e-55ed-474b-949b-0f28f72d92f4" />

#### ✅ Pruebas de Escritorio

| Venta Vehiculo|      Comosion = (Venta Vehiculo * 4) / 100 |          Venta Final = Venta - Comsion |
|---------------|--------------------------------------------|----------------------------------------|
| 25.000     	| Comsion = (25.000 *4) / 100 = 1000         | Venta Final = 25.000 - 1000 = 24.000   |
| 35.000    	| Comsion = (35.000 *4) / 100 = 1400         | Venta Final = 35.000 - 1400 = 14.000   |
| 1500			| Comsion = (1500 *4) / 100	= 60	         | Venta Final = 1500 - 60 = 1440         |	


#### ✅ Codgio en C

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

#### ✅ Ejecución del Programa
<img width="718" height="287" alt="image" src="https://github.com/user-attachments/assets/3d90fde0-c14d-4d70-8358-5603d80f32e8" />

🛠️ [Ejemplo 1](Ejemplo.md)
🏠 [Unidad 1 ](Unidad1.md)

