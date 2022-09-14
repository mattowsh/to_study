# <a  href="https://www.python.org/"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1f/Python_logo_01.svg/800px-Python_logo_01.svg.png" alt="Python Language" width=4% heigth=4% ></img></a> Data Structures

## Data structures
- Maneras de ordenar y almacenar data/información
- Permiten un acceso eficiente a la data almacenada
- Existen diversos tipos, cada uno con eficiencias diferentes: se destacan las **inbuilt**

## Inbuilt data structures
**No tienen otras dependencias** más que las del propio core de Python: no es necesario el uso de librerias externas
- **Lists**
- **Tuples**
- **Sets**
- **Dictionary** (o *dicts*)

Son **one-dimensional data structures**: podemos guardar toda nuestra data en una sola linea o columna

Son **heterogeneas**: permiten almacenar data de diferente tipo (ej. int data type, float data type, range data type)

## LISTS: my_list = []
## TUPLES: my_tuple = ()
## SETS: my_set = {}
Tipo de datos almacenados:
- **UNSORTED**: los elementos no se encuentran ordenados, por lo tanto no pueden llamarse usando index o slicing (ej. [:-1])
- **UNIQUE**: ningún elemento se encuentra repetido, todos son unicos
- **INMMUTABLE**: los elementos y/o su contenido no pueden modificarse, sin embargo el set como tal sí es mutable (ej. add or remove elements)

Muy utilizados para cálculos matemáticos usando **operadores o métodos**:
- *Unión*: `(A | B) or A.union(B)`
- *Intersección*: `(A & B) or A.intersection(B)`
- *Diferencia*: `(A - B) or A.difference(B)`
- *Diferencia simétrica (= 1 - (A | B))*: `(A ^ B) or A.symmetric_difference(B)`

<!--- https://www.programiz.com/python-programming/set -->

## DICTS: my_dict = {}
Cada elemento tiene una **key asociada**: pares (key:value)

Tipo de datos almacenados:
- **UNSORTED**, por lo tanto, no pueden llamarse usando index o slicing pero sí haciendo alusión a su key
- elements **MUTABLES and can be REPEATED**
- keys **INMMUTABLES and UNIQUES**

  ### Dictionary Comprehension:
  Forma elegante y concisa de generar un nuevo dictionary a partir de un iterable, ej.:
  
    `squares = {x: x*x for x in range(6)}` or `odd_squares = {x: x*x for x in range(11) if x % 2 == 1}`
    
<!--- https://www.programiz.com/python-programming/dictionary -->

