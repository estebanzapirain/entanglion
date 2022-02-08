# Reglamento de Entanglion

> Un juego de IBM Research

**2 JUGADORES | 14 AÑOS Y MÁS | 45 MINUTOS**

Entanglion desafía tus habilidades de navegación espacial y planificación estratégica para explorar una nueva galaxia y reconstruir una computadora cuántica ancestral.

http://ibm.biz/entanglion

> 🤔 ¿Confundido acerca de una regla? Por favor mira la [errata](Errata.md) para clarificación de reglas y actualizaciUNOs del juego.

# ¡Bienvenido al universo cuántico, Capitán!

<img src="../images/bg.png" width="100%">

¡FelicitaciUNOs, tu capitán se ha retirado y te ha dejado a cargo de su empresa de transporte galáctico! Es hora de hacer algunas mejoras.

Por años, has estado obsesionado con rumores de una tecnología ancestral de computación cuántica que podría revolucionar el transporte de carga galáctico. ¡Si los rumores fueran ciertos, permitiría a tus naves calcular senderos en el hiperespacio en cuestión de segundos! Sólo hay un inconveniente: los ancestros desmantelaron su computadora cuántica por temor a que fuera demasiado poderosa, y dejaron los componentes desparramados entre los planetas de la fuertemente vigilada galaxia Entanglion.

Si quieres reconstruir esta increíble tecnología, tendrás que navegar tus naves a través de la galaxia Entanglion y evitar las defensas dejadas atrás por los ancestros. Las buenas noticias son que tu antiguo capitán te dejó suficiente dinero para equipar tus naves con los motores potenciados cuánticamente que necesitarás para ingresar a Entanglion. Las malas noticias son que, sin una computadora cuántica para guiarlos, estos motores pueden ser un poco... impredecibles.

¿Crees que estás listo para el desafío?

# Objetivo
Entanglion es un juego de mesa cooperativo diseñado para dos jugadores. El objetivo es reconstruir una computadora cuántica desarrollada por una raza ancestral. Trabaja junto a tu compañero de equipo para navegar las tres galaxias del universo cuántico - Centarious, Superious, y Entanglion - en una búsqueda para recolectar ocho componentes de computadora cuántica. ¡Ten cuidado de evitar ser detectao por los mecanismos de defensa planetarios que vigilan a los componentes!

# Conceptos de Juego
Entanglion fue diseñado para exponer a los jugadores a varios conceptos fundamentales de computación cuántica:

- **Qubits** son los bloques de construcción de la computación cuántica.
- **Superposición** es cuando un sistema cuántico puede existir en una combinación probabilística de múltiples estados a la vez.
- **Entrelazamiento** sucede cuando el estado de un qubit se correlaciona con el estado de otro qubit.
- **Medición** es el proceso de observar el valor clásico de un qubit.
- **Error** ocurre cuando el ruido aleatorio en un sistema cuántico perturba el valor medido de un qubit.

Entanglion además expone a los jugadores a los diferentes tipos de hardware y componentes de software involucrados en construir una computadora cuántica real.

Al final de este libro podrás encontrar discusión adicional de cómo Entanglion se relaciona con la computación cuántica real.

# Preparación del juego
1. **Despliega los tableros de juego y de naves espaciales**. Ubica el tablero de juego al cómodo alcance de cada jugador y distribuye los tableros de naves espaciales a cada jugador.
2. **Ubica los componentes cuánticos**. Baraja los componentes cuánticos y ubícalos boca arria en cada planeta de la galaxia Entanglion, uno por cada planeta.
3. **Baraja el mazo de cartas de motor**. Deja en un lado la carta PROBE y baraja las cartas de motor restantes. Ubica la carta PROBE boca abajo en el mazo de motor, luego ubica las restantes cartas de motor encima, boca abajo.
4. **Prepara la plataforma de eventos cuánticos**. Deja de la do la carta Barajada Cuántica y baraja las cartas de eventos restantes. Reparte tres cartas de eventos boca abajo sobre la plataforma de eventos cuánticos. Finalmente, ubica las restantes cartas de eventos boca abajo sobre la plataforma.
5. **Establece el nivel de detección inicial**. Ubica la ficha de nivel de detección en la escala de nivel de detección. Para un juego fácil, comienza con un nivel de detección de 1 o 2. Para un juego más desafiante, comienza con un nivel de detección de 3. Si el nivel de detección alcanza el nivel final (X) antes de que la computadora cuántica haya sido construida, el juego termina en una derrota.
6. **Determina el primer jugador**. Determina el primer jugador haciendo que cada jugador tire el dado Entanglion (de 8 lados). El jugador con el número más alto comienza. Vuelvan a tirar en el caso de un empate.
7. **Determina las posiciUNOs iniciales de las naves**. Comenzando con el primer jugador, tiren el dado Centarious para ubicar cada nave espacial (0 va a <span style="color: purple"> CERO </span>, 1 va a <span style="color: purple"> UNO </span>). Este proceso es equivalente a inicializar un sistema cuántico.
8. **Levanta las cartas de motor**. Comenzando con el primer jugador, cada jugador levanta tres cartas de motor en su mano. Las cartas de motor pueden dejarse boca arriba.

