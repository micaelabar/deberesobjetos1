# Soluciones y explicaciones.
## Dúo de colores de resistencia.
Las especificaciones establecen claramente que el programa debe generar un número de dos dígitos incluso si la entrada tiene más de dos colores, y el programa debe ignorar los colores adicionales después de los dos primeros.

Sin embargo, la implementación proporcionada solo toma los dos primeros colores de la entrada y genera un número basado únicamente en esos dos colores, ignorando por completo los colores adicionales.

Para superar este problema, es necesario ajustar la implementación para que ignore los colores adicionales después de los dos primeros colores y genere un número de dos dígitos basado únicamente en esos dos primeros colores.

------------------------------------------------------------------------------------------------------------
## Trío de colores de resistencia.
La problematización principal en este ejercicio es la correcta interpretación y manipulación de los colores de las bandas de la resistencia para calcular su valor en ohmios. Se requiere desarrollar un programa que tome tres colores como entrada y genere el valor correcto en ohmios. La dificultad radica en comprender cómo el tercer color representa la cantidad de ceros que deben agregarse al valor principal para obtener el valor en ohmios.

Para abordar esta problematización, necesitaríamos:

1. Interpretar los colores de las bandas de la resistencia y asignarles sus valores numéricos correspondientes según la codificación proporcionada.
2. Calcular el valor principal en ohmios basado en los dos primeros colores.
3. Determinar la cantidad de ceros que se deben agregar al valor principal, según el tercer color.
4. Convertir el valor principal y la cantidad de ceros en la unidad de medida apropiada (ohmios, kiloohmios, etc.).
5. Concatenar el valor calculado con la unidad de medida y devolverlo como resultado.
6. La implementación adecuada de este proceso asegurará que el programa cumpla con los requisitos establecidos y proporcione la salida esperada para diversas combinaciones de colores de resistencias.


## link del video: 
https://youtu.be/o2IJ22ReB7Q?si=LtUFN-1BcAs8gUXm


