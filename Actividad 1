/******************************************************************************

 Autor: Helam Velázquez                            
Fecha: Marzo 24, 2026
Descripción: Programa que te dice si un usuario es mayor de edad o no.
*******************************************************************************/





#include <iostream>  /*aquí se declara la libreria para entrada y salida de datos*/
#include <string>   /*aquí se declara la libreria para manipular caracteres*/

using namespace std; /*permite utilizar elementos de la biblioteca estándar*/
int main () {       /*Sirve para organizar la lógica, llamar a otras funciones y devolver un entero al sistema operativo*/
    int edad;      /*Se declara la variable edad*/

    do{          /*comienza el bucle*/
    
    cout << "Ingresa tu edad (presiona 0 para salir): ";   /*Sale el mensaje para iniciar la interaccion con el usuario*/
    cin >> edad;                                          /*guarda el número que tecleó el usuario*/
     
    if (edad == 0) {                                     /*se agrega la condición de que si el usuario teclea cero*/
            cout << "Saliendo del sistema..." << endl;  /*el sistema muestra ese mensaje*/
            break;                                      /*termina el bucle inmediatamente*/
    }
    
    
    if (edad >= 18){                                               /*se agrega la opción de que si el numero es mayor o igual a 18*/
        cout << "Bienvenido, eres mayor de edad." << endl;        /*Muestra este mensaje*/
    } else {                                                     /*si el numero es menor a 18*/
        
            cout << "Bienvenido, eres menor de edad." << endl;  /*Muestra este otro mensaje*/
        }
        
    } while (true); /*Repite el ciclo*/
    
    return 0;       /*El programa terminó correctamente*/
}