<img src="../images/setup.png" width="100%">

# Materiales

**Tableros**
- 1 tablero de juego
- 2 tableros de nave espacial
<img src="../images/board.png" width="40%">

**Cartas**
- 24 cartas de motor (8 H, 7 CNOT, 5 X, 3 SWAP, 1 PROBE)
<img src="../images/engine_cards.png" width="40%">

- 9 cartas de evento
<img src="../images/events.png" width="100%">

**Piezas**
- 1 ficha de nivel de detección
- 8 componentes cuánticos
<img src="../images/quantum_components.png" width="100%">

- 1 dado Centarious (púrpura binario d6)
- 1 dado Entanglion (amarillo d8)
- 2 fichas de nave espacial
<img src="../images/spaceship.png" width="20%">

**Reglamento**

# Cartas de motor
<img src="../images/engine_cards.png" width="60%">

Las cartas de motor son usadas para navegar tus naves porel universo cuántico. Las rutas de navegación están señaladas en el tablero de juego con la/s carta/s necesarias para atravesarlas (por ejemplo: "X/CNOT" significa que tanto X como CNOT pueden ser utilizadas para atravesar esa ruta). En algunos casos, sólo una nave espacial puede atravesar una ruta. Las cartas de motor pueden ser jugadas sin tener efecto cuando no se muestra una transición en el tablero.

**X**. X es utilizada para navegar entre <span style="color: purple"> CERO </span> y <span style="color: purple"> UNO </span> y en el interior de la galaxia Entanglion.

**H**. H es utilizada para viajar entre Centarious and Superious y en el interior de la galaxia Entanglion.

**SWAP**. Fuera de Entanglion, SWAP intercambia las posiciUNOs de las dos naves espaciales. Dentro de Entanglion, SWAP sólo transiciona las naves entre <span style="color: #facd4d"> OMEGA CERO </span> y <span style="color: #facd4d"> OMEGA TRES </span>.

**CNOT**. CNOT es utilizada para ingresar a la galaxia Entanglion y navegar en su interior. Además invierte la posición de tu nave espacial en Centarious, pero sólo cuando la otra nave está orbitando <span style="color: purple"> UNO </span>.

**PROBE**. ¡Cuando se levanta la carta PROBE, tus naves han sido descubiertas por una sonda defensiva ancestral! Tira el dado Entanglion. Si el resultado es menor a 4 (después de tomar en cuenta los efectos de los componentes cuánticos), incrementa el nivel de detección en uno. Sino, PROBE no tiene efecto. Descarta PROBEy levanta una carta de reemplazo de motor.

> Orienta a las cartas de motor en los espacios de control de motores de forma que las líneas en las cartas estén alineadas con la línea de tu nave espacial.

> Cuando el mazo de motor queda sin cartas, inmediatamente mezcla las cartas de motor en la pila de descarte para recargar el mazo de motor. Incluye la carta PROBE en la mezcla, no la coloques al fondo del mazo.

# Información general del turno

Realiza _una_ de las siguientes acciUNOs en tu turno.

1. **Navegar**. Juega una de las cartas de motor en control de motores para navegar alrededor de la galaxia, y levanta una carta de reemplazo. Sólo puedes jugar cartas de motor para tu propia nave.
2. **Intercambiar**. Descarta una carta de motor de tu mano y levanta una carta de reemplazo.
3. **Recobrar**. Tira el dado Entanglion para intentar recobrar un componente cuántico, si hay uno presente.
4. **Evento**. Juega una carta de evento de tu mano (si posees una).

