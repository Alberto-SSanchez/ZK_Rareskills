# Operador Binario (Binary Operator)

## Primero entendamos qué es un "conjunto" 

<<<<<<< HEAD
De una mseanera sencilla e informal, podríamos decir que un conjunto es un grupo de elementos que tienen algo en común. Por ejemplo: 
=======
De una manera sencilla e informal, podríamos decir que un conjunto es un grupo de elementos que tienen algo en común. Por ejemplo: 
>>>>>>> 84d7ec031c389f90a639b09d68183d74996d23ef

* Los alumnos de un grupo escolar -> {Pedro, Luis, MarÍa, Juan}. 
* Las letras del abecedario -> {a,b,c,d,…}. 
* Los números naturales (enteros positivos) -> {1,2,3,4…}. 

 

<<<<<<< HEAD
Ahora ya podemos enfocarnos en lo que un operador binario (binary operator) es. Utilizemos algunos ejemplos con el conjunto de numeros naturales {1,2,3,…,∞}. 

* Sí tomamos dos elementos del conjunto como 3 y 4; al sumarlos se obtiene 7 que también es un número natural. 
* Es decir, al aplicarle una operación a dos elementos del conjunto, obtenemos un elemento que también pertenece al conjunto. 
* Se puede decir que la suma es una "operación binaria"
=======
Ahora ya podemos enfocarnos en lo que un operador binario (binary operator) es. Utilizemos algunos ejemplos con el conjunto de numeros naturales ___N___ = {1,2,3,…,∞}. 

* Sí tomamos dos elementos del conjunto como 3 y 4; al sumarlos se obtiene 7 que también es un número natural. 
* Es decir, al aplicarle una operación a los elementos del conjunto, obtenemos un elemento que TAMBIÉN pertenece al conjunto. Esta es la característica principal de un operador binario.
* Se puede decir que la suma es una "operación binaria" para el conjunto de números naturales.
* Una operación binaria se denota con el símbolo "*", estrella/asterisco.
  
## Propiedades de los operadores binarios
Vamos a usar nuestro conjunto de números naturales ___N___ = {1,2,3,…,∞} para explicar los siguientes conceptos.  

**MAGMA  -> Operación Cerrada**  
Tal como lo vimos, al aplicar una operación a los elementos del conjunto, se obtiene como resultado un elemento que tambíen pertenece al conjunto. Esto significa que nuestro conjunto original es un MAGMA.  
$2+3=5$

**SEMIGRUPO -> Operación Asociativa**  
Un semigrupo es un MAGMA que tiene un operador _asociativo_. Los numeros se pueden _asociar/agrupar_ de diferente forma y el resultado es el mismo; por ejemplo, vamos a usar "op" como nuestro operador binario (que puede ser suma, multiplicación, etc.)  

- ($A$ $op$ $B$) $op$ $C = D$  -> $(2+3)+4=9$, primero sumamos dos numeros y a eso le sumamos un tercer número.
- $A$ $op$ $(B$ $op$ $C) = D$ -> $2 + (3+4) = 9$, a un primer número le sumamos el resultado de la suma de otros dos.

Otro ejemplo es la multiplicación
- $2\times(3\times4)=24$
- $(2\times3)\times4=24$  
 
Un ejemplo más es la opedración de _union_. Supongamos que tenemos tres subconjuntos de números naturales $A=$ {$1,2$}, $B=$ {$3, 4$} y $C=$ {$5, 6$}. La unión de conjuntos significa unir/juntar/combinar los conjuntos para obtener otro con todos los elementos combinados.
- $A \cup$($B\cup C$) $=$ A union (B union C) = {$1,2$} $\cup$ ({$3,4$} $\cup${$5,6$})= {$1,2,3,4,5,6$}   
- ($A\cup B$)$\cup C=$ (A union B) union C = ({$1,2$}$\cup${$3,4$}$\cup 5,6$) $=$ {$1,2,3,4,5,6,$}
- No importa como se asocien los subconjuntos, el resultado es el mismo.


**MONOIDE -> Operación con elemento Identidad**  
Un monoide es un SEMIGRUPO (que a su vez es un MAGMA) y que tiene un elemento _identidad_ (una especie de elemento NEUTRO); esto se entiende mejor con ejemplos:
- Para la suma el elemento identidad es el número $0$, ya que si sumamos el $0$ con cualquier otro número, el resultado es el número en sí -> $0+1=1$
- Para la multiplicación, cuál sería ese número que no altere el resultado?...  
El número es el $1$ -> $1\times3=3$
- Para la unión de conjuntos, el elemento identidad es el conjunto vacío {}, ya que por ejemplo {$1,2,3$}$\cup${}$=${$1,2,3$} 

**GRUPO -> Todos los anteriores**  
Un GRUPO  es todos los anteriores MAGMA -> SEMIGRUPO -> MONOIDE; pero además tiene una propiedad adicional que es el elemento _inverso_.  
Supongamos que $A$ es un número natural de nuestro conjunto, su elemento inverso se escribe como $A^{-1}$.  
* Podemos entender el elemento inverso como aquel que al aplicarlo al elemento original, nos da como resultado el elemento identidad
* Por ejemplo, sí la suma es nuestro operador binario, entonces tenemos que
$A+A^{-1}=0$ (recordemos que 0 es el elemento identidad de la suma). Es cierto esto?
- $A+X=0$, que valor tiene que tener X para que sea nuestro elemento inverso?... La respuesta es -1. Sí esto es cierto entonces $1+(-1) = 0$
- Para la multiplicación $A\times A^{-1}=1$ (1 es la identidad de la multiplicación)
- $3 \times Y = 1$, cuál es el valor de Y para que esto sea cierto?... La respuesta es $\frac{1}{3}$. Ya que $3 \times \frac{1}{3} = 1$

**GRUPO ABELIANO-> Un grupo con operador conmutativo**  
Esto se refiere básciamente a "El orden de los factores, no altera el producto" cuando hablamos de multiplicación O de "El orden de los sumandos, no altera la suma" cuando hablamos de suma.
- $3\times 4 = 4 \times 3 = 12$
- $3 + 4 = 4 + 3 = 7$
- $A \cup B = B \cup A$ -> {$1,2$}$\cup${$3,4$} $=$ {$3,4$}$\cup${$1,2$} $=$ {$1,2,3,4$}

Eso es todo, en resúmen yendo de lo genera a lo particular:
MAGMA -> SEMIGRUPO -> MONOIDE -> GRUPO -> GRUPO ABELIANO
>>>>>>> 84d7ec031c389f90a639b09d68183d74996d23ef
