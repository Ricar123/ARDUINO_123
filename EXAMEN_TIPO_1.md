## ALUMNO/A:_____________________________________GRUPO:______NOTA:____
## EXAMEN TIC_II. TEMA: "Introducción a la programación con Arduino". 2018-19
La puntuación máxima para esta prueba es de  [10 puntos].

# DADO EL SIGUIENTE CÓDIGO:

int LED=13; 

void setup() {

   pinMode(LED, OUTPUT);
   
}

void loop() {

  digitalWrite(LED, HIGH);  
  
  delay(1000);  
  
  digitalWrite(LED_BUILTIN, LOW); 
  
  delay(1000);   
  
}


# CRITERIO A: "Conocer y Entender" 	[2 Ptos.]
## P1.- Describa completamente una variable que se menciona en el código. 
[1]: ID y tipo de variable. 
[2]:  DES completa. Cómo  y para qué.  

# CRITERIO B: "Procesos. Saber hacer." 	[4 Ptos.]
## P2.- Describa, paso a paso, cómo funciona este código. (iniciación, configuración y proceso). 
[1]: Sólo cierta comprensión del proceso, no enumera paso a paso, sólo es una repetición del código y faltan pasos fundamentales. 
[2]:  Descripción lógica paso a paso usando la información del código pero carece de algunos detalles. 
[3]:  Descripción paso a paso detallada de cada una de las partes fundamentales (iniciación, configuración y proceso) 
[4]:  Descripción completa de todas las partes con desarrollos técnicos más allá del código.

# CRITERIO C: "Solución a un problema planteado. Analizar y Evaluar" 	[4 Ptos.]
## P3.-  Describa y evalúe UNA posible solución necesaria para que al presionar un pulsador, se  encienda un LED y al dejar de pulsarlo se encienda otro LED distinto (control utilizado).  
[1]:  ID qué tipo de control es necesario pero no lo DES. 
[2]:  ID y DES la solución utilizando pseudocódigo con  ciertos errores sintácticos.
[3]:  ID y DES usando un código perfecto.
[4]:  ID, DES y evalúa otras posibles soluciones. 
