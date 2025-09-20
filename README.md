# Juego del Pacman
El clásico juego de arcade de Pacman, programado desde la interface visual de Python. El código original fue obtenido del sitio Grant Jenks, pero era una versión muy básica y simple, por lo que en este repositorio hicimos varios cambios para volverlo más entretenido.
## Acerca del Código Base y su Funcionamiento
El juego de Pacman es uno que todos hemos jugado alguna vez en la vida y tiene una mecánica muy simple, se juega como pacman, el círculo amarillo en la pantalla que se controla con las flechas del teclado, el objetivo es recolectar los puntos en el camino sin ser atacado por un fantasma, los puntos rojos, si uno de estos te toca, pierdes. en esta versión original, los fantasmas son fáciles de evadir, pues son lentos y siguen caminos aleatorios.
## Cambios Realizados al Código Base
Para volver la dificultad del juego más alta, hicimos tres cambios al código original.
### Primer Cambio: Distinta Plantilla de Tablero
Modificamos un poco el tablero manipulando el arreglo en el que se encuentra guardado, para que la navegación sea más complicada.
### Segundo Cambio: Velocidad de Fantasmas
La velocidad de los fantasmas fue aumentada ligeramente para que sea más difícil escapar de ellos
### Tercer Cambio: Inteligencia de los Fantasmas
Ahora el curso de los fantasmas no es generado de manera aleatoria, sino que activamente buscarán el camino más corto hacia Pacman, lo que aumenta con creces la dificultad.
