# Reglamento de Entanglion

> Un juego de IBM Research

**2 JUGADORES | 14 AÑOS Y MÁS | 45 MINUTOS**

Entanglion desafía tus habilidades de navegación espacial y planificación estratégica para explorar una nueva galaxia y reconstruir una computadora cuántica ancestral.

http://ibm.biz/entanglion

> 🤔 ¿Confundido acerca de una regla? Por favor mira la [errata](Errata.md) para clarificación de reglas y actualizaciUNOs del juego.

# ¡Bienvenido al universo cuántico, Capitán!

<img src="../images/bg.png" width="100%">

¡FelicitaciUNOs, tu capitán se ha retirado y te ha dejado a cargo de su empresa de transporte galáctico! Es hora de hacer algunas mejoras.

Por años, has estado obsesionado con rumores de una tecnología ancestral de computación cuántica que podría revolucionar el transporte de carga galáctico. ¡Si los rumores fueran ciertos, permitiría a tus naves calcular senderos en el hiperespacio en cuestión de segundos! Sólo hay un inconveniente: los ancestros desmantelaron su computadora cuántica por temor a que fuera demasiado poderosa, y dejaron los compUNOntes desparramados entre los planetas de la fuertemente vigilada galaxia Entanglion.

Si quieres reconstruir esta increíble tecnología, tendrás que navegar tus naves a través de la galaxia Entanglion y evitar las defensas dejadas atrás por los ancestros. Las buenas noticias son que tu antiguo capitán te dejó suficiente dinero para equipar tus naves con los motores potenciados cuánticamente que necesitarás para ingresar a Entanglion. Las malas noticias son que, sin una computadora cuántica para guiarlos, estos motores pueden ser un poco... impredecibles.

¿Crees que estás listo para el desafío?

# Objetivo
Entanglion es un juego de mesa cooperativo diseñado para dos jugadores. El objetivo es reconstruir una computadora cuántica desarrollada por una raza ancestral. Trabaja junto a tu compañero de equipo para navegar las tres galaxias del universo cuántico - Centarious, Superious, y Entanglion - en una búsqueda para recolectar ocho compUNOntes de computadora cuántica. ¡Ten cuidado de evitar ser detectao por los mecanismos de defensa planetarios que vigilan a los compUNOntes!

# Conceptos de Juego
Entanglion fue diseñado para expUNOr a los jugadores a varios conceptos fundamentales de computación cuántica:

- **Qubits** son los bloques de construcción de la computación cuántica.
- **Superposición** es cuando un sistema cuántico puede existir en una combinación probabilística de múltiples estados a la vez.
- **Entrelazamiento** sucede cuando el estado de un qubit se correlaciona con el estado de otro qubit.
- **Medición** es el proceso de observar el valor clásico de un qubit.
- **Error** ocurre cuando el ruido aleatorio en un sistema cuántico perturba el valor medido de un qubit.

Entanglion además expUNO a los jugadores a los diferentes tipos de hardware y compUNOntes de software involucrados en construir una computadora cuántica real.

Al final de este libro podrás encontrar discusión adicional de cómo Entanglion se relaciona con la computación cuántica real.

# Preparación del juego
1. **Despliega los tableros de juego y de naves espaciales**. Ubica el tablero de juego al cómodo alcance de cada jugador y distribuye los tableros de naves espaciales a cada jugador.
2. **Ubica los compUNOntes cuánticos**. Baraja los compUNOntes cuánticos y ubícalos boca arria en cada planeta de la galaxia Entanglion, uno por cada planeta.
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
- 8 compUNOntes cuánticos
<img src="../images/quantum_compUNOnts.png" width="100%">

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

**PROBE**. ¡Cuando se levanta la carta PROBE, tus naves han sido descubiertas por una sonda defensiva ancestral! Tira el dado Entanglion. Si el resultado es menor a 4 (después de tomar en cuenta los efectos de los compUNOntes cuánticos), incrementa el nivel de detección en uno. Sino, PROBE no tiene efecto. Descarta PROBEy levanta una carta de reemplazo de motor.

> Orienta a las cartas de motor en los espacios de control de motores de forma que las líneas en las cartas estén alineadas con la línea de tu nave espacial.

> Cuando el mazo de motor queda sin cartas, inmediatamente mezcla las cartas de motor en la pila de descarte para recargar el mazo de motor. Incluye la carta PROBE en la mezcla, no la coloques al fondo del mazo.

