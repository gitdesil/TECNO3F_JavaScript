# TECNO3F_JavaScript
# Tarea Opcional N°1 - Tipos de datos y variables
# Ejercicio 1: Calculadora de Compras

Crea un programa que calcule el total de una compra, debe tener 3 variables con precios de productos
Una variable con la cantidad de dinero que tiene la persona Una variable con el total a pagar 
(la suma de los 3) Una variable con el vuelto (dinero que le sobra):

let producto1 = 1500;
let producto2 = 2000;
let producto3 = 1000;
let dinero = 6000;
let total = producto1+producto2+producto3

// Calcular el vuelto
let vuelto = dinero - total

// Mostrar resultados
console.log("Total a pagar: $" + total);
console.log("Tu vuelto es: $" + vuelto);

# Ejercicio 2: Ficha Personal
Crea un programa que Guarde en variables

Nombre: string
Edad: number

Cantidad de horas que destina a programar a la semana: number
Le gusta programar: booleano
Es mayor de edad: decide cual deberia ir aca
Luego debe IMPRIMIR TODO POR CONSOLA

let nombre = prompt("Ingresa tu nombre:");
let edad = Number(prompt("Ingresa tu edad:"));
let horasProgramacion = Number(prompt("¿Cuántas horas programás por semana?"));
let leGustaProgramar = confirm("¿Te gusta programar?");

// Determinar si es mayor de edad
let esMayorDeEdad = edad >= 18;

// Imprimir ficha personal
console.log("Nombre: " + nombre);
console.log("Edad: " + edad);
console.log("Horas de programacion: " + horasProgramacion);
console.log("Le gusta programar: " + leGustaProgramar);
console.log("Es mayor de edad: " + esMayorDeEdad);

# ANEXO: Paso a paso para realizar la actividad

## 1- En tu terminal, en una carpeta tarea-opcional-1 inicia un repositorio de git:
  git init
  git branch -M main
## 2- Realiza la actividad 1
## 3- Hace commit de la actividad 1 realizada con un mensaje claro:
  git add .
  git commit -m “mensaje”
## 4- Realiza la actividad 2
## 5- Hace el paso 3 pero con la actividad 2
## 6- Ve a github y crea un repositorio en tu cuenta para subir tu actividad
## 7- En tu terminal agrega un repositorio remoto: 
  git remote add
  origin <url-de-tu-repo>

8- Desde tu terminal, pushea los cambios. Deberian verse
reflejados en tu github (hace F5): git push origin main
