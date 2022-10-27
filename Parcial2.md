# Presentación
## Problemas resueltos en clase con Diagrama de flujo de datos
### Ejercicio 1. Hacer un diagrama que cuente hasta el 10 e imprima el conteo.
#### 1.1 Analisis
Se necesita que el programa avance del 1 al 10, mientras vaya sumando mediante un contador ir imprimiendo las salidas del contador hasta imprimir los 10 numeros.
#### 1.2 Diagrama
![dfd1while](https://user-images.githubusercontent.com/113472808/198164691-bc7c2a8c-fd99-4bdb-8648-d6eca20adb40.png)

![dfd1dowhile](https://user-images.githubusercontent.com/113472808/198164697-cb3cb421-0199-45d4-a41e-eefeb6ecc205.png)

![dfd1for](https://user-images.githubusercontent.com/113472808/198164698-b41e274f-3043-4cba-b516-edf7e650b492.png)

#### 1.3 Prueba de escritorio


#### 1.4 codigo
//Contar los numeros del 1 al 10 DoWhile

void main() {
  int cont = 1;
  do {
    print(cont);
    cont = cont + 1;
  } while (cont <= 10);
}


//Contar los numeros del 1 al 10 For

void main() {
  for (var i = 1; i <= 10; i++) {
    print(i);
  }
}


//Contar los numeros del 1 al 10 While

void main() {
  int cont = 1;

  while (cont <= 10) {
    print(cont);
    cont = cont + 1;
  }
}


#### 1.5 Entradas
Ningua, solo establece un contador en 0 que vaya en aumento hasta 10
#### 1.6 Salidas
Imprime el aumento del contador. 1,2,3,4,5,6,7,8,9,10

### Ejercicio 2. Contar del 1 al 10 y sumar los valores.
#### 2.1 Analisis
Se requiere insertar un inicio y posteriormente una salida de datos que imprima un dia de la semana como texto "Dia" para dar fin con el programa
#### 2.2 Diagrama
![dfd2while](https://user-images.githubusercontent.com/113472808/198164778-f3e2fcf3-63b1-43ec-9954-80a31f344aac.png)

![dfd2dowhile](https://user-images.githubusercontent.com/113472808/198164779-f8df05d0-4070-46ad-bf1e-605472ee82d5.png)

![dfd2for](https://user-images.githubusercontent.com/113472808/198164781-8ad2f5f0-3e9c-434f-ad28-4b5192a07236.png)

#### 2.3 Prueba de escritorio

#### 2.4 Entradas
Ninguna, solo se asigna la impresion de "Lunes"
#### 2.5 Salidas
Lunes

### Ejercicio 3. Obtenga la suma de los primeros 5 numeros pares.
#### 3.1 Analisis
Se requiere insertar un inicio, se pedira el nombre en un proceso para asignar la variable, imprimira "Hola Nombre" para dar fin al programa
#### 3.2 Diagrama
![dfd3while](https://user-images.githubusercontent.com/113472808/198164813-9456f675-9823-4b1f-8637-2138efcee46f.png)

![dfd3dowhile](https://user-images.githubusercontent.com/113472808/198164814-b766e8ae-7214-4719-ae82-04249f659be6.png)

![dfd3for](https://user-images.githubusercontent.com/113472808/198164815-62a6e6df-eec5-40d4-85e1-385b22f38ab7.png)

#### 3.3 Prueba de Escritorio
![Prueba3](https://user-images.githubusercontent.com/113472808/190934783-b89d1853-b4ab-43c9-affc-b8ecfe692d00.PNG)
#### 3.4 Entradas
Ninguna, solo se asigna una cadena con el Nombre para posteriormente imprimir el mensaje "Hola,Nombre" para dar fin al programa
#### 3.5 Salidas
Hola Pedro

### Ejercicio 4. Almacena en un array el numero N leido del teclado, el tamaño del array es 10.
#### 4.1 Analisis
Se requiere insertar un inicio, el programa preguntara el nombre al usuario, lo asignara en una entrada de datos y soltara una salida imprimiendo "Buen dia,Nom" para dar fin al programa
#### 4.2 Diagrama
![dfd4while](https://user-images.githubusercontent.com/113472808/198164856-1cb3c365-538e-41f4-8afe-755f106f4b94.png)

![dfd4dowhile](https://user-images.githubusercontent.com/113472808/198164859-85c82fb9-a0c4-4bd5-a1f3-91d2bb749c2a.png)

![dfd4for](https://user-images.githubusercontent.com/113472808/198164861-f4f1142a-01b5-4230-8459-bcee4f602011.png)

#### 4.3 Prueba de escritorio
![Prueba4](https://user-images.githubusercontent.com/113472808/190936214-9e9812d1-cda7-40c5-a980-049e0c0cd13b.PNG)
#### 4.4 Entradas
Se pide que se introduzca el nombre de la persona
#### 4.5 Salidas
Buen dia Pedro

### Ejercio 5. Almacene los N numeros leidos del teclado en un vector de 10 elementos.
#### 5.1 Analisis 
Se requiere un inicio, para ingresar un proceso de datos para la operacion 2x2 para imprimir el resultado y dar fin al programa
#### 5.2 Diagrama
![dfd5while](https://user-images.githubusercontent.com/113472808/198164893-47049259-3d7d-46c3-bd32-3e6da32f516e.png)

![dfd5dowhile](https://user-images.githubusercontent.com/113472808/198164894-4579bde0-318a-45b9-829a-230bc2a45121.png)

![dfd5for](https://user-images.githubusercontent.com/113472808/198164895-ec6fd128-cd68-477c-b376-c07897cce463.png)

#### 5.3 Prueba de escritorio
![Prueba5](https://user-images.githubusercontent.com/113472808/190936639-8b5e7f29-d8ee-477c-835b-0f9d3f9f9726.PNG)
#### 5.4 Entradas
Ninguna solo se realiza el proceso 2x2
#### 5.5
2x2

### Ejercicio 6. Almacene un contador regresivo en un vector, el conteo es de 10 a 0
#### 6.1 Analisis
Se requiere un inicio, para ingresar el valor de N que sera de 5, posteriomente un proceso donde se saque su cuadrado con NxN para despues dar fin al programa
#### 6.2 Diagrama
![dfd6while](https://user-images.githubusercontent.com/113472808/198164913-883e216b-1cc5-4500-9f26-1f846da589a4.png)

![dfd6dowhile](https://user-images.githubusercontent.com/113472808/198164916-f55674f8-5948-4ae2-8a16-b4f5e4ad4b41.png)

![dfd6for](https://user-images.githubusercontent.com/113472808/198164917-df10bffa-3cb3-4bad-9be7-48e0c503330f.png)

#### 6.3 Prueba de escritorio
![Prueba6](https://user-images.githubusercontent.com/113472808/190938291-fef70064-aac0-4b32-8698-f33c87e781d5.PNG)
#### 6.4 Entradas
Ninguna, en este caso solo se le imparte el valor de 5 a N
#### 6.5 Salidas 
NxN

### Ejercicio 7. Almacene en un vector de tamaño 10 todos los numeros pares capturados hasta completar todos.
#### 7.1 Analisis
Se requiere un inicio, se hara una entrada de datos para saber el valor que se le dara a N y posteriormente se hara un proceso de datos para sacar su cuadrado mediante NxN para dar fin al programa.
#### 7.2 Diagrama
![dfd7while](https://user-images.githubusercontent.com/113472808/198164938-3b43779c-f1cd-4635-94b3-33d367b69935.png)

![dfd7dowhile](https://user-images.githubusercontent.com/113472808/198164939-bc3a6455-8a8f-4354-9eb9-60807cb8e52b.png)

![dfd7for](https://user-images.githubusercontent.com/113472808/198164940-b6d3f792-8912-4af1-beb4-ff9d2a6d8269.png)

#### 7.3 Prueba de escritorio
![Prueba7](https://user-images.githubusercontent.com/113472808/190938531-1b44c3a1-0af2-4a56-a858-bfa062d939ac.PNG)
#### 7.4 Entradas
Se solicita el valor de N para dar paso a la operacion
#### 7.5 Salidas
NxN

### Ejercicio 8. Obtenga el promedio de las calificaciones aprobatorias y la cantidad de alumnos reprobados. La calificacion es entre 0 y 10 y el maximo de alumnos es 15. Indique la calificacion mas alta.
#### 8.1 Analisis
Se requiere un inicio, se hara una entrada de datos para conocer el año de nacimiento del usuario, posteriormente se hara un proceso para calcular su edad restando a 2022 el año de nacimiento de la persona, para despues dar fin al programa.
#### 8.2 Diagrama
![dfd8while](https://user-images.githubusercontent.com/113472808/198164957-56ab69e6-c7df-40a4-b30f-e598c013c174.png)

![dfd8dowhile](https://user-images.githubusercontent.com/113472808/198164960-da1638e1-6fa9-4f41-9b48-95faa5c54e17.png)

![dfd8for](https://user-images.githubusercontent.com/113472808/198164963-86a46873-ca5c-4bd7-924c-4aa07d3021ac.png)

#### 8.3 Prueba de escritorio
![Prueba8](https://user-images.githubusercontent.com/113472808/190938716-8d8b5a2f-56ba-4eef-9429-7394177dfb6b.PNG)
#### 8.4 Entradas
Se pregunta al usuario su año de nacimiento registrado como "anac"
#### 8.5 Salidas
2022-anac

### Ejercicio 9.  Capture N numeros en el rango li ls donde Li=Limite inferior y Ls=limite superior para Li<ls y Li>0. Obtenga Cantidad de numeros pares y su promedio, cantidad de numeros impares y su promedio y que promedio es mayor.
#### 9.1 Analisis
Se requiere un inicio, posteriormente mediante una entrada de datos se preguntara el año de nacimiento registrado como anac y el año actual registrado como aact, para despues sacar la edad de la persona calculando la resta de aact-anac para dar fin al programa
#### 9.2 Diagrama
![dfd9while](https://user-images.githubusercontent.com/113472808/198164987-12368753-6e1f-423e-8dac-da4c5239b8bd.png)
  
![dfd9dowhile](https://user-images.githubusercontent.com/113472808/198164989-db33bbbf-c90d-47e6-8ca6-d0c88247a254.png)
  
![dfd9for](https://user-images.githubusercontent.com/113472808/198164990-57298c84-3f2c-40f9-b804-9c0d05055ac1.png)

#### 9.3 Prueba de escritorio
![Prueba9](https://user-images.githubusercontent.com/113472808/190939049-95c89175-8074-4c13-89c4-7c475d74bcbe.PNG)
#### 9.4 Entradas
Se registra el año actual como "anac" y el año de nacimiento como "aact"
#### 9.5 Salidas
aact-anac

### Ejercicio 10. Obtener la frecuencia de N calificaciones entre 1,10 Indique cantidad de reprobados, cantidad de aprobados, promedio de aprobados y promedio general.
#### 10.1 Analisis
Se requiere un inicio, mediante una entrada de datos se pediira un numero y posteriormente otro para despues en un proceso sacar el cuadrado de la suma de esos 2 para dar fin al programa
#### 10.2 Diagrama
![dfd10dowhile](https://user-images.githubusercontent.com/113472808/198165017-150285fe-bcd2-4d4c-8c78-7a44adf945dd.png)
  
![dfd10for](https://user-images.githubusercontent.com/113472808/198165018-c6e0e767-2144-40ed-88ab-72cede70fb7a.png)
  
![dfd10while](https://user-images.githubusercontent.com/113472808/198165020-0ad0640b-5511-4d51-bb02-5e801a873b09.png)

#### 10.3 Prueba de escritorio
![Prueba10](https://user-images.githubusercontent.com/113472808/190939857-ec4ae301-666c-4218-9937-02c185c1a5d6.PNG)
#### 10.4 Entradas
Se piden 2 numeros registrados con las variables n1 y n2 respectivamente
#### 10.5 Salidas
(n1+n2)x(n1+n2)

### Ejercicio 11. Captura 10 numeros enteros positivos y los ponga en un verctor, diga cual es mayor.
#### 11.1 Analisis
Se requiere un inicio, en esta ocasion se hara una entrada de datos que registrara el año actual de la persona y su año de nacimiento, posteriormente se comprobara si el año actual de la persona es superior al de nacimiento, si la condicion no se cumple regresara a pedir nuevamente el año actual siendo mayor que el de nacimiento, en caso de que si se cumple se realizara un proceso para saber la edad restando el año de nacimiento al año actual para dar fin al programa
#### 11.2 Diagrama
![dfd11for](https://user-images.githubusercontent.com/113472808/198165097-466a6bbb-1a9b-4966-81b1-f25e6d64ed5e.png)

#### 11.3 Prueba de escritorio
![Prueba11](https://user-images.githubusercontent.com/113472808/190941349-7519dcdf-3ba7-43b8-8821-1762a7712014.PNG)
#### 11.4 Entradas
Se pregunta al usuario su año actual como "aact" y posteriormente su año de nacimiento como "anac" luego se hace una operacion para calcular la edad
#### 11.5 Salidas
aact-anac

### Ejercicio 12. Obtener la distancia mayor de 2 numeros consecutivos en una lista de 10 vectores.
#### 12.1 Analisis
Se requiere un inicio, se le pedira al usuario su año de nacimiento y se comprobara que sea mayor a 0 si la condicion se cumple le pedira el año de actual mayor al año nacimiento, si se cumple la condicion se genera un proceso de operacion para calcular la edad aact-anac para dar fin al programa
#### 12.2 Diagrama
![dfd12for](https://user-images.githubusercontent.com/113472808/198165127-f751b4a5-7ad2-400f-a298-d27faecb2784.png)

#### 12.3 Prueba de escritorio
![Prueba 12](https://user-images.githubusercontent.com/113472808/190944120-343a39aa-7733-4640-9ba0-58b9ec09dab7.PNG)
#### 12.4 Entradas
Se le pide al usuario su año de nacimiento mayor a 0 guardado como anac y el actual registrado como aact
#### 12.5 Salidas
aact-anac

### Ejercicio 13. Almacene en un array el resultado de una tabla de multiplicar (10 numeros)
#### 13.1 Analisis
Se requiere un inicio, se programa un contador en un proceso y se imprime, mediante una condicion se espera que sea 10, en caso no ser 10 el contador aumenta en 1 y regresa a repetir el proceso, una vez el valor sea 10 imprime los 10 numeros para dar fin al programa
#### 13.2 Diagrama
![dfd13for](https://user-images.githubusercontent.com/113472808/198165156-4b06b734-fdad-4b51-a935-222e088e1955.png)

#### 13.3 Prueba de escritorio
![image](https://user-images.githubusercontent.com/113472808/190945543-cd75ca9b-3bc1-4131-b1d2-9f890305610f.png)
#### 13.4 Entradas
Ninguna se crea un proceso con un contador en sumatoria
#### 13.5 Salidas
1,2,3,4,5,6,7,8,9,10

### Ejercicio 14. Imprimir el siguiente dibujo
### *
### **
### ***
### ****
### *****
#### 14.2 Analisis
Se requiere un incio, con un proceso se hace un contador para los numeros naturales hasta el 10 y con el otro para el proceso de la suma, empiezan los procesos de la suma + el contador para entrar en una condicion, si el resultado es menor a 10 aumenta el contador y regresa a la suma, cuando el resultado ya sea 10 imprime el resultado de las sumas para dar fin al programa.
#### 14.2 Diagrama
![dfd14for](https://user-images.githubusercontent.com/113472808/198165170-fdf77ac5-635e-47ed-84ed-f1f24adbd61a.png)

#### 14.3 Prueba de escritorio
![image](https://user-images.githubusercontent.com/113472808/190950119-ce00b111-f12c-41dc-84ba-efead85e8e82.png)
#### 14.4 Entradas
Se establecen un contador en C y se guarda el registro de la suma en S
#### 14.5 Salida
S


# FIN