> Los jugadores no pueden pasar sus turnos, deben realizar una de las acciUNOs detalladas arriba.

# Entrando y saliendo de Entanglion
Para poder entrar a Entanglion, una nave espacial necesita estar en Centarious y la otra en Superious. Sólo la nave en Centarious puede utilizar CNOT para ingresar a Entanglion. Las rutas de ingreso a Entanglion están representadas mediante líneas grises en el tablero de juego.

Nave líder (jugando la CNOT) | La otra nave | Destino
--- | --- | ---
<span style="color: purple"> CERO </span> | <span style="color: green"> MÁS </span> | <span style="color: #facd4d"> PHI MÁS </span>
<span style="color: purple"> CERO </span> | <span style="color: green"> MENOS </span> | <span style="color: #facd4d"> PHI MENOS </span>
<span style="color: purple"> UNO </span> | <span style="color: green"> MÁS </span> | <span style="color: #facd4d"> PSI MÁS </span>
<span style="color: purple"> UNO </span> | <span style="color: green"> MENOS </span> | <span style="color: #facd4d"> PSI MENOS </span>

También es posible salir de Entanglion utilizando CNOT cuando ambas naves están orbitando <span style="color: #facd4d"> PHI MÁS </span>, <span style="color: #facd4d"> PHI MENOS </span>, <span style="color: #facd4d"> PSI MÁS </span>, o <span style="color: #facd4d"> PSI MENOS </span>. La nave que juega la CNOT regresa a Centarious y la otra nave regresa a Superioues, a los planetas indicados con las líneas grises.

Ejemplo: Rubicon está orbitando <span style="color: purple"> CERO </span> y Mercurial está orbitando <span style="color: green"> MÁS </span>. Cuando Rubicon juega una CNOT, ambas naves se mueven a <span style="color: #facd4d"> PHI MÁS </span>.

> Fuera de Entanglion, las naves se mueven en forma independiente. Dentro de Entanglion, ambas naves siempre se mueven juntas, sin importar qué jugador juega una carta de motor.

<img src="../images/entering_entanglion.png" width="40%">

En <span style="color: #facd4d"> PHI MÁS </span>, cuando Rubicon juega CNOT, Rubicon se mueve a <span style="color: purple"> CERO </span> y Mercurial se mueve a <span style="color: green"> MÁS </span>.

<img src="../images/entering_entanglion2.png" width="40%">

# Nivel de Detección
El nivel de detección determina la dificultad de evadir exitosamente las defensas planetarias. La ficha de nivel de detección es utilizada para registrar el nivel de detección actual. Cuando la nave espacial de un jugador ha sido detectada por las defensas orbitales, o el equipo de exploración de un jugador ha sido detectado por las defensas terrestres, el nivel de detección se incrementa, facilitando que las defensas de los planetas detectan al jugador en el futuro. El juego termina cuando el nivel de detección llega al nivel final (designado con una X).

> El nivel de detección se incrementa en uno siempre que eres detectado por las defensas orbitales o terrestres de un planeta.

<img src="../images/detection_rate.png" width="40%">

# Defensas orbitales
Los planetas en Entanglion están protegidos por defensas orbitales que escanean naves que busquen tomar los componentes cuánticos escondidos en su interior. Es posible evadir estas defensas utilizando tus motores cuánticos. Si eres detectado, sin embargo, tu sistema de navigación tomará automáticamente maniobras evasivas y saltará a un planeta aleatorio del sistema Centarious. Este salto desencadena un evento cuántico.

**Cuando navegas a cualquier planeta dentro de Entanglion:** Tira el dado Entanglion. Si el resultado es mayor que el nivel de detección actual, las defensas orbitales han sido evadidas. Sino, realiza las siguientes acciones:

1. Tira el dado Centarious y mueve ambas naves al planeta indicado. Ambas naves saltan juntas.
2. Incrementa en uno el nivel de detección.
3. Toma una carta de evento cuántico y realiza la acción indicada.

> Los Qubits Físicos te permiten decidir en qué planetas de Centarious ubicar tus naves.

> La Programación Cuántica te permite puentear las defensas orbitales cuando un planeta no posee un componente cuántico.

