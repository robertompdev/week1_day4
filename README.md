# week1_day4

> JS | Data types: number and string
>
> JS | Data types: arrays
>
> JS | Conditionals and loops
>
> JS | Functions


## Main points: functions

A nivel de nomenclatura, existen:

- **Funciones nominales**: disponen de declaración e invocación, con alta reusabilidad.
- **Funciones anónimas**: no disponen de declaración, solo de invocación. Usadas en un único contexto.

A nivel de estructura, existen: 
- **Function statement**: disponen de al palabra reservada `function`, de paréntesis para sus parámetros y de bloque:
  ````javascript
  function getTotals(subtotal, tax){
    return subtotal + tax
  }
  ````
- **Arrow function**: carecen de la palabra reservada `function`, el paréntesis en sus parámetros es omitible frente a un único parámetro, y disponen una flecha previo a la apertura de su bloque (bloque omitible en funciones de una única instrucción).
  ````javascript
  const getTotals = (subtotal, tax) => subtotal + tax
  ````
Las funciones pueden recibir argumentos en forma de parámetros, y retornar datos. A efectos del retorno:
- Sólo pueden retornar un único valor,  `undefined` si carecen de retorno.
- Un retorno en una función supone detener su ejecución.
- Las _arrow function_ carentes de bloque disponen de retorno por defecto.

A efecto del alcance de variables:
- Las variables declaradas dentro de un bloque o función se denominan **locales** o **privadas**, accesibles únicamente dentro de ese contexto.
- Las variables declaradas fuera de cualquier bloque o función se denominan **privadas** o **públicas**, accesibles desde cualquier parte del script.

## Main points: string methods

- **`forEach()`**
- **`push()`**
- **`unshift()`**
- **`shift()`**
- **`pop()`**
- **`splice()`**


## Main points: array methods

- **`charAt()`**
- **`indexOf()`**
- **`lastIndexOf()`**
- **`repeat()`**
- **`substring()`**
- **`substr()`**
- **`slice()`**
- **`localCompare()`**
- **`splice()`**
