

*Game Design Document*

**Hotline Miauami**

**Grupo 07:**

Adrián Espínola Gumiel 	[a.espinola.2022@alumnos.urjc.es](mailto:a.espinola.2022@alumnos.urjc.es) 		idarkar3000  
Antonio Machorro Herrera	[a.machorro.2024@alumnos.urjc.es](mailto:a.machorro.2024@alumnos.urjc.es) 		antonioMachorro  
Laura Manso Herrero 		[l.manso.2022@alumnos.urjc.es](mailto:l.manso.2022@alumnos.urjc.es)		laurimans  
David Antonio Paz Gullón	[da.paz.2022@alumnos.urjc.es](mailto:da.paz.2022@alumnos.urjc.es)		DavidPazUni  
Alvaro Rosa Pedraza 		[a.rosa.2022@alumnos.urjc.es](mailto:a.rosa.2022@alumnos.urjc.es)		alvaroRosa23

**ÍNDICE**

[**1\. Introducción	2**](#introducción)

[1.1. Concepto del juego	2](#concepto-del-juego)

[1.2. Género	2](#género)

[1.3. Características principales	2](#características-principales)

[1.4. Propósito	3](#propósito)

[1.5. Público objetivo	3](#público-objetivo)

[1.6. Estilo visual	4](#estilo-visual)

[**2\. Mecánicas de juego	4**](#mecánicas-de-juego)

[Estructura general	4](#estructura-general)

[Mecánicas de movimientos y habilidades	4](#mecánicas-de-movimientos-y-habilidades)

[Mecánicas de Escenario	5](#mecánicas-de-escenario)

[Bonificaciones y potenciadores	5](#bonificaciones-y-potenciadores)

[2.1. Flujo de juego	6](#flujo-de-juego)

[2.2. Controles	6](#controles)

[**3\. Interfaz	8**](#interfaz)

[3.1. Diagrama de estados	8](#diagrama-de-estados)

[3.2. Título	9](#título)

[3.3. Menú principal	9](#menú-principal)

[3.4. Menú Conexiones	10](#menú-conexiones)

[3.5. Menú Selección Roles	10](#menú-selección-roles)

[3.6. Partida	10](#partida)

[3.7. Resultados Ronda	11](#resultados-ronda)

[3.8. Pantalla Victoria Derrota	11](#pantalla-victoria-derrota)

[3.9. Menú Pausa	11](#menú-pausa)

[3.10. Ajustes	12](#ajustes)

[3.11. Créditos	12](#créditos)

[**4\. Arte	13**](#arte)

[4.1. Arte 2D	13](#arte-2d)

[4.2. Audio	15](#audio)

# 

1. # **Introducción** 

   1. ## **Concepto del juego**

*“Hotline Miauami”* es un juego multijugador de persecución 2D, donde un jugador asume el papel de "Policía" y el otro, el de "Ladrón". El objetivo del policía es atrapar al ladrón antes de que el tiempo se acabe, mientras que el del ladrón es evadir al policía y evitar ser atrapado dentro del tiempo establecido. El juego se desarrolla en un escenario 2D con plataformas, obstáculos y bonificaciones que pueden ser usados ​​para escapar, obstaculizar el paso o perjudicar al oponente.

2. ## **Género**

*“Hotline Miauami”* combina dos géneros clave: acción en tercera persona y plataformas 2D, creando una experiencia dinámica y competitiva en tiempo real.

- **Acción en tercera persona**: En este aspecto, el jugador tiene control total de su personaje desde una vista lateral, lo que le permite ver no solo a su propio personaje, sino también su entorno y la posición del oponente. Esta perspectiva añade un componente estratégico, ya que los jugadores pueden planificar sus movimientos mientras observan las rutas y los obstáculos en el nivel. La acción es rápida y fluida, y gracias al uso del temporizador se incita a los jugadores a tomar decisiones velozmente y bajo presión.

- **Plataformas 2D**: El uso de plataformas añade complejidad a la persecución. Los jugadores deben saltar, trepar y usar los elementos del entorno para avanzar, escapar o interceptar al oponente. Las plataformas están diseñadas para fomentar la habilidad y el ingenio, ya que el jugador que mejor maneje el terreno y los obstáculos tendrá una ventaja significativa. Los niveles incluirán múltiples rutas, alturas variables, y elementos móviles que crean un entorno dinámico y desafiante.

La fusión de estos dos géneros crea una jugabilidad rápida, competitiva y variada. Además, los objetos y bonificaciones presentes en los escenarios añaden aún más variedad al gameplay. Esto convierte cada partida en una experiencia única llena de emoción, tensión  y estrategia en tiempo real.

3. ## **Características principales** 

Las características principales del juego son:

* **Roles**:

  * **Policía**: Su objetivo es claro y directo: atrapar al ladrón antes de que el tiempo se acabe. El jugador en este rol debe ser estratégico en su persecución, anticiparse a los movimientos del ladrón y usar el terreno a su favor para acortar distancias y bloquear rutas de escape.

  * **Ladrón**: En contraste, el objetivo del ladrón es evadir al policía usando todas las herramientas disponibles en el entorno. El ladrón debe ser rápido, astuto y tener un buen conocimiento del terreno para aprovechar los obstáculos , haciendo que su rol se enfoque más en la evasión y el uso táctico del entorno.

* **Escenario estático con obstáculos**: Cada partida se desarrolla en un escenario estático en 2D, lo que significa que el mapa no cambia durante el transcurso de la partida. Sin embargo, el nivel está lleno de plataformas y obstáculos que hacen que el terreno sea variado y lleno de desafíos. 

* **Sistema victoria/derrota por rondas al mejor de tres**

* **Partida a contrarreloj:** Este mecanismo crea un ambiente tenso durante las partidas.

* **Bonificaciones por el escenario que perjudican al rival:** En el mapa aparecerán bonificaciones que, al ser recogidas podrán usarse para ganar ventaja o perjudicar al rival.


  4. ## **Propósito**

El propósito del juego es proporcionar una experiencia de juego rápida, intensa y divertida, centrada en la persecución y la evasión. Este juego fomenta la competencia entre dos jugadores. El juego está diseñado para ser accesible pero desafiante, permitiendo que los jugadores disfruten de sesiones cortas y emocionantes, con la posibilidad de partidas rápidas.

* **Entretenimiento competitivo**: Incentivar la competencia directa entre dos jugadores mediante habilidades y estrategias asimétricas.

* **Repetibilidad**: Ofrecer partidas cortas pero con una gran rejugabilidad.

* **Estrategia y agilidad**: Requiere destreza, reflejos rápidos y una buena lectura del entorno para evadir o capturar.

  5. ## **Público objetivo**

*“Hotline Miauami”* está orientado al siguiente público

* **Adolescentes y adultos jóvenes (13-35 años):**   
  El juego está diseñado para un público que disfrute de partidas rápidas y competitivas, ideal para aquellos que buscan diversión directa y multijugador inmediato.  
* **Jugadores ocasionales y competitivos:**

  * **Jugadores casuales:** Pueden disfrutar de mecánicas sencillas y partidas rápidas, lo que hace que sea fácil de aprender y empezar a jugar en poco tiempo.

  * **Jugadores competitivos:** Ofrece un equilibrio de habilidades y estrategias que pueden ser dominadas, lo que atrae a jugadores que buscan mejorar su destreza o desafiar a otros.

* **Amantes de los juegos multijugador:**  
  Ideal para personas que disfrutan de juegos **1v1 multijugador** locales o en línea, con un enfoque en la **acción rápida** y la competencia directa.

* **Jugadores en plataforma PC:**

  El juego se va a desarrollar para PC.

  6. ## **Estilo visual** 

“*Hotline Miauami”* tendrá un estilo visual **pixel art** que aportará un aspecto retro y nostálgico con toques modernos. Se ha elegido esta estética para poder crear una experiencia visual atractiva y con identidad,  lograr claridad visual y transmitir información rápidamente.

2. # **Mecánicas de juego** 

El juego se centra en la **persecución 1v1** en un escenario 2D con plataformas. Uno de los jugadores asumirá el rol de **Policía** y el otro el de **Ladrón.** Deberán utilizar el entorno, habilidades de su personaje y estrategia para cumplir con su objetivo: el Policía debe atrapar al Ladrón antes de que se acabe el tiempo, mientras que el Ladrón debe evadir al Policía.

### **Estructura general** 

* **Duración de la Partida:** Cada partida consta de 3 rondas, en las que los jugadores intercambiarán los roles. Cada ronda dura 2 minutos.

* **Roles Asimétricos:** Los jugadores se alternan entre ser Policía o Ladrón en diferentes rondas.

* **Escenarios Dinámicos:** Los escenarios cambian entre rondas, ofreciendo nuevos desafíos y rutas de escape.

### **Mecánicas de movimientos y habilidades** 

Cada rol tendrá sus propias mecánicas de movimiento y habilidades: 

* **Policía**  
  * **Velocidad:** El Policía tiene una velocidad menor que la del ladrón.

  * **Habilidad única:** El policía puede recoger objetos para perjudicar al ladrón.

  * **Condición de victoria:** Si el policía alcanza al ladrón antes de que termine la ronda, este lo atrapará y ganará.

* **Ladrón**

  * **Velocidad:** El Ladrón es más rápido que el Policía.

  * **Habilidad única:** El ladrón puede manipular el terreno, activando trampas y obstáculos para entorpecer al policía, además de caber por huecos por los que el policía no.

  * **Condición de victoria:** El ladrón deberá de evitar ser capturado toda la ronda para ganar.

### **Mecánicas de Escenario** 

Los escenarios 2D incluyen varias **plataformas** que los jugadores deben utilizar para ganar ventaja. Las plataformas son estáticas, con rutas verticales y horizontales para escapar o interceptar, y están inspiradas en la estructura de un laberinto.

En el nivel habrá **obstáculos interactivos**  como paredes y trampas que el ladrón puede usar para bloquear el camino o desviar al oponente.

* **Puertas cerradas:** Las puertas pueden cerrarse momentáneamente, bloqueando el camino.

* **Alcantarillas de transporte:** El ladrón puede utilizar alcantarillas que podrá utilizar para transportarse a otro punto del mapa. Estas alcantarillas tendrán 30 segundos de enfriamiento hasta que puedan volver a utilizarse.

![][image1]

Boceto Sección de mapa

### **Bonificaciones y potenciadores** 

En el escenario hay **bonificaciones** que aparecen de forma aleatoria cada 15 segundos y que el policía puede recoger para obtener ventajas temporales. Las habilidades son las siguientes:

* **Aumento de Velocidad:** Incrementa la velocidad del personaje temporalmente. La habilidad activa durará 5 segundos.  
* **Capa de Invisibilidad:** El policía puede volverse invisible por un tiempo corto, siendo difícil de ver para el ladrón. La habilidad activa durará 7.5 segundos.  
* **Red de Caza:** El Policía puede obtener una red para lanzar y ralentizar al Ladrón por unos segundos. La habilidad activa durará 1.5 segundos.

El policía tendrá guardada la bonificación, hasta que decida usarla. Solo puede tener una bonificación guardada, por lo que si ya tiene una no podrá recoger otra más hasta que la active.

1. ## **Flujo de juego** 

El jugador inicia el juego y elige Jugar Partida en el **menú principal**. El jugador elige si quiere jugar de forma **Local o En Línea**. El jugador establece conexión con el otro jugador, se eligen los roles y ambos aceptan comenzar la partida.

Se procede a explicar de forma detallada el flujo de una partida en *“Hotline Miauami”*. Al comenzar la partida, el temporizador de 2 minutos empezará a correr y ambos jugadores podrán controlar el movimiento de sus personajes, sean Ladrón o Policía.

Durante el transcurso de la partida, el Policía va a tener que intentar atrapar al Ladrón persiguiéndole por el mapa. Si obtiene una de las tres bonificaciones que saldrán de forma aleatoria por el mapa, guardará esa habilidad en su inventario y la podrá usar cuando quiera usando la tecla Espacio. Al activar la bonificación, el policía desencadenará un efecto con un límite de tiempo. El Ladrón va a poder interactuar con ciertas partes del mapa para cortar caminos al Policía e impedir ser capturado. 

Si el Policía logra capturar al Ladrón, la ronda terminará y se sumará 1 punto al marcador del Policía. Si el tiempo se acaba y el Policía aún no ha logrado capturar al Ladrón, se sumará un punto al marcador del ladrón. Cuando uno de los dos llegue a 2 puntos, la partida finalizará y obtendrá la victoria dicho jugador.

Cuando la partida termina, ambos jugadores podrán volver al menú principal.

2. ## **Controles** 

En el modo local, se usarán los siguientes controles:

* El Ladrón tiene los siguientes controles:

  * **A**: para moverse hacia la izquierda

  * **D**: para moverse hacia la derecha

  * **W**: para saltar

  * **S**: para deslizarse si está en movimiento, agacharse si está parado o bajar de plataforma

  * **Space**: para activar una trampa en el mapa

* El Policía tiene los siguientes controles propios:

  * **J**: para moverse hacia la izquierda

  * **L**: para moverse hacia la derecha

  * **W**: para saltar

  * **Shift derecho**: para activar la bonificación

En el modo en red, se usarán los siguientes controles:

* Ambos roles comparten:

  * **A**: para moverse hacia la izquierda

  * **D**: para moverse hacia la derecha

  * **W**: para saltar

* El Ladrón tiene los siguientes controles propios:

  * **S**: para deslizarse si está en movimiento, agacharse si está parado o bajar de plataforma

  * **Space**: para activar una trampa en el mapa

* El Policía tiene los siguientes controles propios:

  * **Space**: para activar la bonificación

3. # **Interfaz** 

Se ha realizado un diagrama de flujo para visualizar cómo será la navegación entre las pantallas del juego. Después, se detalla cómo será cada una de estas pantallas.

1. ## **Diagrama de estados** 

![][image2]

	

## 

2. ## **Título** 

   En el Título, únicamente aparecerá el logo del juego, una imagen de fondo y un texto que indica al jugador que tecla debe de pulsar para seguir.

![][image3]

3. ## **Menú principal** 

   En el menú principal, el jugador o jugadores podrán acceder a las opciones básicas del juego, incluyendo iniciar partida, modificar los ajustes y salir del juego.

   

   El menú principal contará con los siguientes botones:

   

* **Jugar:** Este botón lleva al jugador a la selección del modo de juego. Desde allí, se podrá escoger entre jugar de forma local o en red.


* **Opciones:** Al presionar este botón, el jugador accede al Menú de Ajustes, donde podrá modificar parámetros como el volumen general, volumen de efectos o volumen de la música.


* **Salir:** Este botón permite al jugador cerrar el juego. Se mostrará un mensaje de confirmación para evitar que el jugador cierre el juego por error.

  4. ## **Menú Conexiones** 

  En este menú los dispositivos se conectarán al servidor para buscar un rival. Todavía no tenemos claro con qué método se implementará esta función

  5. ## **Menú Selección Roles** 

  En esta pantalla, a cada jugador se le asignará el rol de Policía o el rol de ladrón de manera aleatoria.

![][image4]

6. ## **Partida** 

   En la pantalla de Partida es donde ocurrirá toda la acción. Los dos jugadores serán posicionados en el mapa, lejos el uno del otro. Tras un conteo de 3 segundos, ambos jugadores conseguirán el control de sus respectivos personajes para cumplir con su respectivo objetivo. En la interfaz, lo único que aparecerá será la cuenta atrás y la bonificación que tenga el policía.

   

![][image5]

7. ## **Resultados Ronda** 

   Al finalizar cada ronda, se mostrará una pantalla de Resultados de Ronda sencilla, que indicará de forma clara si el jugador ha ganado o perdido la ronda, y mostrará el contador. Esta pantalla servirá como transición rápida hacia el cambio de rol de los jugadores y a la siguiente ronda.

   

![][image6]

8. ## **Pantalla Victoria Derrota** 

   Cuando uno de los dos jugadores consigue ganar dos rondas, aparecerá esta pantalla. En ella se indicará qué jugador es el que ha ganado la partida.

   

![][image7]

9. ## **Menú Pausa** 

   Este menú flotante aparecerá cuando el jugador presione la tecla “ESC”, donde tendrá la opción de continuar, ir al menú de ajustes o de salir.

   

   En modo local, si uno de los dos jugadores presiona la tecla “ESC” se congelará el juego hasta que se pulse el botón de continuar.

   

   En el caso de que el modo de juego sea en red. Si uno de los dos jugadores pulsa la tecla “ESC”, el juego se congelará hasta que, o bien, el jugador presione el botón de continuar o pase 1 minuto.

   

![][image8]

10. ## **Ajustes** 

Desde este menú el jugador podrá regular el volumen del juego.

![][image9]

11. ## **Créditos** 

En la pantalla de créditos se despliega un fondo repleto de patrones geométricos en colores neón. La música synthwave continúa sonando, creando un ambiente intenso y envolvente que recuerda a la estética del juego.

En el centro de la pantalla, los créditos comienzan a aparecer en un formato vertical. Cada nombre está escrito en una tipografía pixelada, colorida y de neón.

Al final de la lista de créditos, un mensaje final se deslizará lentamente hacia el centro: “Gracias por jugar”, seguido de una animación donde el fondo estalla en colores brillantes cerrando así la escena.

4. # **Arte** 

   1. ## **Arte 2D** 

El arte de *“Hotline Miauami”* será pixel art de alta resolución y texturas sencillas, inspirado en el estilo de juegos como *The Binding of Isaac.* En cuanto al color, se usará una paleta de colores vivos e incluso neones, inspirada en la estética de juegos como *Hotline Miami.* El juego mantendrá la temática de animales, con un escenario estático inspirado en una granja o ciudad, pero añadiendo la ambientación y colores neones. 

**![][image10] 		![][image11]**

*The Binding of Isaac					Hotline Miami* 		

El personaje del policía, representado por la imagen de un cerdo, mantendrá la estética estereotipada del policía de las series y dibujos animados. Tendrá una baja forma física y un traje de policía apretado. Mientras que el ladrón, representado por un gato, tendrá una estética de bandido, con un cuerpo ágil y delgado y con una cinta en los ojos para ocultar el rostro. Similares a los animales de juego *Sly cooper*.

Imágenes de referencia

Concept Art Policia

![][image12]

Concept Art Ladrón

## 

2. ## **Audio** 

**Música** 

*“Hotline Miauami”* contará con música de **Persecución Synthwave (Retrowave) en 8-bit**

El **synthwave**, con sus sintetizadores melódicos, ritmos electrónicos y tonos nostálgicos de los años 80, es el núcleo de la banda sonora. Este estilo captura perfectamente el ambiente de persecución, con melodías energéticas y envolventes que transmiten una sensación de urgencia y emoción.

Para darle un toque único y retro, el synthwave se transforma en **8-bit**, evocando los sonidos característicos de las consolas clásicas de videojuegos.

**Indicadores auditivos durante la cuenta regresiva**

El aspecto de contrarreloj se refuerza con indicadores auditivos. A medida que el tiempo corre, se incorporan sonidos que aumentan de velocidad y el ritmo de la música conforme se acerca el final del tiempo. Esto genera más tensión para los jugadores, aumentando la presión en los momentos finales de la partida.

**Efectos de sonido**

Los efectos sonoros son esenciales para proporcionar retroalimentación al jugador. Están diseñados en un estilo retro 8-bit para complementar la estética de la música. Cada acción importante en el juego, como saltar, recoger bonificaciones, o activar trampas, está acompañada por efectos de sonido distintivos.

## 

