# <a  href="https://www.python.org/"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1f/Python_logo_01.svg/800px-Python_logo_01.svg.png" alt="Python Language" width=4% heigth=4% ></img></a> Errors and exceptions

## Error vs. exceptions
**Errors**: problemas que surgen durante la ejecución de un programa que obligan a su detención

### Tipos de errores
- Syntax errores: falta de paréntesis, llamada incorrecta de variables, etc.
- Logical errors = **Exceptions**

**Exceptions**: se dan cuando, en un programa siendo ejecutado, ocurren eventos internos que cambian el flujo normal del programa. Son aquellos que **pasan las pruebas de sintaxis**

## Logical errors = Exceptions
`ZeroDivisionError` : aparece cuando trato de dividir cualquier número entre 0

`IdentationError` : aparece cuando existe una incorrecta identación

<div align="center">
	
<img width="303" alt="exceptions" src="https://user-images.githubusercontent.com/103126719/190436613-39685654-894e-48e3-b717-aafd1f9b904d.png">
	
</div>

Python Built-in exceptions: https://docs.python.org/3/library/exceptions.html#bltin-exceptions

## Error handling
### Método Try/Except/Finally
- `try:` escribimos el código en el que esperamos que pueda surgir un error
- `except:` escribimos el código a ejecutarse si llega a ocurrir un error en el bloque `try:`
- `else:` si no ocurre ninguna excepción previamente considerada en el bloque `except:` se ejecutará el bloque `else:`, no es obligatorio escribirlo siempre, lo uso en caso de ser necesario
- `finally` bloque de código que se va a ejecutar haya o no ocurrido un error en `try:`, siempre será ejecutado

### Otros
- `raise` : permite que una exception se de a la fuerza, se usa en conjunto con el método Try/Except/Finally

<!--- **bold // *italic // ``simil-code -->