> La carta de evento Túnel Cuántico te permite puentear defensas orbitales. Si juegas esta carta despues de entrar en la órbita de un planeta en Entanglion, no necesitas tirar el dado Entanglion para determinar si tus naves fueron detectadas por las defensas orbitales.

> Si ingresas a Entanglion a través de la carta Heisenberg, puedes ignorar las defensas orbitales.

> Si juegas una carta de motor que no transiciona a tus naves a un nuevo planeta en Entanglion, no necesitas volver a verificar si tus naves han sido detectadas.

# Componentes Cuánticos
Hay ocho componentes que los jugadores deben obtener para construir la computadora cuántica y ganar el juego, mostrados en cada uno de los tableros de nave espacial. ¡Cada componente además otorga una habilidad especial permanente u obstáculo a tu nave, así que debes armar estrategias con tu compañero de equipo para obtener los componentes en el orden óptimo!

> Los componentes cuánticos son mejoras permanentes a tu nave y alteran la jugabilidad por el resto de la partida.

<img src="../images/quantum_components.png" width="100%">

Cuando tus naves están orbitando un planeta con un componente cuántico, puedes enviar un equipo de exploración a la superficie del planeta para recuperarlo. Los componentes cuánticos son custodiados por defensas terrestres automatizadas que deben ser evadidas, de la misma forma que las defensas orbitales.

**Para realizar una misión de recuperación:** Tira el dado Entanglion. Si el resultado es mayor que el nivel de detección actual, recoge el componente y ubícalo en tu tablero de nave espacial. Sino, tu equipo de exploración fue detectado por las defensas terrestres: incrementa en uno el nivel de detección.

> Si tu equipo de exploración fracasa en recuperar un componente cuántico, tus naves se mantienen en órbita en el planeta actual. No necesitas realizar otra verificación de defensas orbitales en el próximo turno, a menos que navegues a otro planeta que posea defensas orbitales.

> La carta de evento Túnel Cuántico te permite puentear las defensas terrestres. Si juegas esta carta en el transcurso de tu turno, tu misión de recuperación es exitosa. No necesitas tirar el dado Entanglion para determinar si tu equipo de exploración fue detectado por las defensas terrestres; añade el componente cuántico a tu nave.

# Eventos cuánticos
¡Los motores cuánticos pueden ser impredecibles a veces! Una vez que todos los casilleros de control de motores se han llenado, realiza un evento cuántico al final de tu turno. Adicionalmente, realiza un evento cuántico siempre que has sido detectado por las defensas orbitales.

**Para realizar un evento cuántico:** Levanta una carta de evento y sigue las instrucciones. Quita todas las cartas de motor del tablero de juego y ponlas en la pila de descarte de motor.

> Cuando se levanta Mezcla Cuántica, vuelve a mezclar las cartas de evento cuántico siguiendo las instrucciones de la preparación del juego.

> En el caso de que tu nave haya sido detectada por las defensas orbitales en el mismo turno que se llenaron los seis casilleros de control de motores, realiza dos eventos cuánticos.

<img src="../images/events.png" width="100%">

# Fin del juego
Los jugadores inmediatamente ganan el juego cuando han recolectado los ocho componentes de la computadora cuántica. Los jugadores inmediatamente pierden el juego cuando el nivel de detección llega al máximo (X).

# Tu primer juego
Prepara el tablero de juego como se describe en Preparación. En esta partida, Mercurial (el jugador azul) comienza. Mercurial levanta tres cartas: X, H, y H. Rubicon levanta tres cartas: CNOT, SWAP, y X. Ambas naves comienzan en <span style="color: purple"> CERO </span>.

<img src="../images/first1.png" width="40%">

1. Mercurial juega una H para navegar a <span style="color: green"> MÁS </span>. Mercurial levanta una X como carta de reemplazo.

<img src="../images/first2.png" width="40%">

2.Rubicon juega CNOT para navegar ambas naves a <span style="color: #facd4d"> PHI MÁS </span>. Rubicon levanta una H como carta de reemplazo. Luego de arribar a un planeta en Entanglion, Rubicon debe tirar el dado Entanglion para evadir las defensas orbitales. Como el nivel de detección es 1, Rubicon necesita sacar un 2 o más. Rubicón tira el dado Entanglion y saca un 3, ¡justo lo suficiente para evadir ser detectada!

<img src="../images/first3.png" width="40%">
<img src="../images/first_detection.png" width="40%">

