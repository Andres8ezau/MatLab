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
 _Se puede agregrar un numero n de condiciones si se agrega **elseif**_
  
     
    if (condición)
      <Declaración1>
        elseif (condicion2)
          <Declaración2>
            else
               <Declaracion3>
        
       end;
 
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
Termina la ejecución de un bucle __for o while__ . Las instrucciones del bucle después de que la instrucción __break__ no se ejecuten.
En bucles anidados, __break__ sólo sale del bucle en el que se produce. El control pasa a la instrucción que sigue al __end__ de dicho bucle.
## Continue
Se salta a la siguiente iteracion, cualquier declaracion remanente que se encuentre en el ciclo __for__ o __while__ no la ejecutara.

##Sentencia switch-case

Sirve para controlar el flujo del programa ya que permite un mecanismo
para escoger y ejecutar instrucciones deseadas de entre varios grupos
posibles.

    
      
      switch expresiòn
    case valor 1  
        %instrucciones
    case valor 2
        %instrucciones
    case valor N
    end;



La "expresiòn" es comparada con cada valor de uno de los casos, si
coincide ejecuta las instrucciones, una vez terminadas sale del switch, si
no conicide con ninguna termina la sentencia switch.
 ##Otherwise
Powered with GitHub by @Andres8ezau :octocat:
