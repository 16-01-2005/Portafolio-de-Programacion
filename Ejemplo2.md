# Ejemplo 2 

    Algoritmo calcularNota
		
		// Declaración de variables reales (flotantes)
		Definir Nota1, Nota2, Nota3, NC, NF, NL Como Real
		
		// Se pide al usuario ingresar las notas
		Escribir "Ingrese su primera nota, segunda nota y la nota del laboratorio:"
		Leer Nota1, Nota2, NL
		
		// Se realiza la fórmula: Nota3 = 3 * ((60 - (NL * 0.3)) / 0.7) - (Nota1 + Nota2)
		Nota3 <- 3 * ((60 - (NL * 0.3)) / 0.7) - (Nota1 + Nota2)
		
		// Estructura condicional para evaluar los casos posibles
		Si Nota3 < 0 Entonces
			Escribir "Ya aprueba con las notas actuales."
			Nota3 <- 0
		Sino
			Si Nota3 > 100 Entonces
				Escribir "No es posible aprobar (necesitaría más de 100 puntos)."
			Sino
				Escribir "La tercera nota que necesita es de: ", Nota3, " para aprobar con 60."
			FinSi
		FinSi
		
		// Se calcula el promedio de certámenes: NC = (Nota1 + Nota2 + Nota3) / 3
		NC <- (Nota1 + Nota2 + Nota3) / 3
		
		// Se calcula la nota final: NF = (NC * 0.7) + (NL * 0.3)
		NF <- (NC * 0.7) + (NL * 0.3)
		
		// Se muestran los resultados finales
		Escribir "Promedio de los certámenes (NC): ", NC
		Escribir "Nota final estimada (NF): ", NF
		
    FinAlgoritmo


<img width="682" height="706" alt="image" src="https://github.com/user-attachments/assets/d2605e88-14fc-461e-94ad-5e658bb19b03" />


    #include <stdio.h>

    int  main(){

    //Se ingresan las variables reales (Flotantes) 
    float Nota1, Nota2, Nota3, NC, NF, NL;

    //Se pide al usuario la Nota 1, Nota 2 y la Nota del Laboratorio
    printf("Ingrese su primer, segunda nota y la nota del laboratorio: \n");
    //Se leen las variables 
    scanf("%f %f %f", &Nota1, &Nota2, &NL);

    //Se realiza la formula Nota3 = 3 * ((60 - (NL * 0.3)) / 0.7) - (Nota1 + Nota2)
    Nota3 = 3 * ((60 - (NL * 0.3)) / 0.7) - (Nota1 + Nota2);

    //Utilize el if y else if para poder poner condiciones y dependiendo de las condiciones cumplidas se imprime lo necesario
    if (Nota3 < 0) {
        printf("\nYa aprueba con las notas actuales.\n");
        Nota3 = 0;
    } else if (Nota3 > 100) {
        printf("\nNo es posible aprobar (necesitaria mas de 100 puntos)\n");
    } else {
        printf("\nLa tercer nota que necesita es de: %.2f para aprobar con 60\n", Nota3);
    }

    // Se realizo la operacion nc=(n1+n2+n3)/3
    NC = (Nota1 + Nota2 + Nota3) / 3;
    
    // Se realizo la operacion nf=(nc*0.7)+(nl*0.3)
    NF = (NC * 0.7) + (NL * 0.3);

    //Se imprimer las notas fnales 
    printf("\nLa nota 3 es: %.2f\n", Nota3);
    printf("Promedio de las notas es: %.2f\n", NC);
    printf("Nota final estimada (NF): %.2f\n", NF);

    return 0;
    }

<img width="698" height="344" alt="image" src="https://github.com/user-attachments/assets/6d6b18a2-36af-44fa-9c94-0b9e2280f022" />


🏠 [Unidad 1 ](Unidad1.md)

