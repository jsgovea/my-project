<!-- # Welcome to MkDocs

For full documentation visit [mkdocs.org](http://mkdocs.org). -->

<!-- ## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.
* `portada` -->

#Tarea
##Centro de Estudios Superiores del Noroeste
![Logo](img/cesun.png)

* `Nombre del Alumno` - Jorge Soto Govea
* `Materia` - Matemáticas Discretas
* `Nombre del Maestro` - Manuel Iván Cañez García
* `Actividad` - Proyecto Final 
* `Fecha de Entrega` - Martes 5 de Diciembre de 2017


# Problemas

## Problema 1
```
Inicio 
numero = 0

IMPRIMIR ingrese un numero entero
LEER numero
IF(numero % 2 == 0)
{
    
}else if(j + 1; > raiz(i))
{
    IMPRIMIR es numero primo
}

FIN
```

## Problema 2
```
INICIO

numero = 0
sumatoria = 0;
resultado; 

IMPRIMIR ingrese un numero entero
LEER numero
FOR(i = 0; numero>0; i++)
{
    FOR(j = 2; j<i; j++)
    {
        IF(i % j == 0)
        {
            sumatoria++;
        }
    }
}

sumatoria = resultado;

IMPRIMIR resultado;

FIN
```

## Problema 3
[Compilar](https://codepad.remoteinterview.io/XPNDLATXPR).
``` c++
#include <iostream>
#include <math.h>

int main(int argc, const char * argv[]) {
        for (int i=2; i<100; i++)
            for (int j=2; j*j<=i; j++)
            {
                if (i % j == 0)
                    break;
                else if (j+1 > sqrt(i)) {
                    std::cout << i << " ";
                    
                }
                
            }
        
        return 0;
}

```
## Problema 4
```
INICIO
 
 numero = 0;
factorial

 ESCRIBIR ingrese un numero
 LEER numero

 WHILE(numero != 0)
 {
     factorial = factorial * numero;
     numero = numero - 1;
 }

 ESCRIBIR factorial

 FIN
```

## Problema 5
```
INICIO

a, b = 0
diferencia

ESCRIBIR ingrese el valor para a
LEER a
ESCRIBIR ingrese el valor para b
LEER b

WHILE(diferencia > 0)
{
    IF(a > b)
    {
        a = b
        b = diferencia
        diferencia = a % b
    }ELSE IF
    {
        ESCRIBIR a debe ser mayor a b 
    }
}

ESCRIBIR el maximo comun divisor es b

FIN
```

## Problema 6
[Compilar](https://codepad.remoteinterview.io/ZAXZTAQIQB).
``` c++
#include <iostream>

int main(int argc, const char * argv[]) {
    int numero = 0;
    
    std::cout << "Ingrese un numero: ";
    std::scanf("%d", &numero);
    
    if(numero % 2 == 0)
    {
        std::cout << "\nEl numero es par";
    }else
        std::cout << "\nNumero impar";
   
    return 0;
}
```

## Problema 7
```
INICIO

numero = 0

ESCRIBIR ingrese un numero
LEER numero

IF(num % 3 == 0)
{
    ESCRIBIR el numero es multiplo de 3
}ELSE
    ESCRIBIR el numero no es multiplo de 3

FIN
```

## Problema 8
```
INICIO

arreglo[1, 2, 3, 4, 5]
arreglo[].length
numero = 0

WHILE(numero != arreglo.lenght)
 {
     factorial = factorial * arreglo.length;
     numero = numero - 1;
 }

 ESCRIBIR factorial

FIN
```