3. Mercurial decide recuperar las Compuertas Cuánticas presentes en <span style="color: #facd4d"> PHI MÁS </span>. Mercurial tira un 6, mucho más alto que el nivel de detección de 1, y recolecta exitosamente el componente.

<img src="../images/first4.png" width="40%">

4. Rubicon decide que el siguiente destino es span style="color: #facd4d"> OMEGA TWO </span> y juega una H para navegar ambas naves allí.

<img src="../images/first5.png" width="40%">

Rubicon tira el dado Entanglion y saca un 1. ¡Las naves han sido detectadas, así que deben retroceder! Rubicon saca un 1 en el dado Centarious, así que ambas naves deben retroceder a <span style="color: purple"> UNO </span>. Como han sido detectadas, el nivel de detección es incrementado en uno y un evento cuántico se activa. Rubicon levanta una carta de evento cuántico - Heisenberg - que podrá ser usada en un turno posterior.

<img src="../images/first5.png" width="40%">
<img src="../images/first_detection2.png" width="40%">

El juego continúa hasta qye Rubicon o Mercurial hayan recolectado todos los componentes cuánticos de Entanglion, o hasta que el nivel de detección alcance el nivel máximo.

# Cómo se relaciona Entanglion con la computación cuántica
Entanglion modela varios aspectos de una computadora cuántica de 2 qubits. Específicamente, las dos naves espaciales representan a dos qubits, y cada planeta de cada galaxia representa un estado distinto de estos qubits. Las cartas de motor representan las compuertas cuánticas usadas para transicionar los qubits entre los diferentes estados.