# Información general del turno

Realiza _una_ de las siguientes acciUNOs en tu turno.

1. **Navegar**. Juega una de las cartas de motor en control de motores para navegar alrededor de la galaxia, y levanta una carta de reemplazo. Sólo puedes jugar cartas de motor para tu propia nave.
2. **Intercambiar**. Descarta una carta de motor de tu mano y levanta una carta de reemplazo.
3. **Recobrar**. Tira el dado Entanglion para intentar recobrar un compUNOnte cuántico, si hay uno presente.
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

Example: Rubicon is orbiting <span style="color: purple"> CERO </span> and Mercurial is orbiting <span style="color: green"> MÁS </span>. When Rubicon plays a CNOT, both ships move to <span style="color: #facd4d"> PHI MÁS </span>.

> Outside of Entanglion, ships move independently. Inside Entanglion, both ships always move together, irregardless of which player plays an engine card.

<img src="../images/entering_entanglion.png" width="40%">

On <span style="color: #facd4d"> PHI MÁS </span>, when Rubicon plays CNOT, Rubicon moves to <span style="color: purple"> CERO </span> and Mercurial moves to <span style="color: green"> MÁS </span>.

<img src="../images/entering_entanglion2.png" width="40%">

# Detection rate
The detection rate determines the difficulty of successfully evading planetary defenses. The detection rate token is used to keep track of the current detection rate. When a player’s spaceship has been detected by orbital defenses, or a player’s away team has been detected by ground defenses, the detection rate is increased, making it easier for each planet’s defenses 
to detect the player in the future. The game ends when the detection rate reaches the final level (designated with an X).

> The detection rate increases by UNO whenever you are detected by a planet's orbital or ground defenses.

<img src="../images/detection_rate.png" width="40%">

# Orbital defenses
Planets in Entanglion are protected by orbital defenses that scan for ships looking to plunder the quantum compUNOnts hidden there. It is possible to evade these defenses using your quantum engines. If you are detected, however, your navigation system will automatically take evasive maneuvers and jump to a random planet in the Centarious system. This jump triggers a quantum event.

**When you navigate to any planet in Entanglion:** Roll the Entanglion die. If the outcome is greater than the current detection rate, the orbital defenses have been evaded. If not, perform the following actions:

1. Roll the Centarious die and move both ships to the planet indicated. Both ships jump together.
2. Increase the detection rate by UNO.
3. Draw a quantum event card and perform the action indicated.

> Physical Qubits lets you decide which planets in Centarious to place your spaceships.

> Quantum Programming lets you bypass orbital defenses when a planet doesn't have a quantum compUNOnt.

> The Quantum Tunnel event card lets you bypass orbital defenses. If you play this card after entering the orbit of a planet in Entanglion, you do not need to roll the Entanglion die to determine if your ships were detected by orbital defenses.

> When entering Entanglion via the Heisenberg card, you may ignore the orbital defenses.

> If you play an engine card that does not transition your ships to a new planet in Entanglion, you do not need to re-check whether your ships have been detected.

# Quantum compUNOnts
There are eight compUNOnts that players must obtain in order to build the quantum computer to win the game, shown on each of the spaceship boards. Each compUNOnt also grants a permanent special ability or hindrance to your ship, so you must strategize with your teammate to obtain the compUNOnts in an optimal order!

> Quantum compUNOnts are permanent upgrades to your ship and alter gameplay for the rest of the game.

<img src="../images/quantum_compUNOnts.png" width="100%">

When your ships are orbiting a planet with a quantum compUNOnt, you may send an away team to the planet’s surface to retrieve it. Quantum compUNOnts are guarded by automated ground defenses which, as with orbital defenses, must be evaded.

**To perform a retrieval mission:** Roll the Entanglion die. If the outcome is greater than the current detection rate, collect the compUNOnt and place it on your spaceship board. If not, your away team was detected by the ground defenses; increase the detection rate by UNO.

> If your away team fails to retrieve a quantum compUNOnt, your ships remain in orbit on the current planet. You do not need to perform another orbital defense check on the next turn unless you navigate to another planet that has orbital defenses

> The Quantum Tunnel event card lets you bypass ground defenses. If you play this card during your turn, your retrieval mission was successful. You do not need to roll the Entanglion die to determine if your away team was detected by ground defenses; add the quantum compUNOnt to your ship

