# Juego-Python-Cinquillo-2022-2023
## Proyecto en Python. Un juego de mesa

## OBJETIVO:

El objetivo principal de este proyecto en parejas es la creación de un juego de mesa en entorno de texto mediante la cooperación del equipo de desarrollo. Podemos jugar, siendo el resultado de ganar o perder partidas contra una “Inteligencia Artificial” básica.

El juego se llama Cinquillo. El cinquillo es un juego de cartas de baraja española (aunque también puede emplearse la francesa), en el que pueden jugar de 2 a 4 jugadores y el objetivo principal es ir colocando cartas sobre la mesa hasta quedarse sin ninguna, el ganador siendo el primero de todos los jugadores en quedarse sin cartas.

## PLANIFICACIÓN:

Dentro de la planificación se encontrarán los integrantes que se encargarán de realizar el proyecto, que en este caso somos Alba Caro Horcas y Celia Jiménez Forteza. El proyecto se divide en cuatro fases: la primera fase consiste en la investigación y desarrollo conceptual; después contramos la fase de traslado en entornos de programas; la tercera fase consiste en la codificación y creación de funciones, y finalmente encontramos la última fase, la fase de pruebas y correcciones de errores.

## INVESTIGACIÓN Y DESARROLLO CONCEPTUAL (IDC)

¿Qué vas a encontrar en la fase de investigación y desarrollo conceptual?

En esta fase, básicamente, lo que hemos hecho es buscar información sobre el funcionamiento del juego. Los datos que hemos buscado, los hemos utilizado para crear el pseudocódigo del programa y posteriormente presentarlo a la siguiente fase. Hemos identificado las reglas generales que componen el juego, y hemos hecho un esquema sobre los requisitos de usuario que se van a necesitar.

## TRASLADO A ENTORNOS DE PROGRAMAS (TEP)

¿Qué vas a encontrar en la fase de traslado a entornos de programas?

## CODIFICACIÓN Y CREACIÓN DE FUNCIONES (CCF)

¿Qué vas a encontrar en la fase de codificación y creación de funciones?

En esta fase, pasaremos el pseudocódigo a código y crearemos las funciones pertinentes con la especificación de cada regla.

## PRUEBAS Y CORRECCIONES DE ERRORES (PCE)

¿Qué vas a encontrar en la fase de pruebas y correcciones de errores?

Creación del documento IDC:

Cómo jugar al Cinquillo (juego de 2 a 4 personas):

## PREPARACIÓN

1.1 Se adquiere una baraja de cartas españolas.
1.2 Se sacan las cartas del sobre.
1.3 Se barajan las cartas.
1.4 Se reparten las cartas (dependiendo del número de jugadores).
1.5 Se saca la carta del triunfo (la dominante)
1.6 Se elige el primer turno de forma aleatoria
2 jugadores: Es posible elegir el número de cartas que se reparten en las opciones de mesa, a elegir de 10 a 15 cartas. El resto de cartas se quedarán en el mazo boca abajo para robar.
3 jugadores: Se reparten todas las cartas. Por sorteo, un jugador recibe 14 cartas y el resto de jugadores reciben 13. En las siguientes rondas, tendrá 14 cartas el jugador situado a la derecha del anterior.
4 jugadores: Se reparten todas las cartas, 10 por jugador.

## JUGAR A TURNOS

2.1 El juego lo empieza el jugador que posee el 5 de oros 
2.2 El siguiente jugador saca una carta de las que posee
2.3 Se comparan los valores y palos de esas dos cartas con la central
2.4 Las reglas del turno surgen efecto y se decide un ganador
2.5 El jugador que gana suma los puntos de las dos cartas tiradas
2.6 El jugador que gana el turno es el primero en coger una carta de la baraja
2.7 El jugador que ha ganado tiene el primer turno en la próxima jugada

## REGLAS DEL TURNO

En su turno el jugador puede: Abrir descarte / Seguir escalera / Pasar turno.

Abrir Descarte: El jugador coloca un 5 de cualquier pinta en uno de los espacios de descartes.
Seguir Escalera: El jugador puede colocar una carta de un número sucesor o antecesor a las que se encuentran en la mesa (siguiendo la escalera). Ej.: En la mesa se encuentra el 5 de oros y 5+6 copas; el jugador puede colocar una de las siguientes cartas: 4 de oros, 6 de oros, 4 de copas, 7 de copas.
Para hacer más visual que cartas se encuentran en la mesa, se aconseja colocar los 5 en el centro, arriba las cartas descendentes (4,3,2,1) y abajo las cartas ascendentes (6,7,S,C,R), de forma escalonada.
Pasar turno: Si el jugador no tiene carta para colocar en la mesa, debe pasar el turno.
Terminar el turno: Cuando el jugador juega una carta o pasa, termina su turno. El nuevo jugador activo es el de su izquierda (sentido horario).

## FINALIZACIÓN DE LA PARTIDA

La partida finaliza cuando a alguno de los jugadores se le acaban las cartas que tiene en la mano y gana el jugador que se quede antes sin cartas.
