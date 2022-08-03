![LarnU](../_src/assets/00-PrimerosPasos/logo_LarnU.png)

<br>
<br>

# Desafío: JAVASCRIPT

## Instrucciones

Crear un nuevo archivo dentro de la carpeta `Clases` llamado `introduccion_js` donde deberás escribir a un costado los valores que tomaran los siguentes ejercicios:

6 / "3" = 2
El resultado lo divide ya que la primera variable es numerica y realiza la operación matemática

"2" * "3"
El resultado es 6 aunque las variables no son numericas explicitamente las reconoce al ejecutar

4 + 5 + "px" = 9px
Realiza la suma de las 2 variables numericas y concatena la variable px

"$" + 4 + 5 = $45
La primera es una variable no numerica por lo tanto llama a concatenar todos los elementos 

"4" - 2 = 2
Aunque no esta expresada la primera variable como numerica lo es por eso realiza la resta 

"4px" - 2 = Nan
la primera variable no es numerica no puede realizar la operacion y expresa NAN "not a number"

7 / 0 = Infinity
Cualquier numero dividio para cero da como resultado el infinito matematico

{}[0]
no lo entendi

parseInt("09") = 9
Si parseInt encuentra un carácter que no es un numeral de la base especificada, lo ignora a él y a todos los caracteres correctos siguientes, devolviendo el valor entero obtenido hasta ese punto.

5 && 2 = 2
Devuelve expr1 si se puede convertir a false; de lo contrario, devuelve expr2. Por lo tanto, cuando se usa con valores booleanos, && devuelve true si ambos operandos son true; de lo contrario, devuelve false.

2 && 5 = 5
Devuelve expr1 si se puede convertir a false; de lo contrario, devuelve expr2. Por lo tanto, cuando se usa con valores booleanos, && devuelve true si ambos operandos son true; de lo contrario, devuelve false.

5 || 0 = 5
0 || 5 = 5
Devuelve expr1 si se puede convertir a true; de lo contrario, devuelve expr2. Por lo tanto, cuando se usa con valores booleanos, || devuelve true si alguno de los operandos es true; si ambos son falsos, devuelve false


[3]+[3]-[10] = 23
concatena los 2 primeros valores y forma una nueva variable numerica la cual resta de la
ultima 

3>2>1 = false
3 es mayor a 2 pero resta y queda 1 lo cual no es mayor a 1 seria verdadero si queda 
3>2>=1


[] == ![] = False
Devuelve false si su único operando se puede convertir a true; de lo contrario, devuelve true.


Analiza cual sera el resultado de los console.log:

var profesor = "Jhoswe";
let teacher = "Jose";
if (true) {
    var profesor = "The Flash";
    let teacher = "Reverse Flash";
    console.log(profesor);
    console.log(teacher);
}
console.log(profesor); The Flash 
console.log(teacher);  Jose

El valor de var fue cambiado a the flash y este cambio es a nivel de windows 
lo que no sucede con let que su cambio es al nivel de la pagina al esta fuera del if traera el valor original de let y el valor cambiado a nivel de window en var