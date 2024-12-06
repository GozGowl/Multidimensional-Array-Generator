**Generador de Array Multidimensionales (1D, 2D, 3D):** Clase para generar arrays de diferentes dimensiones basandose en las especificaciones del usuario utilizando el Scanner, mostrando en el terminal toda la estructura del array con cada direccion (index) y su respectivo valor. Aspectos del codigo:

**1 - Validacion de los inputs del usuario:**
- Los metodos `readArrayType()`, `readValueType()`, `readInteger()`, `readPositiveInteger()`, `readRandomRange()`, se encargan de comprobar y validar que los inputs son los correctos, de lo contrario, el output sera un mensaje de invalidacion y se tendran mas oportunidades para ingresar el input valido.
- Los valores ingresados pueden estar en minusculas o mayusculas (case-insensitive), y con espacios al principio o al final; los numeros enteros que se almacenaran en el array pueden ser negativos, positivos o a '0', con excepcion de los numeros al especificar la cantidad de valores (1D), filas, columnas y profundidad del array, los cuales deben ser mayores a '0'; en el rango de valores aleatorios el valor minimo no puede ser mayor que el valor maximo.
- **readArrayType()**:
  - Inputs validos: `1d, 2d, 3d`
  - Mensaje error: `Invalid array type. Enter '1d', '2d' or '3d'.`
- **readValueType()**:
  - Inputs validos: `random, custom`
  - Mensaje error: `Invalid value type. Enter 'random' or 'custom'.`
- **readInteger()**:
  - Inputs validos: `'int'`
  - Mensaje error: `Invalid value. Enter a  integer.`
- **readPositiveInteger()**:
  - Inputs validos: `'int > 0'`
  - Mensaje error: `Invalid value. Enter a positive integer greater than '0'.`
- **readRandomRange()**:
  - Inputs validos: `'int && (min <= max)'`
  - Mensaje error: `The maximum must be greater than or equal to the minimum.`