La galaxia Centarious representa a los estados clásicos 0 y 1, escritos en la "notación ket" como ⎢0 〉(<span style="color: purple"> CERO </span>) y ⎢1 〉(<span style="color: purple"> UNO </span>). La galaxia Superious representa los estados de superposición cuántica, conocidos como ⎢+ 〉(<span style="color: green"> MÁS </span>) y ⎢- 〉(<span style="color: green"> MENOS </span>). La galaxia Entanglion representa a los estados de entrelazamiento. Cuatro de los estados entrelazados, ⎢Ψ+ 〉(<span style="color: #facd4d"> PSI MÁS </span>), ⎢Ψ- 〉(<span style="color: #facd4d"> PSI MENOS </span>), ⎢Φ+ 〉(<span style="color: #facd4d"> PHI MÁS </span>), y ⎢Φ- 〉(<span style="color: #facd4d"> PHI MENOS </span>), son conocidos como los [estados Bell](https://en.wikipedia.org/wiki/Bell_state). Los otros estados entrelazados, que han sido etiquetados ⎢ω0 〉(<span style="color: #facd4d"> OMEGA CERO </span>) hasta ⎢ω3 〉(<span style="color: #facd4d"> OMEGA TRES </span>), son estados adicionales que son alcanzables a través de la operación combinada de las compuertas X, H, SWAP, y CNOT.

El requisito de que ambas naves deben moverse juntas dentro de Entanglion es el resultado de el hecho de que para los estados entrelazados, el estado del sistema es más complejo que una simple combinación de los estados de los qubits individuales. Esta es una de las mayores diferencias entre la mecánica cuántica y la física clásica.

## Cartas de motor
Las cartas de motor representan _algunas_ de las distintas compuertas lógicas cuánticas utilizadas por las computadoras cuánticas. 

<img src="../images/engine_cards.png" width="60%">

- **X**. La compuerta X invierte el valor de un qubit. Es también conocida como la compuerta de inversión de bit.
- **SWAP**. SWAP intercambia los valores de los dos qubits.
- **CNOT**. CNOT significa "Not Controlada". Necesita dos qubits para funcionar: un qubit es designado el "objetivo", que es invertido si el otro qubit, conocido como el "control", tiene un valor de 1.
- **H**. La compuerta Hadamard es utilizada para crear o colapsar la superposición. Es una de las compuertas más importantes en la computación cuántica.

## Componentes cuánticos
Los componentes cuánticos en Entanglion representan a los diferentes componentes físicos o lógicos necesarios para construir una computadora cuántica real.

- **Qubits físicos**. De la misma forma que los procesadores de las computadoras clásicas están implementados por medio de hardware de transistores, los procesadores cuánticos están implementados por hardware de qubits. Existen [varias formas distintas](https://en.wikipedia.org/wiki/Qubit#Physical_representation) en las que los ciéntificos están creando qubits físicos, incluyendo uniones de Josephson, trampas de iones, y puntos cuánticos.
- **Interconexión de qubits**. Los qubits deben estar físicamente conectados entre sí para volverse entrelazados.
- **Refrigerador de dilución**. Los qubits físicos deben ser mantenidos a temperaturas muy bajas - incluso más frías que el espacio exterior - para mantener su coherencia. Los refrigeradores de dilución son capaces de enfriar los qubits físicos a temperaturas tan bajas como 2 milikelvins.
- **Compuertas cuánticas**. En la computación clásicas, las compuertas lógicas como la AND, OR, NOT, y NAND son combinadas para crear computación de órdenes más altos. En la computación cuántica, las compuertas cuánticas como la X, CNOT, SWAP, y H son utilizadas para la computación.
- **Programación Cuántica**. Para mejorar la productividad de los programadores cuánticos, son necesarios los lenguajes de programación cuántica de alto nivel. Por ejemplo, [IBM OpenQASM](https://github.com/IBM/qiskit-openqasm) te permite programar una computadora cuántica mediante un lenguaje estilo ensamblador, y [IBM QISKit](https://qiskit.org) te permite programar una computadora cuántica en Python.
- **Corrección Cuántica de Errores**. Los qubits físicos experimentan ruido que puede causar que ocurran errores durante la medición. [La corrección cuántica de errores](https://en.wikipedia.org/wiki/Quantum_error_correction) es utilizada para corregir estos errores. La clave de la corrección cuántica de errores es usar múltiples qubits físicos para simular un qubit lógico.
- **Infraestructura de Control**. Las computadoras cuánticas necesitan una forma de medir el estado interno de un qubit. La infraestructura de control utiliza radiación de microondas para leer el estado de un qubit y digitalizarlo en un estado binario (0 o 1).
- **Blindaje Magnético**. Los qubits son extremadamente sensibles a campos magnéticos errantes. El blindaje magnético se asegura de que los qubits estén protegidos de fuentes externas de magnetismo.

## Cartas de eventos
Las cartas de eventos agregan elementos divertidos y aleatorios al juego. Algunas cartas de evento toman el nombre de gente que realizó contribuciones significativas al campo de la física cuántica y de la ciencia de la información cuántica, como Werner Heisenberg y Erwin Schrödinger. Una carta de evento es extra especial, en homenaje al investigador de IBM Charles Bennett, uno de los fundadores de la teoría de la información cuántica y un contribuidor clave al descubrimiento del efecto de teleportación cuántica. Otras cartas de evento toman el nombre de efectos cuánticos como la tunelización cuántica, los errores de inversión de bit, el colapso de la función de onda, y la "espeluznante acción a la distancia" de Einstein. ¡Alentamos a los jugadores curiosos a investigar esta gente y estos temas para conocer más de la física detrás de la información cuántica!

<img src="../images/events.png" width="100%">

## Defensas, medición, y error
El proceso de encontrar defensas orbitales al navegar la galaxia Entanglion es análogoa realizar una medición clásica (también conocida como una medición Z) sobre el estado cuántico. Adicionalmente, el acto de recolectar un componente cuántico es análogo a realizar una medición de entrelazamiento, también conocida como un [prueba de Bell](https://en.wikipedia.org/wiki/Bell_test_experiments). A veces, el ruido en el sistema cuántico no nos permite ver una medición confiable. Llamamos a esto error en la lectura. Los efectos del ruido y los errores son modelados a través del nivel de detección.

## Recursos adicionales
Recomendamos algunos recursos para aprender más acerca de computación cuántica.

- [IBM Q Experience Beginner's Guide](http://ibm.biz/qx-guide) by IBM Research
- [Q is for Quantum](http://a.co/iJbiNS8) by T. Rudolph
- [Quantum Computing for Computer Scientists](http://a.co/cCZBoS9) by N. Yanofsky and M. Mannucci
- [Quantum Computation and Quantum Information](http://a.co/coZAko8) by M. A. Nielsen and I. L. Chuang
- [Quantum Computer Science: An Introduction](http://a.co/iYdi4Bv) by N. D. Mermin
- [Quantum Computing Since Democritus](http://a.co/1HzDIgF) by S. Aaronson
