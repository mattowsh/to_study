# <a  href="https://www.python.org/"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1f/Python_logo_01.svg/800px-Python_logo_01.svg.png" alt="Python Language" width=4% heigth=4% ></img></a> Special functions: lambda, map, filter, reduce

## Lambda
- Sirve para crear funciones anónimas, sin nombre = **funciones desechables**
- Funcionan allí donde fueron creadas
- Puedo asignarles el nombre de una variable para poder trabajar con ellas: ej. `sum(2, 4)`
- Se potencia cuando se usa en conjunto con *map*

| Variable name | Función | Argumentos | Expresión ejecutable |
| -- | -- | -- | -- |
| sum = | lambda | x, y: | x + y |

## Map
- Toma 2 argumentos: `variable = map(func, seq)`
- Ejecutará la `func` con todos los valores en la `seq` (que pueden estar dentro de una lista o tuple)
- La `func` puede ser definida usando *lambda* previamente, o directamente como argumento 0 de *map*: ej.:

| Variable name | Retorno tipo + map | func | seq |
| -- | -- | -- | -- |
| square = | list(map( | lambda x: x\*x, | my_list) |

<!--- https://python-course.eu/advanced-python/lambda-filter-reduce-map.php -->
