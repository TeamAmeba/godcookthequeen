# God Cook the Queen

## 1.Introducción 

#### 1.1. Concepto del juego
God Cook the Queen es un Cooking Mama medieval competitvo. Dos jugadores se enfrentarán en un duelo de cocina para entretener y alimentar a la nobleza.

#### 1.2. Características principales
- Juego basado en minijuegos: Para muchas de las acciones que quiera hacer el jugador, se enfrentará a un minijuego muy sencillo, adaptado para ordenador y smartphone.
- Auténtica cocina medieval: Todos los escenarios, assets, ingredientes y recetas estarán completamente sacados del medievo español.
- Dificultad basada en recetas: Algunas recetas serán más difíciles que otras. Esto estará determinado por la complejidad de la receta, el número de ingredientes y la dificultad de los minijuegos que incluya.
- Competición indirecta: Cada jugador intentará ser el más rápido en completar la receta. Pero además, cuando supere un minijuego sin ningún error y más rápido que el otro jugador, le mandará un castigo que aumentará la dificultad del minijuego que esté realizando o vaya a realizar.

#### 1.3. Género
Pertenece al género de los simuladores.

#### 1.4. Público objetivo
Es un juego para todos los públicos. Las mecánicas son sencillas, perfectas para jugadores casuales. La clasificación Pegi será Pegi OK.

#### 1.5. Jugabilidad
El juego contará con tres partes bien diferenciadas:
- Selección de ingredientes: Después de haber elegido la receta a cocinar, lo primero que aparecerá frente al jugador será una mesa con los ingredientes necesarios. En esta pantalla se podrá seleccionar cualquier ingrediente, lo que llevará a un minijuego en el que se preparará ese ingrediente para dejarlo listo para añadirlo al plato o cocinarlo.
- Minijuegos: Cada ingrediente activará un minijuego sencillo que consistirá en la preparación de ese ingrediente. Puede ser cortar, amasar o mezclar. Estos minijuegos consistirán en realizar movimientos sencillos en el móvil conforme la pantalla los va pidiendo o, si se juega en ordenador, pulsar una serie de teclas o hacer movimientos con el ratón.
- Cocinar: Se podría contar como un minijuego más, pero la diferencia principal es que se verán todos los ingredientes preparados y el recipiente en el que se van a cocinar. El jugador deberá arrastrar cada ingrediente dentro del recipiente (u horno) para proceder a cocinarlo.

Estas tres partes contarán con una cámara estática, que mirará hacia la mesa de ingredientes o de cocina con un plano picado. En el caso de los ingredientes (minijuegos) se hará un zoom para que ocupen gran parte de la pantalla y la acción sea más clara.

#### 1.6. Estilo visual
Se utilizará una estética medieval, con colores grises y marrones, a excepción de los ingredientes que tendrán un aspecto mucho más llamativo, con colores saturados. Las principales técnicas que definen el estilo visual serán el low poly, texturas pintadas a mano y cell shading.

#### 1.7. Alcance
Se realizarán 2 recetas jugables, además de una que servirá de tutorial. Las recetas estarán completas y se podrán jugar de forma competitiva con otro jugador.

