# __Operadores Lógicos__


| Operador      |  Definicion   |
| ------------- |:-------------:| 
| &&            | and           |
|     ( I )     | ( or)         |
| XOR           | Or Exclusivo  |

##  Operadores de relacion

| Operador      |  Definicion   |
| ------------- |:-------------:| 
| >             | Mayor que     |
| <             | Menor que     |
| >=            | Mayor o igual a  |
| <=            | Menor o igual a  |
| ==            | Igual a       |
| ~=            | Diferente de |

# __Ciclos en MATLAB__

## Instruccion _if-end_

   Si la ejecucion se cumple, se ejecutan las declaraciones hasta el *end* 
   si no lo cumple se salta el ciclo 
   
   
    if (condicion)
      <Declaración>
        end;
## Instrucción _if-end-else_ 
Si la primera *condicion* se cumple se ejecuta la **Declaracion1**, si no, se ejecuta la **Declaracion2**   
        
    if (condición)
      <Declaración1>
       else
        <Declaración2>
       end;
 _Se puede agregra otra condicion si se agrega **elseif**_
## instrucción _For_
  Este se ejecuta un cierto numero de veces asignadas      
        
        for (condicion) 
           <declaracion>
          end;
## Instrucción _While_
El ciclo *while* ejecuta repetidamente declaraciones mientras que una condición específica sea verdadera.
  
     while (condición)
          <Declaración>
         end;

## Break
Termina la ejecución de un bucle for o while . Las instrucciones del bucle después de que la instrucción break no se ejecuten.
En bucles anidados, break sólo sale del bucle en el que se produce. El control pasa a la instrucción que sigue al end de dicho bucle.

   
Powered with GitHub by @Andres8ezau :octocat:
