# mtg-deck-creator

Va a ser una app con escaner, base de datos propia solo para las cartas escaneadas y el creador de mazos.
Tiene que tener un escaner que supongo que ira conectada a la API de magic, de la que tendremos los datos de la carta para que se pueda guardar en la base de datos (queda pendiente como añadir tambien el tipo de "sinergia" o "actividad" que tendría la carta escaneada).

Luego la aplicación en si tendrá una ventana con un editor de mazos, primero vamos ha hacer que trabaje con las cartas que tiene en la base de datos para crear mazos aleatorios o que al menos sean una sugerencia con las cartas escaneadas dado un input solapado (que puedas poner una o mas condiciones) que puede ser pues, color/es del mazo, tematica, curva de maná, estrategia...

De momento obviamente no nos vamos a venir arriba y vamos a crear un sistema para mazos de 60, commander ya lo incluiremos si nos funciona esto, y luego también que a parte de solo mirar la base de datos sugiera cartas que no tengas tipo si quieres un mazo de goblins y no tienes suficientes goblins pues te sugiera cartas que no esten en la base de datos.

Que vamos a usar:

-Para la lógica del programa creo que conviene c++ o ruby (ruby es una opción flexible y rápida para crear un sistema, y c++ nos puede ayudar con la optimización de los algoritmos)

-Como base de datos seguramente una mySQL rápida, ya detallaremos más. Y la ORM también dependerá de la tecnología que utilicemos para la app, algo como Prima vendría bien.

-Para la app en sí, conozco react native que será un derivado para aplicaciones android del framework de react y supongo que será fácil de montar algo consistente y responsivo.

API de magic
https://docs.magicthegathering.io/
