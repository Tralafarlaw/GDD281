# Indice

- [Indice](#indice)
- [Cambios](#cambios)
- [Introduccion](#introduccion)
  - [Concepto del juego](#concepto-del-juego)
  - [Caracteristicas principales](#caracteristicas-principales)
  - [Genero](#genero)
  - [Proposito y publico objetivo](#proposito-y-publico-objetivo)
  - [Jugabilidad](#jugabilidad)
  - [Estilo visual](#estilo-visual)
  - [Alcance](#alcance)
- [Mecánicas de juego](#mecánicas-de-juego)
  - [Jugabilidad](#jugabilidad-1)
    - [Modo introduccion](#modo-introduccion)
    - [Modo enjambre](#modo-enjambre)
    - [Modo suicida](#modo-suicida)
    - [Modo Homing *(moviéndose a sus posiciones iniciales en modo de enjambre)*](#modo-homing-moviéndose-a-sus-posiciones-iniciales-en-modo-de-enjambre)
  - [Flujo de juego](#flujo-de-juego)
    - [Cambios de nivel](#cambios-de-nivel)
    - [Muerte enemiga](#muerte-enemiga)
    - [Muerte del jugador](#muerte-del-jugador)
    - [Game Over](#game-over)
  - [Personajes](#personajes)
  - [Protagonista](#protagonista)
  - [Movimiento y fisicas](#movimiento-y-fisicas)
  - [Interaccion entre elementos](#interaccion-entre-elementos)
  - [Controles](#controles)
- [Interfaz](#interfaz)
  - [Diagrama de flujo](#diagrama-de-flujo)
  - [Menu principal](#menu-principal)
  - [Creditos](#creditos)
  - [Seleccion de perfil](#seleccion-de-perfil)
  - [Seleccion de nivel](#seleccion-de-nivel)
  - [Seleccion de habilidades](#seleccion-de-habilidades)
  - [Nivel](#nivel)
  - [Fin de nivel](#fin-de-nivel)
- [Arte](#arte)
- [Audio](#audio)

# Cambios


# Introduccion
Este es el documento de diseño de Galaga, un juego desarrollado en 1981 por la compañia **Namco**, el juego estuvo disponible para la plataforma **Arcade**, posteriormente fue lanzado para diferentes consolas como la **Nintendo Entertainment System (NES)**, la **Xbox Live**, la **Xbox 360**, la **Xbox One**, etc. lo que demuestra que el juego no pasa de moda. **Galaga** es la secuela del reconocido juego **Galaxian**, el cual años antes causó furor.
El objetivo del presente documento es plasmar los elementos que incluye **Galaga** y servir como carta de presentación.

## Concepto del juego
**Galaga** es un videojuego en el que controlamos una nave espacial equipada con un cañon, el objetivo es eliminar las distintas naves enemigas hasta quedarnos solos para asi poder pasar al siguiente nivel, en el cual la dificultad se vera incrementada.
Durante el juego tendremos que mover nuestra nave de izquierda a derecha, para esquivar tanto los misiles como los ataques de las naves enemigas. Contamos con un cañon que tiene una frecuencia de tiro limitada, por lo que tengamos que afinar más y más nuestra puntería conforme avanza el juego. No obstante, si dejamos que alguna de nuestras naves sea capturada por un jefe, tendremos la posibilidad de duplicar nuestro poder de disparo, siempre que recuperemos nuestra nave exitosamente.
El juego cuenta con un total de 255 niveles, incluyendo los ocho niveles diferentes de bonus o “Challenging Stages”, como se les denominan en el juego. Cada tres niveles convencionales, nos enfrentaremos a un nivel distinto de bonus.

## Caracteristicas principales
El juego se basa en los siguientes pilares:
   * **Planteamiento sencillo:** el objetivo del juego es muy simple, simplemente se requiere destruir las naves enemigas.
   * **Tactica:** mover la nave de izquierda a derecha, para esquivar tanto los misiles como los ataques de las naves enemigas, y con ayuda del cañon y nuestra punteria destruir las naves enemigas.
   * **Dinamismo:** **Galaga:** es un juego muy dinamico que muchas veces provoca en el jugador un sensacion de tención en el jugador.
   * **Aplicación:** **Galaga** debe ser ampliable para nuevos niveles como así también para nuevos poderes de los enemigos como poderes nuevos de la nave aliada como también se deberá poder añadir nuevos campos de fuegos. 
## Genero


## Proposito y publico objetivo
El objetivo de Galaga es anotar tantos puntos como sea posible mediante la destrucción de enemigos similares a insectos. El jugador controla un caza estelar que puede moverse a izquierda y derecha a lo largo de la parte inferior del campo de juego.

Galaga está dirigido a jugadores de un amplio rango de edades en la cual ya puedan usar sus instintos y sentidos de persepción del fuego como tambíen cuentan con un tiempo limitado que dedicar al ocio electrónico. Por ello, se apuesta por un sistema de partidas cortas y recompensas rápidas. 
La historia es sencilla, lo que permite poder jugar de forma esporádica.

## Jugabilidad
Obtienes 3 cazas estelares al principio del juego (puedes obtener más). Te mueves a la izquierda y a la derecha y puedes disparar teniendo un máximo de 2 balas en la pantalla al mismo tiempo. Si tu luchador es capturado por un Bossfighter, puedes matar al Bossfighter para recuperarlo, y luego lo hace se une con tu Caza Estelar actual para que tengas 2 cazas estelares a la vez y puedas disparar 2 balas a la vez (máximo 4).
El jugador tiene un caza estelar solitario en la parte inferior de la pantalla, que debe evitar que las fuerzas de Galaga destruyan a toda la humanidad. El objetivo de cada etapa es derrotar a todos los extraterrestres Galaga, que volarán en formación desde la parte superior y los lados de la pantalla. Al igual que Galaxian, los extraterrestres se lanzarán hacia el jugador mientras disparan proyectiles; colisionar con proyectiles o alienígenas resultará en la pérdida de una vida.
En unos niveles en encima de la formación enemiga hay unos grandes alienígenas conocidos como “Boss Galaga”, que necesitan dos disparos para destruir. Estos extraterrestres pueden usar un rayo tractor para capturar la nave del jugador, regresando con él a la parte superior de la formación y costándole una vida al jugador. Si quedan vidas adicionales, el jugador tiene la oportunidad de derribar al Boss Galaga que sostiene la nave capturada.

## Estilo visual
Galaga tendrá un estilo visual más asemejado al espacio con un fondo mas oscuro y detallado con partículas de un color claro que ayudará al jugador a poder distinguir los alienígenas como también los disparos tanto como del enemigo como también de casa estelar del jugador. El estilo visual es mas asemejado a los dibujos pixelados para que se pueda obtener una percepción mas clara de lo que es la colisión de las balas a los alienígenas como también de las balas de los alienígenas a la casa estelar. 

## Alcance
El objetivo principal de **Galaga** es desarrollar un sistema de juego sólido al que podamos introducirle contenidos sin
dificultad. En primera instancia se desarrollará un pack de contenidos básicos que será ampliado en un futuro.

# Mecánicas de juego


## Jugabilidad

### Modo introduccion

Hay 4 caminos que los enemigos siguen en todos los niveles, cuando acaban entra en modo homing.

**Nivel impar**

> 1er grupo
>
>> *camino 1* `[8, 9, 16, 17]`
>>
>> *camino 2*  `[25, 26, 35, 36]`
>>
> 2do grupo
> 
>> *camino 3* `[1, 7, 2, 10, 3, 15, 4, 18]`
>
> 3er grupo
> 
>> *camino 4* `[11, 6, 12, 5, 19, 14, 20, 13]`
>
> 4to grupo
>
>> *camino 2* `[27, 24, 28, 23, 37, 34, 38, 33`
>
> 5to grupo
>
>> *camino 1* `[29, 22, 30, 31, 39, 32, 40, 31]`
>

**Nivel Par**

> 1er grupo
>
>> *camino 1* `[8, 9, 16, 17]`
>>
>> *camino 2*  `[25, 26, 35, 36]`
>>
> 2do grupo
> 
>> *camino 3* `Hacia afuera (7, 10, 15, 18), Hacia adentro (1, 2, 3, 4)`
>
> 3er grupo
> 
>> *camino 4* `Hacia afuera (5, 6, 13, 14), Hacia adentro (11, 12, 19, 20)`
>
> 4to grupo
>
>> *camino 2* `Hacia afuera (27, 28, 37, 38), Hacia adentro (23, 24, 33, 34)`
>
> 5to grupo
>
>> *camino 1* `Hacia afuera (21, 22, 31, 32), Hacia adentro (29, 30, 39, 40)`
>

### Modo enjambre

Los enemigos van de arriba hacia abajo y las abejas de los costados salen de formacion y de manera aleatoria entran en mono suicidad

### Modo suicida

Las abejas azules se mueven hacia adelante y hacia atrás una cierta cantidad y se mueven hacia la parte inferior de la pantalla. Cuándo
llegan a la parte inferior, hacen un bucle y entran en el modo Homing. Las abejas rojas se mueven hacia adelante y hacia atrás hacia el centro de la pantalla. Cuando llegan al fondo,
aparece en la parte superior de la pantalla y entra en el modo de inicio. Las abejas jefes toman dos abejas rojas y hacen bucles hacia el centro de la pantalla mientras disparan balas. Todos los enemigos que atacan tienen una pequeña posibilidad de disparar balas al azar hacia abajo durante su ataque.Las abejas azules

### Modo Homing *(moviéndose a sus posiciones iniciales en modo de enjambre)*

Las abejas se mueven hacia sus posiciones de origen desde donde estaban antes y cuando han
llegado, se mueven en modo de enjambre.

## Flujo de juego

### Cambios de nivel

- Si no quedan enemigos en la pantalla, agregar 1 al contador de nivel
- Actualice la insignia en la interfaz de usuario.
- Genera el siguiente grupo de enemigos (se corresponde con el contador de nivel)

### Muerte enemiga

- Las abejas enemigas explotan al chocar con el jugador o la bala del jugador (la explosión dura 1 segundo)
- actualizar la puntuación
- El número de enemigos se resta en 1
- BossFighters (verde) pierden 1 vida y se vuelven azules


### Muerte del jugador

- La nave del jugador explota cuando es golpeada por un enemigo o bala. 
- Si (vidas> 0) Entonces actualice las vidas restantes, mueva todas enemigos de vuelta a sus posiciones de origen
- Pausa
- mostrar pantalla de "¿Listo?" durante 2 segundos
- Crea una nueva nave
- Continúa  el juego

### Game Over

Si no quedan más vidas.
- Mueve a todos los enemigos a sus posiciones iniciales
- Mostrar "JUEGO TERMINADO" por 2 segundos
- Luego vaya a la pantalla de resultados.


## Personajes

1. Boss fighters
   
   > 2 de salud
   > cambian color de verde a purpura
   > Puede robar  vidas al jugador

2. Red Bees
   
   > 1 de salud
   > color rojo/azul
   > 320 puntos en fase de inicio
   > 160 puntos en fase de enjambre

3. Blue Bees

   > 1 de salud
   > color azul/amarillo
   > 100 puntos en fase de inicio
   > 50 puntos en fase de enjambre

## Protagonista

Obtienes 3 vidas al inicio del juego (*puedes obtener mas*).

Te puedes mover de izquierda a derecha y puedes dispara un maximo de 2 balas en la pantalla al mismo tiempo

Si un Boss Fighter te roba una vida puedes recuperarla para obtener un compañero y asi tener un maximo de 4 balas en la pantalla al mismo tiempo.

## Movimiento y fisicas

> El jugador solo podra moverse de izquierda a derecha

## Interaccion entre elementos

> El jugador no podra salir de la pantalla

> Si el jugador chocha con un un enemigo o bala ambos quedan destruidos

> Si un enemigo sale de la pantalla regresara por el otro lado

## Controles

  > `<-` Izquierda
  
  > `->` Derecha

  > `X` Ataque

  > [`Enter`] Inicio / Pausa

# Interfaz
   

## Diagrama de flujo
El siguiente diagrama de estados muestra las pantallas presentes a lo largo de Galaga  y las transiciones
entre ellas. En puntos posteriores nos centraremos en ellas de forma individual.
![IMG-20160201-WA0003](https://user-images.githubusercontent.com/89058289/129837062-38a7a940-25e1-422a-b58b-0757c44ad254.jpg)

## Menu principal
Menú principal cuenta con dos opciones que son:
* Botón 1 PLAYER (un jugador) que al pulsar lleva al primer nivel del Galaga
* Botón 2 PLAYER (dos jugadores) que al pulsarlo lleva al primer jugador al primer nivel y una vez este muera lleva al segundo al primer nivel y asi susecivamnete al nivele que les corresponda por turnos de jugadores.
   Como se ve en la siguiente imagen:
   ![nes_galaga_1](https://user-images.githubusercontent.com/89058289/129838092-66ac8b01-0119-4cc0-a9c1-02baf7f1707e.jpg)
## Creditos
**Desarrollador:** Namco

**Editor:** Bandai América (NA), Namco (JP)


Los creditos se les puede encontrar en la siguiente imagen:
![nes_galaga_1](https://user-images.githubusercontent.com/89058289/129838092-66ac8b01-0119-4cc0-a9c1-02baf7f1707e.jpg)

## Seleccion de perfil
En la selección de perfil se puede apreciar que no consta de perfiles para escoger ya que es un fuego que no tiene autoguardado en la cual solo consta de dos perfiles prediseñados en la que pueden jugar dos fugadores o uno y que también al escoger unos de los dos modos de juegos ya sea de un jugador o dos es directamente dirigido al nivel 1 como se puede apreciar en el fuego Super Mario Bros.
Se puede apreciar en el siguiente enlace el modo de ingreso del juego:https://www.nintendo.es/Juegos/NES/Galaga--789285.html

## Seleccion de nivel
La seleción del nivel es de forma automática a medida que el jugador o los jugadores van matando a todos los alienígenas sin llegar a perder todas sus vidas en la que se puede constar que en cada nivele llega a ser mas dificil que la anterior ya que no se puede crear un perfil o aun guardado del nivel en la que se encuentra el jugador.
Como se puede apreciar en el siguiente video:https://www.youtube.com/watch?v=UPcO0HvIhkA&t=546s

## Seleccion de habilidades
Obtienes 3 cazas estelares al principio del juego (puedes obtener más).Teniendo un máximo de 2 balas en la pantalla al mismo tiempo. Si la casa estear es capturado por un Bossfighter, puedes matar al Bossfighter para recuperarlo, y luego lo hace se une con tu Caza Estelar actual para que tengas 2 cazas estelares a la vez y puedas disparar 2 balas a la vez (máximo 4).
Se puede apreciar en la siguiente imagen:https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTHqvyyopmr2qKMYigCXGDorrNSD6D2LZV6gaa6FCu3n71nHPMEr71Yvr8degn5hWC4pZ0&usqp=CAU
Cuando es retraido por el Bossfighter:https://www.gamespot.com/a/uploads/original/gamespot/images/2007/105/reviews/790450-938076_20070416_001.jpg
Cuando es recuperado el caza estelar:https://www.gamespot.com/a/uploads/original/gamespot/images/2007/105/reviews/790450-938076_20070416_001.jpg
## Nivel
Espacio de desplazamiento / fondo de estrella (píxeles coloridos generados en varias capas que se mueven a diferentes velocidades).

La interfaz de usuario se muestra a la derecha como una barra con los siguientes elementos:

*	"High Score" --> comienza en 30k (cuando la puntuación del jugador la supera, se actualiza)
*	"Score" -->  1up / 2up (parpadean al jugar)
*	"Vidas" -->  Fotos de los cazas estelares restantes
*	"Nivel"-->  Imágenes de insignias de rango
Como se muestra en la siguiente imagen:https://i.ytimg.com/vi/UPcO0HvIhkA/hqdefault.jpg


## Fin de nivel
Las abejas enemigas explotan al colisionar con el jugador o la bala del jugador (la explosión dura 1 seg), las actualizaciones de puntuación, el número de enemigos de recuento resta 1.

Unhurt BossFighters (green) pierden 1 vida &se convierten en blue  Player Death

La nave del jugador explota cuando es alcanzada por una bala enemiga o cualquier enemigo.

Si (vidas>0) Luego actualiza las vidas restantes, mueve a todos los enemigos de vuelta a sus posiciones de origen, pausa, muestra la pantalla "listo?" durante 2 segundos, haz una nueva nave y deja que el juego continúe como se ve en la siguinete imagen: https://oldgameshelf.com/roms/nes/galaga/images/upload-galaga-1573954570429.jpeg

Si no quedan más vidas, mueva a todos los enemigos de vuelta a sus posiciones de origen, muestre "GAME OVER" durante 2 segundos, luego vaya a la pantalla de resultados (derecha-->)
como muestra la siguiente imagen:https://www.gamesdatabase.org/Media/SYSTEM/Arcade/GameOver/big/Galaga_3_-_1984_-_Namco.jpg


# Arte
**Galaga** debe tener un fondo oscuro que sea más de tipo espacial para que se pueda apreciar las naves de los alienígenas con colores resaltantes como también la casa estelar del jugador es una nave espacial notoria con colores mas resaltantes y en lo cual estos colores deben ser llamativos al igual que las balas para que no pueda existir conflicto con el fondo oscuro 
Espacio de desplazamiento/fondo de estrella (generado)
Encontrado en (http://spritedatabase.net/file/10492)

# Audio
Clips de sonido encontrados (http://www.sounds-resource.com/arcade/galagaarrangement/sound/3665/)
(la mayoría estaban enprecisa)
Compró clips precisos de iTunes por $ 2
Haremos nuestros propios sonidos en bfxr.net para cualquiera que todavía falte.

