# Soluciones y explicaciones.
## Bob.
1. Función Principal: hey
2. **message.trim()**: Elimina los espacios en blanco al principio y al final del mensaje.
3. **isEmpty(message)**: Comprueba si el mensaje está vacío después de haber sido recortado.
 - Si está vacío, retorna 'Fine. Be that way!'.
4. **isAllCaps(message)**: Comprueba si el mensaje está en mayúsculas.
   - Si está en mayúsculas, se hace una segunda comprobación con isQuestion(message):
     - Si también es una pregunta, retorna 'Calm down, I know what I\'m doing!'.
     - Si no es una pregunta, retorna 'Whoa, chill out!'.
5.  *Si el mensaje no está en mayúsculas*, pero es una pregunta (isQuestion(message)):
   - Retorna 'Sure.'.
6. *Para cualquier otra cosa*, retorna 'Whatever.'.
---------------------------------------------------------------------------------
## Matrix.
1.  **Propiedades rows y columns**:
   - Ambas propiedades son matrices de matrices de números (number[][]).
   - Son readonly, lo que significa que no se pueden modificar después de la inicialización.
2. **Constructor constructor(text: string)**:
   - El constructor toma un string como argumento. Este string representa la matriz, con las filas separadas por saltos de línea (\n) y los elementos dentro de cada fila separados por espacios en blanco.
3.  **text.split('\n')**: Divide el texto en líneas, creando un array de cadenas, donde cada cadena representa una fila de la matriz.
4. **.map((row) => { return row.split(/\s+/).map(Number) })**: Itera sobre cada fila:
5.  **row.split(/\s+/)**: Divide la fila en elementos usando cualquier cantidad de espacios en blanco como delimitador.
6.  **.map(Number)**: Convierte cada elemento de la fila (que es un string) en un número.
El resultado es una matriz (rows) donde cada subarray representa una fila de números.
---------------------------------------------------------------------------------
## Link de video:
https://youtu.be/w-ihVb-sTN8


