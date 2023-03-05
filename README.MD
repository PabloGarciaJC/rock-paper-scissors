
# Piedra, Papel, Tijera

# Explicación

1. Se definen las variables rockBtn, paperBtn, scissorsBtn y result utilizando el método document.getElementById(), que se utiliza para acceder a los elementos HTML en la página a través de sus identificadores únicos.

2. Se define la función getComputerChoice(), que devuelve una opción aleatoria para la computadora a partir de una matriz de opciones usando el método Math.random() y Math.floor().

3. Se agregan eventos click a los botones rockBtn, paperBtn y scissorsBtn utilizando el método addEventListener(). Cada función de manejo de eventos obtiene el valor del botón que se hizo clic utilizando la propiedad target.id, llama a la función getComputerChoice() para obtener la opción de la computadora y luego llama a la función determineWinner() para determinar el resultado del juego. El resultado se muestra en el elemento result utilizando la propiedad textContent.

4. La función determineWinner() toma dos parámetros, userChoice y computerChoice, que representan las opciones elegidas por el usuario y la computadora, respectivamente. La función utiliza declaraciones if y else para comparar las opciones y determinar el resultado del juego, que se devuelve como una cadena de texto.

Demo: [https://master--dainty-twilight-a0700f.netlify.app/]

## Contáctame para más información o preguntas

| Redes Sociales  | Desarrollador de Aplicaciones Web |
| ------------- | ------------- |
| ![Facebook](https://pablogarciajc.com/wp-content/uploads/2023/02/facebook.png)   | **[@pablogarciajc](https://www.facebook.com/PabloGarciaJC)** |
| ![Facebook](https://pablogarciajc.com/wp-content/uploads/2023/02/linkedin.png)  | **[@pablogarciajc](https://www.linkedin.com/in/pablogarciajc/)**  |
| ![Facebook](https://pablogarciajc.com/wp-content/uploads/2023/02/web-icono.png)   | **[www.pablogarciajc.com](https://pablogarciajc.com/)**  |

"El buen trabajo es la solución de hoy.
Para construir el futuro del mañana".