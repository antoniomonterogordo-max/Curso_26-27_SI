# Relacion de Ejercicios de Binario y de Puertas Logicas

> @autor: Antoniomonterogordo

## Relacion 19

### Ejercicio 1

- Apartado a solucion
E7F,C1(16) = N(10) = 15 * 16^0 + 7 * 16^1 + 14 * 16^2 + 12 * 16^-1 + 1 * 16^-2 =
3711,75390...(10)  
- Apartado b solucion
10011000,011(2) = 0 * 2^0 + 0 * 2^1 + 0 * 2^2 + 1 * 2^3 + 1 * 2^4 + 0 * 2^5
 + 0 * 2^6 + 1 * 2^7 + 0 * 2^-1 + 1 * 2^-2 + 1 * 2^-3 = 152,375(10)


### Ejercicio 2

- Apartado a solución
240,4375(10) = 11110000/0111(2)
11110000/0111(2) = 364,34(8)
11110000/0111(2) = 150,7(16)
- Apartado b solución
6,6(10) = 110,100110(2)
La parte fraccionaria es un periódico mixto puro, por lo cual no tiene un final
decimal definido
Valor almacenado = 6 + 1 * 2^-1 + 0 * 2^-2 + 0 * 2^-3 + 1 * 2^-4 + 1 * 2^-5
 + 0 * 2^-6 = 6,59375(10)
Error cometido = 6,6(10) - 6,59375(10) = 0,00625(10)


### Ejercicio 3

- Apartado a solución
96D,1(16) = 010101101101/0001(10) = 1 * 2^0 + 0 * 2^1 + 1 * 2^2 + 1 * 2^3 +
0 * 2^4 + 1 * 2^5 + 1 * 2^6 + 0 * 2^7 + 1 * 2^8 + 0 * 2^9 + 1 * 2^10 +
0 * 2^11 + 0 * 2^-1 + 0 * 2^-2 + 0 * 2^-3 + 1 * 2^-4 = 1389,0625(10)
- Apartado b solución
2357,7(8) = 010011101111/111(10) = 1 * 2^0 + 1 * 2^1 + 1 * 2^2 + 1 * 2^3 +
0 * 2^4 + 1 * 2^5 + 1 * 2^6 + 1 * 2^7 + 0 * 2^8 + 0 * 2^9 + 1 * 2^10 +
0 * 2^11 + 1 * 2^-1 + 1 * 2^-2 + 1 * 2^-3 = 1263,875(10)


### Ejercicio 4 

- Apartado a solución
101000,11(2) + 1010,01(2) = 110011,00(2)
Acarreo en el segundo decimal, también en la quinta y primera  bombilla
- Apartado b solución
1010100,1 - 100111,01 = 101101,01(2)


### Ejercicio 5 
- Apartado a
-88 = 1 1011000  a complemento 1: 0 0100111 complemento 2: 0 0101000
- Apartado b
20 - 37 en c2: 1 01100 + 0 011010 = 1 1101111
- Apartado c
(-45) + (-41) en c2: 11010011 + 11010111 = 110101010
No ocurre desbordamiento, debido a que no cambia de signo
- Apartado d
(-20) + (37): 10010100 + 00100101
Lo que ocurre es que el de resultado tendra que tener el símbolo del de mayor valor, por lo que el bit del signo vendrá
del +37 el cual seria 0.


### Ejercicio 6
- Apartado a
5 - 6,5 = 0011,000 - 1001,1000 = 1110,1000
c1 resultado = 0001,0111, le sumamos 1: 0001,1000


### Ejerciio 7
- Apartado a
10000 * 101 = 1010000
- Apartado b
1011,11 * 101 = 111010,11
- Apartado c
11000001 = 193
Moverlo dos a la izquierda nos daria 1100000100, que seria multiplicarlo por 4, y nos daria 772
No se perdería ninguna información
Moverlo tres a la derecha nos daría 11000,001, que seria como dividirlo por 8, y nos daría 24,125 o 24(10)
Se predería la fraccional 0,125


### Ejercicio 8
- Apartado a
4,7GB archivo, 800Mbps
4,7GB = 4,7 * 10^9bytes 1GiB = 1073741824 bytes
4,7 * 10^9 / 1073741824 = 4,377GiB * 8 = 37,6 * 10 ^9 bits
800 Mbps = 0,8 * 10^9 bits
37,6 * 10^9 / 0,8 * 10^9 = 47 segundos mínimo


### Ejercicio 9
- Apartado a
S = A + B(Negado) + (B XOR C)
- Tabla de Verdad
| A | B | C | NOT(A + B) | B XOR C | S |
|---|---|---|:----------:|:-------:|:-:|
| 0 | 0 | 0 |     1      |    0    | 1 |
| 0 | 0 | 1 |     1      |    1    | 1 |
| 0 | 1 | 0 |     0      |    1    | 1 |
| 0 | 1 | 1 |     0      |    0    | 0 |
| 1 | 0 | 0 |     0      |    0    | 0 |
| 1 | 0 | 1 |     0      |    1    | 1 |
| 1 | 1 | 0 |     0      |    1    | 1 |
| 1 | 1 | 1 |     0      |    0    | 0 |


###Ejercicio 10
- Expresión simplificada
S = NOT(A)·NOT(B) + NOT(A)·NOT(C) + A·B·C

- Tabla de Verdad
| Pos | A | B | C | S |
|:---:|:-:|:-:|:-:|:-:|
|  0  | 0 | 0 | 0 | 1 |
|  1  | 0 | 0 | 1 | 1 |
|  2  | 0 | 1 | 0 | 1 |
|  3  | 0 | 1 | 1 | 0 |
|  4  | 1 | 0 | 0 | 0 |
|  5  | 1 | 0 | 1 | 0 |
|  6  | 1 | 1 | 0 | 0 |
|  7  | 1 | 1 | 1 | 1 |


### Fecha: 05-October-2026- Expresión simplificada