![alt text](http://www.aevi.org.es/web/wp-content/uploads/2015/12/pegi_ok.jpg)


#### 1.8. Reparto de roles
- Ángel: Arte 2D/3D
- Alberto: Programación
- Dani: Arte 2D/3D - Música y Sonido - Programación
- Juan: Game design - Programación
- Víctor: Web - Programación

## 2.Mecánicas de juego
#### 2.1. Jugabilidad
En la selección de ingredientes se hará tap o click sobre cualquier ingrediente para seleccionarlo y acceder a su minijuego. El orden será el que decida cada jugador. 
En los minijuegos se solicitará al jugador hacer ciertos movimientos con el dedo o ratón o pulsar ciertas teclas para realizar cada acción necesaria en la preparación del ingrediente. Después de seguir las instrucciones, el ingrediente estará preparado de repente (no habrá estados intermedios necesariamente). 
En la pantalla de cocinar, se mostrarán todos los ingredientes ya preparados y solo habrá que arrastrarlos hacia el horno o cacerola en la que se vaya a preparar y en algunos casos terminar la preparación con algún último minijuego. 

#### 2.2. Flujo de juego
En el menú principal, se permitirá conectarse con otro jugador o realizar el tutorial. Una vez conectados, tendrán una lista de recetas disponibles, cada una con una dificultad asociada.
Al elegir la receta (la misma para los dos), se cargará el juego y se mostrará una cuenta atrás, tras la cual comenzará la competición.
Cada jugador se encontrará con los ingredientes necesarios y podrá elegir el orden en el que realiza el minijuego de cada uno.
Cuando se hayan preparado todos los ingredientes, se pasará a la parte de cocinado. Finalmente, cuando un jugador complete la receta, ganará la partida. Se mostrará una pantalla de final, con la puntuación y dos opciones: volver al menú principal o seleccionar nueva receta.

#### 2.3. Personajes
El juego no cuenta con personajes como tal, ya que el jugador no ve ni la representación de su personaje ni la del oponente.

#### 2.4. Movimiento
No habrá movimiento.

#### 2.5. Controles
Los controles variarán según se juegue en ordenador o smartphone. Para mover los ingredientes se arrastrarán con el ratón o el dedo. Los minijuegos, en cambio variarán. En smartphone utilizarán tanto tap como swype, pero en ordenador utilizarán teclas y movimientos de ratón.

## 3.Interfaz 
A continuación se muestra el diseño de interfaz con las diferentes pantallas que forman el videojuego. Se muestra tanto las diferentes pantallas así como su conexión entre ellas a través de un diagrama de flujo. Posteriormente, se presentan los esquemas bocetados de cada una de ellas. Estos esquemas solo muestran una distribución de elementos a priori. Es el diseñador y artista el que debe darle estilo, imagenes y forma según los elementos con la que la componga. 

#### 3.1. Diagrama de flujo
En el siguiente diagrama se muestran las diversas pantallas y cómo se conectan entre sí:

![diagrama de flujo](https://github.com/TeamAmeba/bewarethecandykids/blob/master/img/diagramadeflujo.jpg)


#### 3.2 Pantallas de juego
A continuación se visualizan las pantallas de selección de ingredientes, de minijuego y de cocinar:

![ingredientes](https://github.com/TeamAmeba/godcookthequeen/blob/master/img/ingredientes.jpg "Ingredientes")
![minijuegos](https://github.com/TeamAmeba/godcookthequeen/blob/master/img/minijuego.jpg "Minijuego")
![cocinar](https://github.com/TeamAmeba/godcookthequeen/blob/master/img/cocinar.jpg "Cocinar")


#### 3.3 Pantalla de Título, Créditos y Ranking
La pantalla de resultados mostrará la puntuación del jugador, si ha ganado o perdido y el ranking TOP 10.

![pantalla titulo](https://github.com/TeamAmeba/godcookthequeen/blob/master/img/titulo.jpg "Pantalla de título")
![ranking](https://github.com/TeamAmeba/godcookthequeen/blob/master/img/ranking.jpg "Ranking")
![creditos](https://github.com/TeamAmeba/godcookthequeen/blob/master/img/creditos.jpg "Creditos")


## 4.Arte 
Es un videojuego de cocina multijugador que transcurre en la Edad Media. Al suceder en esta época, el juego contará con una paleta de colores grises y ocres, pero con colores ligeramente saturados y llamativos en los ingredientes para llamar la atención de todos los públicos. 

#### 4.1 Arte 2D 
Las imágenes estarán en formatos .jpeg ya que es el más indicado para trabajar en web. Asimismo cada una deberá pesar 100KB como máximo. 

##### Interfaz: 
Logo
- Habrá dos logos. Uno más minimalista y con un elemento representativo del juego (espada y batidor) y otro con las letras del título. 

GUI: 
- Puntero: Para la versión de web, el videojuego contará con un puntero con unos colores acordes a la temática.
- Indicadores de acción: Guían al jugador mostrándole cómo debe de realizar los movimientos en los ingredientes. Poseerán transparencias para no taparlos:
	- Flecha arriba
	- Flecha abajo
	- Flecha derecha
	- Flecha izquierda
	- Flecha circular
	- Indicador de toque
- Icono de utensilio: Se situará en una esquina de la pantalla y mostrará el utensilio que se está utilizando en ese momento.


Mensajes 
- Mensaje de “Bien Hecho”
- Mensaje de “Oh no…”: Cuando haces algo mal.
- Mensaje de comienzo: Da comienzo la partida
- Mensaje de final de partida
- Mensaje castigo recibido: Mensaje avisando de que vas a sufrir un castigo.
- Mensaje de tiempo récord.

Texturas:
- La textura de cada ingrediente
- Textura de recipientes, utensilios y lugar: olla, batidor, mesa, etc.
	
Escenario

- Vista cenital de la mesa en la que se preparan los ingredientes.
- Vista cenital de la mesa en la que se cocina. Poseerá:
- Fogones
- Horno de piedra

#### 4.2 Arte 3D 
Los modelos se realizarán en el entorno de desarrollo 3D Blender, guardándolos en formato .blend y convirtiéndolos posteriormente al formato adecuado para Unity si es necesario. El render final de los elementos tendrá un estilo cel shading, similar al del videojuego Okami. Los modelos serán:

Recipientes:
- Olla
- Alambique
- Sartén

Utensilios:
- Batidor
- Cuchillo
- Espada
- Cucharón

Ingredientes
- Zanahoria
- Arroz
- Queso
- Harina
- Huevo
- Cebolla
- Ajo
- Carne
- Setas
- Especias
- Apio
- Pescado
	
#### 4.3 Audio 
En el apartado musical contaremos con dos temas, ambos con melodías típicas medievales pero empleando técnicas modernas:
- Tema del menú principal: relajado, con un ritmo lento que funcione para que el jugador entre en situación en este mundo medieval.
- Tema in game: animado. El videojuego consiste en cocinar rápido, por lo que debe de ser un tema alegre y  que invite a pasarlo bien mientras se compite por ganar.

Efectos:
Trataremos de crear un ambiente sonoro realista y satisfactorio que responda a las acciones del jugador. Se recrearán por tanto sonidos de ingredientes siendo manipulados  así como de los utensilios que usemos.


## Anexo
#### Referencias artísticas
**Okami**
![alt text](https://www.instant-gaming.com/images/products/2297/screenshot/2297-5.jpg)

**Donut County**
![alt text](http://www.donutcounty.com/images/screenshots/dc_donutshop.png)

**BorderLands**
![alt text](http://blogs-images.forbes.com/insertcoin/files/2015/05/borderlands.jpg)