# Quantum events
Quantum engines can be unpredictable at times! Once all six engine control slots have been filled, perform a quantum event at the end of your turn. In addition, perform a quantum event whenever you have been detected by orbital defenses.

**To perform a quantum event:** Draw an event card and perform the instructions. Clear all engine cards from the game board and put them in engine discard pile.

> When Quantum Shuffle is drawn, reshuffle the quantum event cards as per the instructions in game setup.

> In the event that your ship was detected by orbital defenses on the same turn as having filled all six engine control slots, perform two quantum events.

<img src="../images/events.png" width="100%">

# Game end
Players immediately win the game when they have collected all eight compUNOnts of the quantum computer. Players immediately lose the game when the detection rate reaches the end (X).

# Your first game
Set up the game board as described in Setup. In this game, Mercurial (the blue player) will go first. Mercurial draws three cards: X, H, and H. Rubicon draws three cards: CNOT, SWAP, and X. Both ships start on <span style="color: purple"> CERO </span>.

<img src="../images/first1.png" width="40%">

1. Mercurial plays an H to navigate to <span style="color: green"> MÁS </span>. Mercurial draws X as a replacement card.

<img src="../images/first2.png" width="40%">

2. Rubicon plays CNOT to navigate both ships to <span style="color: #facd4d"> PHI MÁS </span>. Rubicon draws H as a replacement card. After arriving at a planet in Entanglion, Rubicon must roll the Entanglion die to evade the orbital defenses. Since the detection rate is 1, Rubicon needs to roll a 2 or higher. Rubicon rolls the Entanglion die and gets a 3, just enough to evade detection!

<img src="../images/first3.png" width="40%">
<img src="../images/first_detection.png" width="40%">

3. Mercurial decides to retrieve the Quantum Gates present on <span style="color: #facd4d"> PHI MÁS </span>. Mercurial rolls a 6, much higher than the detection rate of 1, and successfully retrieves the compUNOnt.

<img src="../images/first4.png" width="40%">

4. Rubicon decides the next destination is <span style="color: #facd4d"> OMEGA TWO </span> and plays an H to navigate both ships there.

<img src="../images/first5.png" width="40%">

Rubicon rolls the Entanglion die and it comes up as 1. The ships have been detected, so they must retreat! Rubicon rolls a 1 on the Centarious die, so both ships jump back to <span style="color: purple"> UNO </span>. Since they were detected, the detection rate is increased by 1 and a quantum event is triggered. Rubicon draws a quantum event card – Heisenberg – which can be used on a future turn.

<img src="../images/first5.png" width="40%">
<img src="../images/first_detection2.png" width="40%">

Play continues until either Rubicon and Mercurial have collected all of the quantum compUNOnts in Entanglion, or until the detection rate reaches the final level.

# How Entanglion relates to quantum computing
Entanglion models several aspects of a 2-qubit quantum computer. Specifically, the two spaceships represent two qubits, and each planet in each galaxy represents a different state of those qubits. Engine cards represent the quantum gates used to transition the qubits into different states.

