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

![image](https://user-images.githubusercontent.com/113472808/198320670-8b90cce5-9cdf-4b1e-8629-1c32efda71ba.png)

![image](https://user-images.githubusercontent.com/113472808/198320850-07915870-0110-4d30-add2-799da1d72d53.png)

![image](https://user-images.githubusercontent.com/113472808/198320967-77ef664a-78b6-4480-b4fe-f6c39f6c38f3.png)


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
1,2,3,4,5,6,7,8,9,10

### Ejercicio 2. Contar del 1 al 10 y sumar los valores.
#### 2.1 Analisis
Imprimir un contador que vaya en aumento del 1 al 10, 1 2 3 4 5 6 7 8 9 10 y hacer que sume los valores 1+2+3+4+5+6+7+8+9+10=55
#### 2.2 Diagrama
![dfd2while](https://user-images.githubusercontent.com/113472808/198164778-f3e2fcf3-63b1-43ec-9954-80a31f344aac.png)

![dfd2dowhile](https://user-images.githubusercontent.com/113472808/198164779-f8df05d0-4070-46ad-bf1e-605472ee82d5.png)

![dfd2for](https://user-images.githubusercontent.com/113472808/198164781-8ad2f5f0-3e9c-434f-ad28-4b5192a07236.png)

#### 2.3 Codigo
//Contar del 1 al 10 y sumar los valores DoWhile

void main() {
  var suma = 0;
  int cont = 1;

  do {
    suma = suma + cont;
    cont = cont + 1;
  } while (cont <= 10);

  print(suma);
}


//Contar del 1 al 10 y sumar los valores FOR

void main() {
  var Suma = 0;
  for (var i = 1; i <= 10; i++) {
    Suma = Suma + i;
  }
  print(Suma);
}


//Contar del 1 al 10 y sumar los valores While

void main() {
  int suma = 0;
  int cont = 1;

  while (cont <= 10) {
    suma = suma + cont;
    cont = cont + 1;
  }

  print(suma);
}


#### 2.4 Prueba de escritorio

![image](https://user-images.githubusercontent.com/113472808/198338067-215e9e57-640b-4489-8f9d-da8d571f279c.png)

![image](https://user-images.githubusercontent.com/113472808/198338082-1309dd06-42ef-4707-a226-fc847d748e45.png)

![image](https://user-images.githubusercontent.com/113472808/198338100-7d927164-3fca-489c-8d26-bd894498bf8b.png)


#### 2.5 Entradas
Ninguna, solo se establece un contador, y posteriormente una suma que guarde cada numero que va imprimiendo el contador y lo sume con el siguiente
#### 2.6 Salidas
55

### Ejercicio 3. Obtenga la suma de los primeros 5 numeros pares.
#### 3.1 Analisis
Establecer un contador para que imprima numeros consecutivos comprobar que sean pares hasta completar 5 numeros pares y sumarlos. 1 2 3 4 5 6 7 8 9 10 2+4+6+8+10=30
#### 3.2 Diagrama
![dfd3while](https://user-images.githubusercontent.com/113472808/198164813-9456f675-9823-4b1f-8637-2138efcee46f.png)

![dfd3dowhile](https://user-images.githubusercontent.com/113472808/198164814-b766e8ae-7214-4719-ae82-04249f659be6.png)

![dfd3for](https://user-images.githubusercontent.com/113472808/198164815-62a6e6df-eec5-40d4-85e1-385b22f38ab7.png)

#### 3.3 Codigo
//calcular la suma de los primeros 5 numeros pares DoWhile

void main() {
  int suma = 0;
  int cont = 1;

  do {
    suma = suma + cont * 2;
    cont = cont + 1;
  } while (cont <= 5);

  print(suma);
}


//Obtenga la suma de los primeros 5 numeros pares For

void main() {
  int suma = 0;

  for (var i = 2; i <= 10; i += 2) {
    suma = suma + i;
  }

  print(suma);
}


//Calcular la suma de los primeros 5 numeros pares While

void main() {
  int suma = 0;
  int cont = 1;

  while (cont <= 5) {
    suma = suma + cont * 2;
    cont = cont + 1;
  }

  print(suma);
}


#### 3.4 Prueba de Escritorio

![image](https://user-images.githubusercontent.com/113472808/198338156-33eb6d41-1f1a-48d3-ac26-d7f7bc0901d1.png)

![image](https://user-images.githubusercontent.com/113472808/198338175-fc0faeb3-f068-40eb-ad4f-34ce1495dde4.png)

![image](https://user-images.githubusercontent.com/113472808/198338192-62df15b9-e8d7-43a6-8d17-462db7f0857e.png)


#### 3.5 Entradas
Ninguna, el contador establece un conteo consecutivo, detecta si un numero es par, y en caso de ser par lo va sumando en una suma.
#### 3.6 Salidas
30

### Ejercicio 4. Almacena en un array el numero N leido del teclado, el tamaño del array es 10.
#### 4.1 Analisis
En un array [10] alamacenar el numero N leido, 5 [5,5,5,5,5,5,5,5,5,5]
#### 4.2 Diagrama
![dfd4while](https://user-images.githubusercontent.com/113472808/198164856-1cb3c365-538e-41f4-8afe-755f106f4b94.png)

![dfd4dowhile](https://user-images.githubusercontent.com/113472808/198164859-85c82fb9-a0c4-4bd5-a1f3-91d2bb749c2a.png)

![dfd4for](https://user-images.githubusercontent.com/113472808/198164861-f4f1142a-01b5-4230-8459-bcee4f602011.png)

#### 4.3 Codigo
//Almacena en un array el numero N leido del teclado, el tamaño del array es 10 FOR
import 'dart:io';
import 'dart:async';

void main() {
  var cont = 0;
  var array = [];
  int n = int.parse(stdin.readLineSync()!);
  do {
    array.add(n);
    cont = cont + 1;
  } while (cont <= 9);

  print(array);
}


//Almacena en un array el numero N leido del teclado, el tamaño del array es 10 FOR
import 'dart:io';
import 'dart:async';

void main() {
  var array = [];
  int n = int.parse(stdin.readLineSync()!);
  for (var i = 0; i < 10; i++) {
    array.add(n);
  }
  print(array);
}


//Almacena en un array el numero N leido del teclado, el tamaño del array es 10 FOR
import 'dart:io';
import 'dart:async';

void main() {
  var cont = 0;
  var array = [];
  int n = int.parse(stdin.readLineSync()!);
  while (cont <= 9) {
    array.add(n);
    cont = cont + 1;
  }

  print(array);
}


#### 4.4 Prueba de escritorio

![image](https://user-images.githubusercontent.com/113472808/198338244-ed747bed-59fe-4d2e-a83c-86cea66a7ca9.png)

![image](https://user-images.githubusercontent.com/113472808/198338256-bb859094-9576-498b-bcf7-98509d41cd0c.png)

![image](https://user-images.githubusercontent.com/113472808/198338270-a0242db8-b83a-46fc-8e6c-d96f673d7e84.png)

#### 4.5 Entradas
Se crea un array de 10, y se almacena el numero N "5" por ejemplo
#### 4.6 Salidas
[5,5,5,5,5,5,5,5,5,5]

### Ejercio 5. Almacene los N numeros leidos del teclado en un vector de 10 elementos.
#### 5.1 Analisis 
Crear una array de [10] hasta llenarlo de numeros leidos del teclado. [4,6,2,4,1,7,8,10,5,2]
#### 5.2 Diagrama
![dfd5while](https://user-images.githubusercontent.com/113472808/198164893-47049259-3d7d-46c3-bd32-3e6da32f516e.png)

![dfd5dowhile](https://user-images.githubusercontent.com/113472808/198164894-4579bde0-318a-45b9-829a-230bc2a45121.png)

![dfd5for](https://user-images.githubusercontent.com/113472808/198164895-ec6fd128-cd68-477c-b376-c07897cce463.png)

#### 5.3 Codigo

//Almacena los N numeros leidos del telcado en un vector de 10 elementos WHILE
import 'dart:io';
import 'dart:async';

void main() {
  var cont = 0;
  var array = [];
  do {
    int n = int.parse(stdin.readLineSync()!);
    array.add(n);
    cont = cont + 1;
  } while (cont <= 9);

  print(array);
}



//Almacena los N numeros leidos del telcado en un vector de 10 elementos FOR
import 'dart:io';
import 'dart:async';

void main() {
  var array = [];

  for (var i = 0; i < 10; i++) {
    int n = int.parse(stdin.readLineSync()!);
    array.add(n);
  }
  print(array);
}


//Almacena los N numeros leidos del telcado en un vector de 10 elementos WHILE
import 'dart:io';
import 'dart:async';

void main() {
  var cont = 0;
  var array = [];

  while (cont <= 9) {
    int n = int.parse(stdin.readLineSync()!);
    array.add(n);
    cont = cont + 1;
  }
  print(array);
}


#### 5.4 Prueba de escritorio

![image](https://user-images.githubusercontent.com/113472808/198338395-61039f54-c283-4298-bbed-63a0aaaec47b.png)

![image](https://user-images.githubusercontent.com/113472808/198338409-4e8887da-adc6-4914-8daa-9b8aab833ec7.png)

![image](https://user-images.githubusercontent.com/113472808/198338421-f5e1ad3b-d565-4841-87f4-58d1c7d58ec8.png)


#### 5.5 Entradas
Ingresamos n numeros hasta completar 10. 2 4 7 5 78 10 2 53 2 6
#### 5.6
[2, 4, 7, 5, 78, 10, 2, 53, 2, 6]

### Ejercicio 6. Almacene un contador regresivo en un vector, el conteo es de 10 a 0
#### 6.1 Analisis
Se necesita crear un array para almacenar un conteo de 10 a 0, en este caso seria de [11] hacer un contador que empiece en 10 e irlo reduciendo hata que sea igual a 0.
#### 6.2 Diagrama
![dfd6while](https://user-images.githubusercontent.com/113472808/198164913-883e216b-1cc5-4500-9f26-1f846da589a4.png)

![dfd6dowhile](https://user-images.githubusercontent.com/113472808/198164916-f55674f8-5948-4ae2-8a16-b4f5e4ad4b41.png)

![dfd6for](https://user-images.githubusercontent.com/113472808/198164917-df10bffa-3cb3-4bad-9be7-48e0c503330f.png)

#### 6.3 Codigo

//Almacene un contador regresivo en un vector, el conteo es de 10 a 0 DoWhile

void main() {
  var array = [];
  var c = 10;
  do {
    array.add(c);
    c--;
  } while (c >= 0);

  print(array);
}


//Almacene un contador regresivo en un vector, el conteo es de 10 a 0 FOR

void main() {
  var array = [];

  for (var i = 10; i >= 0; i--) {
    array.add(i);
  }
  print(array);
}


//Almacene un contador regresivo en un vector, el conteo es de 10 a 0 DoWhile

void main() {
  var array = [];
  var c = 10;

  while (c >= 0) {
    array.add(c);
    c--;
  }

  print(array);
}


#### 6.4 Prueba de escritorio

![image](https://user-images.githubusercontent.com/113472808/198338485-b08abee7-f19c-4c3e-ba4f-37860a3671fd.png)

![image](https://user-images.githubusercontent.com/113472808/198338498-5e9eba3b-26ac-4a07-bf9e-8515928a88df.png)

![image](https://user-images.githubusercontent.com/113472808/198338518-8f67d747-35c8-4fcc-8ae9-9ea2370831f6.png)


#### 6.5 Entradas
Ninguna, se crea un contador en 10 y un array que almacene los 11 numeros.
#### 6.6 Salidas 
[10,9,8,7,6,5,4,3,2,1,0]

### Ejercicio 7. Almacene en un vector de tamaño 10 todos los numeros pares capturados hasta completar todos.
#### 7.1 Analisis
En un vector de [10] se van a almacenar los numeros pares que se logren capturar hasta llenar todos, los impares no deben entrar al vector por lo que se ignoraran y seguiran. 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 [2 4 6 8 10 12 14 16 18 20]
#### 7.2 Diagrama
![dfd7while](https://user-images.githubusercontent.com/113472808/198164938-3b43779c-f1cd-4635-94b3-33d367b69935.png)

![dfd7dowhile](https://user-images.githubusercontent.com/113472808/198164939-bc3a6455-8a8f-4354-9eb9-60807cb8e52b.png)

![dfd7for](https://user-images.githubusercontent.com/113472808/198164940-b6d3f792-8912-4af1-beb4-ff9d2a6d8269.png)

#### 7.3 Codigo

//Almacene en un vector de tamaño 10 todos los numeros pares capturados hasta completar todos DoWhile
import 'dart:io';
import 'dart:async';

void main() {
  var array = [];
  var c = 0;
  do {
    int n = int.parse(stdin.readLineSync()!);

    if (n % 2 == 0) {
      array.add(n);
      c = c + 1;
    }
  } while (c <= 9);
  print(array);
}

//Almacene en un vector de tamaño 10 todos los numeros pares capturados hasta completar todos FOR
import 'dart:io';
import 'dart:async';

void main() {
  var array = [];

  for (var i = 0; i <= 10; i++) {
    int n = int.parse(stdin.readLineSync()!);
    if (n % 2 == 0) {
      array.add(n);
      i = i - 1;
    }
  }
  print(array);
}



//Almacene en un vector de tamaño 10 todos los numeros pares capturados hasta completar todos DoWhile
import 'dart:io';
import 'dart:async';

void main() {
  var array = [];
  var c = 0;

  while (c <= 10) {
    int n = int.parse(stdin.readLineSync()!);
    c = c + 1;
    if (n % 2 == 0) {
      array.add(n);
      c = c - 1;
    }
  }
  print(array);
}


#### 7.4 Prueba de escritorio

![image](https://user-images.githubusercontent.com/113472808/198338655-b374ad0c-6626-4836-8c0d-651f9369151b.png)

![image](https://user-images.githubusercontent.com/113472808/198338668-698ecf2c-eb28-4b13-9451-ea5bca839e63.png)

![image](https://user-images.githubusercontent.com/113472808/198338684-511cfb4a-1b6b-4458-8a3b-1dc39d91a467.png)


#### 7.5 Entradas
Insertar la cantidad de N numeros hasta que se complete el vector que almacenara solo los N numeros pares hasta haber leido 10. 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 
#### 7.6 Salidas
[2 4 6 8 10 12 14 16 18 20]

### Ejercicio 8. Obtenga el promedio de las calificaciones aprobatorias y la cantidad de alumnos reprobados. La calificacion es entre 0 y 10 y el maximo de alumnos es 15. Indique la calificacion mas alta.
#### 8.1 Analisis
Insertar N cantidad de calificaciones, almacenar en un contador los alumnos que aprobaron <6 y sumarlos para sacar el promedio y los alumnos que reprobaron >6, solo se pueden insertar calificaciones entre el numero 0 y 10 por lo que si excede el numero no sera una calificacion valida, y son maximo 15 alumnos, por lo que se tendran que llenar 15 espacios pero no mas. Ademas almacenar las calificaciones para compararlas y ver cual de todas las insertadas es la mas alta.
#### 8.2 Diagrama
![dfd8while](https://user-images.githubusercontent.com/113472808/198164957-56ab69e6-c7df-40a4-b30f-e598c013c174.png)

![dfd8dowhile](https://user-images.githubusercontent.com/113472808/198164960-da1638e1-6fa9-4f41-9b48-95faa5c54e17.png)

![dfd8for](https://user-images.githubusercontent.com/113472808/198164963-86a46873-ca5c-4bd7-924c-4aa07d3021ac.png)

#### 8.3 Codigo

/*calcule calificaciones de maximo 15 alumnos, saque promedio de aprobados
cuantos reprobaron y la calificacion mas alta DoWhile*/
import 'dart:io';
import 'dart:async';

void main() {
  double proma = 0;
  var contr = 0;
  double sumaa = 0;
  double conta = 0;
  double cal1 = 0;
  double cal2 = 1;
  var cont = 0;
  do {
    double c = double.parse(stdin.readLineSync()!);
    cont = cont + 1;
    if (c > 10) {
      print('la calificacion no puede ser mayor a 10');
      cont = cont - 1;
    }
    if (c < 0) {
      print('la calificacion no puede ser menor a 0');
      cont = cont - 1;
    }
    if (c < 6 && c > 0) {
      contr = contr + 1;
    }
    if (c <= 10 && c >= 6) {
      cal1 = c;
      sumaa = sumaa + cal1;
      conta++;
    }
    if (cal1 > cal2) {
      cal2 = cal1;
    }
  } while (cont <= 14);

  proma = sumaa / conta;
  print('el promedio de aprobados es $proma');
  print('la calificacion mas alta es $cal2');
  print('la cantidad de reprobados son $contr');
}



/*calcule calificaciones de maximo 15 alumnos, saque promedio de aprobados
cuantos reprobaron y la calificacion mas alta FOR*/
import 'dart:io';
import 'dart:async';

void main() {
  double proma = 0;
  var contr = 0;
  double sumaa = 0;
  double conta = 0;
  double cal1 = 0;
  double cal2 = 1;

  for (var i = 1; i <= 15; i++) {
    double c = double.parse(stdin.readLineSync()!);
    if (c > 10) {
      print('la calificacion no puede ser mayor a 10');
      i = i - 1;
    }
    if (c < 0) {
      print('la calificacion no puede ser menor a 0');
      i = i - 1;
    }
    if (c < 6 && c > 0) {
      contr = contr + 1;
    }
    if (c <= 10 && c >= 6) {
      cal1 = c;
      sumaa = sumaa + cal1;
      conta++;
    }
    if (cal1 > cal2) {
      cal2 = cal1;
    }
  }
  proma = sumaa / conta;
  print('el promedio de aprobados es $proma');
  print('la calificacion mas alta es $cal2');
  print('la cantidad de reprobados son $contr');
}



/*calcule calificaciones de maximo 15 alumnos, saque promedio de aprobados
cuantos reprobaron y la calificacion mas alta While*/
import 'dart:io';
import 'dart:async';

void main() {
  double proma = 0;
  var contr = 0;
  double sumaa = 0;
  double conta = 0;
  double cal1 = 0;
  double cal2 = 1;
  var cont = 0;

  while (cont <= 14) {
    double c = double.parse(stdin.readLineSync()!);
    cont = cont + 1;
    if (c > 10) {
      print('la calificacion no puede ser mayor a 10');
      cont = cont - 1;
    }
    if (c < 0) {
      print('la calificacion no puede ser menor a 0');
      cont = cont - 1;
    }
    if (c < 6 && c > 0) {
      contr = contr + 1;
    }
    if (c <= 10 && c >= 6) {
      cal1 = c;
      sumaa = sumaa + cal1;
      conta++;
    }
    if (cal1 > cal2) {
      cal2 = cal1;
    }
  }

  proma = sumaa / conta;
  print('el promedio de aprobados es $proma');
  print('la calificacion mas alta es $cal2');
  print('la cantidad de reprobados son $contr');
}


#### 8.4 Prueba de escritorio

![image](https://user-images.githubusercontent.com/113472808/198338766-23856ed8-b01c-461a-afa4-32b0b38ea02e.png)

![image](https://user-images.githubusercontent.com/113472808/198338790-2dbe720d-e733-4b17-ad63-2a6ae749de65.png)

![image](https://user-images.githubusercontent.com/113472808/198338821-e638cd24-4dbf-40a8-8f45-4ab70a259a2b.png)

#### 8.5 Entradas
5 8 6 9 7 5 8 4 5 10 4 9 7 8 9 
#### 8.6 Salidas
promedio 8.1, calificacion mas alta 10 y reprobados 5

### Ejercicio 9.  Capture N numeros en el rango li ls donde Li=Limite inferior y Ls=limite superior para Li<ls y Li>0. Obtenga Cantidad de numeros pares y su promedio, cantidad de numeros impares y su promedio y que promedio es mayor.
#### 9.1 Analisis
Capturar los N numeros del rango introducido que es li y ls, donde li debe ser menor a ls y mayor a 0 y ls debe ser mayor a li, sumar los pares para sacar su promedio y cuantos son al igual que con los impares, y de esos 2 promedios tenemos que compararlos para saber cual de esos es mayor.
#### 9.2 Diagrama
![dfd9while](https://user-images.githubusercontent.com/113472808/198164987-12368753-6e1f-423e-8dac-da4c5239b8bd.png)
  
![dfd9dowhile](https://user-images.githubusercontent.com/113472808/198164989-db33bbbf-c90d-47e6-8ca6-d0c88247a254.png)
  
![dfd9for](https://user-images.githubusercontent.com/113472808/198164990-57298c84-3f2c-40f9-b804-9c0d05055ac1.png)
  
#### 9.3 Codigo
  
/*capture N numeros en el rango [Li,Ls] donde:
Li=Limite inferior
Ls=Limite superior para Li<Ls y Li>0
obtenga:
-cantidad de numeros pares y su promedio
-cantidad de numeros impares y su promedio
-que promedio es mayo?*/

import 'dart:io';

void main() {
  double sumap = 0;
  double sumai = 0;
  var contp = 0;
  var conti = 0;
  double promp = 0;
  double promi = 0;
  print('Introduce el limite inferior, mayor a 0');
  var li = int.parse(stdin.readLineSync()!);
  if (li < 0) {
    print('tu limite inferior debe ser mayor a 0');
  }
  if (li > 0) {
    print('Ahora introduce un limite superior');
    var ls = int.parse(stdin.readLineSync()!);
    if (ls < li) {
      print('tu limite superior debe ser mayor a tu limite inferior');
    }
    var cont = li;
    do {
      if (cont <= ls) {
        sumai = sumai + cont;
        conti = conti + 1;
      }
      if (cont % 2 == 0) {
        sumap = sumap + cont;
        contp = contp + 1;
        sumai = sumai - cont;
        conti = conti - 1;
      }
      cont = cont + 1;
    } while (cont <= ls);

    promi = sumai / conti;
    print('los impares son $conti y su promedio es $promi');
    promp = sumap / contp;
    print('los pares son $contp y su promedio es $promp');
    if (promp < promi) {
      print('$promi es mayor');
    }
    if (promp > promi) {
      print('el promedio $promp es mayor');
    }
  }
}

  
  
  
  /*capture N numeros en el rango [Li,Ls] donde:
Li=Limite inferior
Ls=Limite superior para Li<Ls y Li>0
obtenga:
-cantidad de numeros pares y su promedio
-cantidad de numeros impares y su promedio
-que promedio es mayo?*/

import 'dart:io';

void main() {
  double sumap = 0;
  double sumai = 0;
  var contp = 0;
  var conti = 0;
  double promp = 0;
  double promi = 0;
  print('Introduce el limite inferior, mayor a 0');
  var li = int.parse(stdin.readLineSync()!);
  if (li < 0) {
    print('tu limite inferior debe ser mayor a 0');
  }
  if (li > 0) {
    print('Ahora introduce un limite superior');
    var ls = int.parse(stdin.readLineSync()!);
    if (ls < li) {
      print('tu limite superior debe ser mayor a tu limite inferior');
    }

    for (var i = li; i <= ls; i++) {
      sumai = sumai + i;
      conti = conti + 1;

      if (i % 2 == 0) {
        sumap = sumap + i;
        contp = contp + 1;
        sumai = sumai - i;
        conti = conti - 1;
      }
    }

    promi = sumai / conti;
    print('los impares son $conti y su promedio es $promi');
    promp = sumap / contp;
    print('los pares son $contp y su promedio es $promp');
    if (promp < promi) {
      print('$promi es mayor');
    }
    if (promp > promi) {
      print('$promp es mayor');
    }
  }
}

  
  
  /*capture N numeros en el rango [Li,Ls] donde:
Li=Limite inferior
Ls=Limite superior para Li<Ls y Li>0
obtenga:
-cantidad de numeros pares y su promedio
-cantidad de numeros impares y su promedio
-que promedio es mayo?*/

import 'dart:io';

void main() {
  double sumap = 0;
  double sumai = 0;
  var contp = 0;
  var conti = 0;
  double promp = 0;
  double promi = 0;
  print('Introduce el limite inferior, mayor a 0');
  var li = int.parse(stdin.readLineSync()!);
  if (li < 0) {
    print('tu limite inferior debe ser mayor a 0');
  }
  if (li > 0) {
    print('Ahora introduce un limite superior');
    var ls = int.parse(stdin.readLineSync()!);
    if (ls < li) {
      print('tu limite superior debe ser mayor a tu limite inferior');
    }
    var cont = li;

    while (cont <= ls) {
      if (cont <= ls) {
        sumai = sumai + cont;
        conti = conti + 1;
      }
      if (cont % 2 == 0) {
        sumap = sumap + cont;
        contp = contp + 1;
        sumai = sumai - cont;
        conti = conti - 1;
      }
      cont = cont + 1;
    }
    

    promi = sumai / conti;
    print('los impares son $conti y su promedio es $promi');
    promp = sumap / contp;
    print('los pares son $contp y su promedio es $promp');
    if (promp < promi) {
      print('$promi es mayor');
    }
    if (promp > promi) {
      print('el promedio $promp es mayor');
    }
  }
}

 

#### 9.4 Prueba de escritorio

![image](https://user-images.githubusercontent.com/113472808/198338897-967e07d6-71d1-488d-ae9d-cc46e55520ce.png)

![image](https://user-images.githubusercontent.com/113472808/198338946-7c974e9d-e67d-4e4b-8805-7382bb70bce8.png)

![image](https://user-images.githubusercontent.com/113472808/198338979-a632872b-9ffc-4c5a-a18e-7488f6160bb2.png)
  
#### 9.5 Entradas
Capturar los limites ejemplo establecer el limite inferior 2 y superior 7
#### 9.6 Salidas
promedio pares 4, promedio impares 5, el promedio mayor es 5

### Ejercicio 10. Obtener la frecuencia de N calificaciones entre 1,10 Indique cantidad de reprobados, cantidad de aprobados, promedio de aprobados y promedio general.
#### 10.1 Analisis
Se requiere obtener N calificaciones entre 1 y 10 de calificacion, sacar la frecuencia con la que cada calificacion aparece, indicar cunantos alumnos reprobaron, cuantos son los que aprobaron, sacar el promedio de aprobados mediante un contador y una suma solo de los aprobados 6> y un promedio general por lo que tambien se deben contar los reprobados y el total de todos los alumnos y sus calificaciones para sacar su promedio general
#### 10.2 Diagrama
![dfd10dowhile](https://user-images.githubusercontent.com/113472808/198165017-150285fe-bcd2-4d4c-8c78-7a44adf945dd.png)
  
![dfd10for](https://user-images.githubusercontent.com/113472808/198165018-c6e0e767-2144-40ed-88ab-72cede70fb7a.png)
  
![dfd10while](https://user-images.githubusercontent.com/113472808/198165020-0ad0640b-5511-4d51-bb02-5e801a873b09.png)
  
#### 10.3 Codigo
  
  /*obtener la frecuencia de N calificaciones entre [1,10]
indique cantidad de reprobados, cantidad de aprobados,
promedio de aprobados y promedio general FOR*/
import 'dart:io';

void main() {
  var contr = 0;
  var conta = 0;
  var contt = 0;
  double sumag = 0;
  double sumaa = 0;
  double promg = 0;
  double porma = 0;
  var C0 = 0;
  var C1 = 0;
  var C2 = 0;
  var C3 = 0;
  var C4 = 0;
  var C5 = 0;
  var C6 = 0;
  var C7 = 0;
  var C8 = 0;
  var C9 = 0;
  var C10 = 0;

  print('inserta las 10 calificaciones entera positiva, entre 1 y 10');
  for (var i = 0; i <= 9; i++) {
    int c = int.parse(stdin.readLineSync()!);

    if (c > 11) {
      print('La calificacion debe ser menor a 10');
      i = i--;
    }
    if (c < 0) {
      print('la calificacion debe ser mayor a 0');
      i = i--;
    }
    if (c == 0) {
      C0 = C0 + 1;
    }
    if (c == 1) {
      C1 = C1 + 1;
    }
    if (c == 2) {
      C2 = C2 + 1;
    }
    if (c == 3) {
      C3 = C3 + 1;
    }
    if (c == 4) {
      C4 = C4 + 1;
    }
    if (c == 5) {
      C5 = C5 + 1;
    }
    if (c == 6) {
      C6 = C6 + 1;
    }
    if (c == 7) {
      C7 = C7 + 1;
    }
    if (c == 8) {
      C8 = C8 + 1;
    }
    if (c == 9) {
      C9 = C9 + 1;
    }
    if (c == 10) {
      C10 = C10 + 1;
    }
    if (c < 11 && c >= 0) {
      if (c >= 6) {
        conta = conta + 1;
        sumaa = sumaa + c;
      }
      if (c < 6) {
        contr = contr + 1;
      }
      sumag = sumag + c;
    }
  }
  porma = sumaa / conta;
  contt = conta + contr;
  promg = sumag / contt;

  print('La frecuencia de 0 es $C0');
  print('La frecuencia de 1 es $C1');
  print('La frecuencia de 2 es $C2');
  print('La frecuencia de 3 es $C3');
  print('La frecuencia de 4 es $C4');
  print('La frecuencia de 5 es $C5');
  print('La frecuencia de 6 es $C6');
  print('La frecuencia de 7 es $C7');
  print('La frecuencia de 8 es $C8');
  print('La frecuencia de 9 es $C9');
  print('La frecuencia de 10 es $C10');
  print('Cantidad de reprobados $contr');
  print('cantidad de aprobados $conta');
  print('promedio general $promg');
  print('promedio aprobados $porma');
}


#### 10.4 Prueba de escritorio
                
![image](https://user-images.githubusercontent.com/113472808/198409155-c7c90450-0cbc-44c8-91f9-49496bd4a17f.png)



#### 10.5 Entradas
5 4 7 7 8 9 4 10 10 10 
#### 10.5 Salidas
La frecuencia de 0 es 0
La frecuencia de 1 es 0
La frecuencia de 2 es 0
La frecuencia de 3 es 0
La frecuencia de 4 es 2
La frecuencia de 5 es 1
La frecuencia de 6 es 0
La frecuencia de 7 es 2
La frecuencia de 8 es 1
La frecuencia de 9 es 1
La frecuencia de 10 es 3
Cantidad de reprobados 3
cantidad de aprobados 7
promedio general 7.4
promedio aprobados 8.7

### Ejercicio 11. Captura 10 numeros enteros positivos y los ponga en un verctor, diga cual es mayor.
#### 11.1 Analisis
se requiere un vector de [10] para capturar N numeros hasta contar 10 positivos, de esos 10 compararlos para saber cual es mayor [1 2 3 4 5 65 6 7 8 40] 65
#### 11.2 Diagrama
![dfd11for](https://user-images.githubusercontent.com/113472808/198165097-466a6bbb-1a9b-4966-81b1-f25e6d64ed5e.png)
                
#### 11.3 Codigo
                
/*Diagrama que capture 10 numeros enteros positivos y los ponga en un vector
diga cual es mayor FOR*/

import 'dart:io';

void main() {
  var num = [];
  var mayor = 0;
  var menor = 0;
  for (var i = 0; i <= 9; i++) {
    int n = int.parse(stdin.readLineSync()!);
    if (n > 0) {
      num.add(n);
      if (n < 0) {
        print('el numero debe ser positivo');
        i = i - 1;
      }
    }
  }
  print(num);
  for (var i = 0; i <= 9; i++) {
    if (mayor < num[i]) {
      mayor = num[i];
    }
  }
  print('el numero mayor es $mayor');
  menor = mayor;
  for (var i = 0; i <= 9; i++) {
    if (menor > num[i]) {
      menor = num[i];
    }
  }
  print('el numero menor es $menor');
}


#### 11.4 Prueba de escritorio
  
![image](https://user-images.githubusercontent.com/113472808/198407761-654a0788-b11b-467e-9c44-b7c21f7283a8.png)
                
                
#### 11.5 Entradas
capturar los N numeros hasta tener 10 positivos 2 5 8 96 3 4 5 8 4 6 
#### 11.6 Salidas
[2, 5, 8, 96, 3, 4, 5, 8, 4, 6] Mayor es 96, el menor es 2

### Ejercicio 12. Obtener la distancia mayor de 2 numeros consecutivos en una lista de 10 vectores.
#### 12.1 Analisis
De una lista en un vector de 10 como por ejemplo [4 6 2 5 0 8 4 6 5 2] sacar su distancia y ver cual es mayor entre cada uno [2 4 3 5 8 4 2 1 3] la distancia mayor aqui seria 8
#### 12.2 Diagrama
![dfd12for](https://user-images.githubusercontent.com/113472808/198165127-f751b4a5-7ad2-400f-a298-d27faecb2784.png)
                
                
#### 12.3 Codigo
                
//obtener la distancia mayor de 2 numeros consecutivos en una lista de 10 vectores FOR
import 'dart:io';

void main() {
  var num = [];
  var d = [];
  var dis = 0;
  var mayor = 0;

  for (var i = 0; i <= 9; i++) {
    int n = int.parse(stdin.readLineSync()!);
    if (n < 0) {
      print('el numero no debe ser negativo');
      i = i--;
    }
    if (n > 0) {
      num.add(n);
    }
  }
  print('los numeros son $num');
  for (var i = 0; i < 9; i++) {
    dis = num[i] - num[i + 1];
    d.add(i);
    if (dis < 0) {
      d[i] = dis * -1;
    }
    if (dis > 0) {
      d[i] = dis;
    }
  }
  print('las distancias son $d');
  for (var i = 0; i < 9; i++) {
    if (mayor < d[i]) {
      mayor = d[i];
    }
  }
  print('la distacia mayor es $mayor');
}


#### 12.3 Prueba de escritorio
  
![image](https://user-images.githubusercontent.com/113472808/198406463-e2c6ea2e-3064-4ee4-997a-20b93848b972.png)
  
#### 12.4 Entradas
Almacenar los 10 numeros positivos [4 6 2 5 0 8 4 6 5 2] sacar las distacias y decir cual es mayor
#### 12.5 Salidas
[2 4 3 5 8 4 2 1 3] la distancia mayor es 8

### Ejercicio 13. Almacene en un array el resultado de una tabla de multiplicar (10 numeros)
#### 13.1 Analisis
Poner un numero "5" para sacar en un array de [10] su tabla de multiplicar, la multiplicacion en ascenso hasta 10. [5,10,15,20,25,30,35,40,45,50]
#### 13.2 Diagrama
![dfd13for](https://user-images.githubusercontent.com/113472808/198165156-4b06b734-fdad-4b51-a935-222e088e1955.png)
  
  
#### 13.3 Codigo
  
//Almacene en un vector el resultado de una tabla de multiplicar 10 numeros FOR
import 'dart:io';

void main() {
  var array = [];
  int n = int.parse(stdin.readLineSync()!);
  for (var i = 0; i < 11; i++) {
    array.add(i);
    array[i] = n * i;
  }
  print('$array');
}


#### 13.4 Prueba de escritorio
                         
![image](https://user-images.githubusercontent.com/113472808/198406537-3885a851-2c2d-4dac-b034-a49dd14999c1.png)
                         
#### 13.5 Entradas
Ingresar el numero para sacar su tabla de multiplicar 5
#### 13.6 Salidas
[5,10,15,20,25,30,35,40,45,50]

### Ejercicio 14. Imprimir el siguiente dibujo
### *
### **
### ***
### ****
### *****
#### 14.2 Analisis
Imprimir un * hasta que se completen 5 mientras vaya saltando una linea.
#### 14.2 Diagrama
![dfd14for](https://user-images.githubusercontent.com/113472808/198165170-fdf77ac5-635e-47ed-84ed-f1f24adbd61a.png)
                         
#### 14.3 Codigo
                         
#### /*escriba el siguiente dibujo
#### * 
#### **
#### ***
#### ****
#### *****
#### */
import 'dart:io';

void main() {
  var n = 5;
  for (var i = 0; i < 5; i++) {
    for (var j = 0; j <= i; j++) {
      stdout.write('*');
    }
    print('');
  }
}


#### 14.4 Prueba de escritorio
                          
![image](https://user-images.githubusercontent.com/113472808/198406618-3511e9fe-384c-44fb-8762-79d049550c03.png)


#### 14.5 Entradas
Ninguna, se imprime el * y va saliendo cada linea de *
#### 14.6 Salida
#### * 
#### **
#### ***
#### ****
#### *****


# FIN