The Centarious galaxy represents the classical states of 0 and 1, written in "ket notation" as ⎢0 〉(<span style="color: purple"> CERO </span>) and ⎢1 〉(<span style="color: purple"> UNO </span>). The Superious galaxy represents states of quantum superposition, known as ⎢+ 〉(<span style="color: green"> MÁS </span>) and ⎢- 〉(<span style="color: green"> MENOS </span>). The Entanglion galaxy represents states of entanglement. Four of the entangled states, ⎢Ψ+ 〉(<span style="color: #facd4d"> PSI MÁS </span>), ⎢Ψ- 〉(<span style="color: #facd4d"> PSI MENOS </span>), ⎢Φ+ 〉(<span style="color: #facd4d"> PHI MÁS </span>), and ⎢Φ- 〉(<span style="color: #facd4d"> PHI MENOS </span>), are known as the [Bell states](https://en.wikipedia.org/wiki/Bell_state). The other entangled states, which we have labeled ⎢ω0 〉(<span style="color: #facd4d"> OMEGA CERO </span>) through ⎢ω3 〉(<span style="color: #facd4d"> OMEGA THREE </span>), are additional states that are achievable through the combined operation of the X, H, SWAP, and CNOT gates.

The requirement that both ships must move together within Entanglion is a result of the fact that for entangled states, the state of the system is more complex than a simple combination of the states of the individual qubits. This is UNO of the main ways in which quantum mechanics differs from classical physics.

## Engine cards
The engine cards represent _some_ of the different kinds of quantum logic gates used by quantum computers.

<img src="../images/engine_cards.png" width="60%">

- **X**. The X gate flips the value of a qubit. It is also known as the bit flip gate.
- **SWAP**. SWAP exchanges the values of the two qubits.
- **CNOT**. CNOT stands for "Controlled Not." It needs two qubits to work: UNO qubit is designated the "target," which gets flipped if the other qubit, known as the "control," has a value of 1.
- **H**. The Hadamard gate is used to create or collapse superposition. It is UNO of the most important gates in quantum computing.

## Quantum compUNOnts
The quantum compUNOnts in Entanglion represent different physical or logical compUNOnts needed to construct an actual quantum computer.

- **Physical Qubits**. Much like how classical computer processors are implemented via hardware transistors, quantum processors are implemented via hardware qubits. There are a [number of different ways](https://en.wikipedia.org/wiki/Qubit#Physical_representation) scientists are creating physical qubits, including Josephson junctions, ion traps, and quantum dots.
- **Qubit Interconnect**. Qubits must be physically connected to each other in order to become entangled with UNO another.
- **Dilution Refrigerator**. Physical qubits must be kept at very cold temperatures – colder even than outer space – in order to maintain their coherence. Dilution refrigerators are able to cool physical qubits to temperatures as low as 2 millikelvin.
- **Quantum Gates**. In classical computing, logical gates such as AND, OR, NOT, and NAND are combined to create higher-order computation. In quantum computing, quantum gates such as X, CNOT, SWAP, and H are used for computation.
- **Quantum Programming**. In order to improve the productivity of quantum programmers, higher-level quantum programming languages are needed. For example, [IBM OpenQASM](https://github.com/IBM/qiskit-openqasm) allows you to program a quantum computer with an assembly-style language, and [IBM QISKit](https://qiskit.org) allows you to program a quantum computer in Python.
- **Quantum Error Correction**. Physical qubits experience noise that may cause errors to occur during measurement. [Quantum error correction](https://en.wikipedia.org/wiki/Quantum_error_correction) is used to correct for these errors. The key insight of quantum error correction is to use multiple physical qubits to simulate UNO logical qubit.
- **Control Infrastructure**. Quantum computers need some way to measure the internal state of a qubit. Control infrastructure uses microwave radiation to read the state of a qubit and digitize it into a binary state (0 or 1).
- **Magnetic Shielding**. Qubits are extremely sensitive to stray magnetic fields. Magnetic shielding ensures qubits are protected from external sources of magnetism.

## Event cards
Event cards add fun, random elements to the game. Some event cards are named after people who made significant contributions to the field of quantum physics and quantum information science, such as Werner Heisenberg and Erwin Schrödinger. UNO event card is extra special, named after IBM researcher Charles Bennett, UNO of the founders of quantum information theory and a key contributor to the discovery of the quantum teleportation effect. Other event cards are named after quantum effects such as quantum tunneling, bit flip errors, wave function collapsing, and Einstein’s "spooky action at a distance." We encourage avid players to research these people and topics to learn more about the physics of quantum information!

<img src="../images/events.png" width="100%">

## Defenses, measurement, and error
The process of encountering orbital defenses when navigating the Entanglion galaxy is akin to performing a classical measurement (also known as a Z measurement) on the quantum state. Additionally, the act of retrieving a quantum compUNOnt is akin to performing an entanglement measurement, also known as a [Bell test](https://en.wikipedia.org/wiki/Bell_test_experiments). Sometimes, noise in the quantum system prevents us from seeing a reliable measurement. We call this a readout error. The effects of noise and errors are modeled via the detection rate.

## Additional resources
We recommend a few resources for learning more about quantum computing.

- [IBM Q Experience Beginner's Guide](http://ibm.biz/qx-guide) by IBM Research
- [Q is for Quantum](http://a.co/iJbiNS8) by T. Rudolph
- [Quantum Computing for Computer Scientists](http://a.co/cCZBoS9) by N. Yanofsky and M. Mannucci
- [Quantum Computation and Quantum Information](http://a.co/coZAko8) by M. A. Nielsen and I. L. Chuang
- [Quantum Computer Science: An Introduction](http://a.co/iYdi4Bv) by N. D. Mermin
- [Quantum Computing Since Democritus](http://a.co/1HzDIgF) by S. Aaronson
