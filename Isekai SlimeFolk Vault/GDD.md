

---

# Enviado de la Diosa - Documento de Diseño (v3.0)

## Visión General

**Género:** RPG / Deck Building / Sim de Citas / Gestión de Pueblo.

 **Premisa:** Eres una persona que vivió enferma toda su vida y murió joven. La última Diosa te revive para salvar un mundo moribundo sumido en la "Eterna Penumbra". Tu poder no es tuyo; proviene de la **Fe** que la gente tiene en ti.
 
RPG de gestión y Deck-Building con progresión horizontal. El poder del jugador emana de la **Fe** y la relación con los NPCs. Al alcanzar el máximo vínculo, el sistema se abre a una personalización profunda de habilidades (_Intercambio de Esencia_).

**Objetivo:** Convertir a los habitantes en súbditos de la Diosa. Sus corazones se convierten en tu poder (Summons). Vencer a los 6 Demonios y liberar a los 10 Dioses Hijos para restaurar el equilibrio.

---

## Lore y Estructura del Mundo

### La Creación (El Génesis)
*   **Origen:** Al principio existían la **Diosa de la Luz (Yang)** y el **Dios de la Oscuridad (Yin)**.
*   **Los Hijos:** Juntos crearon **10 Dioses Hijos** (5 de Luz, 5 de Oscuridad) y el mundo.

### El Cataclismo (El Cisma y el Retorno)
*   **La Guerra:** Las ideologías chocaron. La Luz ganó y desterró a la Oscuridad al **Vacío Abisal**.
*   **El Retorno:** Los Dioses Oscuros regresaron, corruptos por el rencor. En un intento desesperado por detenerlos, Los Dioses Hijos de la Luz utilizaron todo su poder, convirtiéndose en 5 torres mágicas enormes de energía, dedicadas a mantener encerrados a los dioses malignos, evitando que se propaguen y arrasen con el mundo. Sin embargo, las fuerzas malignas continuaron aumentando, desbordando las torres, las cuales a penas lograban contener su poder, teniendo que crecer hacia las alturas progresivamente para mantenerlos a raya. 
*   **El Rey Demonio:** El Dios de la Oscuridad se asentó en un **Volcán Gigante**, cubriendo el cielo de cenizas.

### El Estado Actual: La Eterna Penumbra
Los Dioses Hijos de la Luz han dejado a su gente desprotegida, al usar todo su poder en las torres. La gente ha perdido su fé. La flora se marchita. El cielo es gris. El mundo muere lentamente, permitiendo que El Rey Oscuro siembre tinieblas y tormento, matando a los seguidores de La Diosa de La Luz y condenandola al olvido.
*   **Tú:** Invocado por el último suspiro de la Diosa de la Luz. Eres el **Campeón de la Fe**.



---
## El Personaje Jugador (Protagonista)

Además de comandar Summons, el protagonista tiene sus propias estadísticas para interactuar con el mundo fuera del combate.

### Atributos Principales (Stats)
*   **Mente:** Influencia diálogos, labia y capacidad de convencimiento. (Sirve para los diálogos)
*   **Cuerpo:** Fuerza para mover objetos pesados y resistencia física. (Sirve para el sexo)
*   **Magia:** Mana y capacidad para usar hechizos fuera de combate (Sirve para el combate y mecánicas del juego).

Aumentar el stat de Cuerpo, permite prolongar cada vez más las escenas de sexo, desbloqueando diálogos / escenas extra.
Aumentar el stat de Mente mejora el trato de los NPC's hacia vos, desbloqueando más opciones.

Quiero crear algo de subir que sea facil, pero que tome un poco de tiempo, como que 
los stats van de 1 a 5, pero que subir 1 punto cueste un poco, pero que al tener varios summons al nivel maximo, puedas tener al personaje 5 en todo. no me interesa que sea muy dificil de maxear el juego, porque, de nuevo, es todo sobre una progresión horizontal, yo quiero que maxie las rutas, conozca los personajes, sea fácil de jugar la historia y las peleas sean el core.

Quizás podría armar mas adelante puzzles de cómo vencer a tal enemigo con estos poderes y así, para crear mas desafíos.

---
## Sistema de NPCs y Summons (El Motor del Juego)

Cada NPC tiene una vida en el pueblo, pero su fe proyecta un **Summon** que pelea contigo. Relación medida en **6 Corazones**.

### Tabla de Progresión del Summon

| Corazón  | Desbloqueo       | Efecto en el Summon                                                                                                                                                                                                                             |
| :------- | :--------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **❤️ 1** | **Despertar**    | Se une al equipo. Gana **1 Elemento Aleatorio** (de 5). Aprende 1er poder.                                                                                                                                                                      |
| **❤️ 2** | **Vínculo**      | Gana **2do Elemento Aleatorio**. Aprende 2do poder.                                                                                                                                                                                             |
| **❤️ 3** | **Evolución 1**  | Gana **3er Elemento Aleatorio**. Aprende 3er poder. <br>**Evoluciona** (Nuevo sprite, +Stats). <br>**1 Ranura de Runa** (Para equipar objetos). <br>                                                                                            |
| **❤️ 4** | **Maestría**     | Gana **4to Elemento Aleatorio**.  Gana una pasiva.                                                                                                                                                                                              |
| **❤️ 5** | **Omnielemento** | Gana el **5to y último Elemento**. Ahora domina todos los elementos comunes.Aprende 4to poder.                                                                                                                                                  |
| **❤️ 6** | **Fanatismo**    |  **2da Evolución** (Aspecto Divino/Demoníaco, ++Stats). <br> **2da Ranura de Runa** (Total: 2). <br> **Intercambio de Esencia:** Permite swappear elementos/pasivas con otros Nivel 6. <br> **Desbloqueo H:** Escena sexual y minijuego íntimo. |

### Reglas de los Summons
*   **Tipos:** Fijos al nacer (Atacante, Defensor, Soporte). No cambian.
*   **Elementos:** Aleatorios al subir de nivel. Al tener los 5 desbloqueados, **puedes cambiar libremente el elemento activo fuera de combate** para adaptarte a la misión.
*   **Intercambio:** Solo al Nivel 6 puedes cambiar los poderes.


---
## Sistema de Combate: 

El combate es por turnos con resolución basada en velocidad.

- **Formación:** 3 vs 3 unidades.
    
- **Targeting por Keywords:** * `Frente`: Objetivo en el mismo índice que el atacante.
    
    - `Izquierda/Derecha`: Objetivo en `índice ± 1`.
        
    - `AOE`: Afecta a toda la fila enemiga o aliada.
        
- **Modificadores Elementales:** Las habilidades son neutras, pero los Summons tienen un elemento seleccionado y sus habilidades escalan con el elemento activo del Summon (Fuego, Metal, Madera, Tierra, Agua, Luz, Oscuridad).

### El Libro de Monstruos (Gestor de Decks)
*   Comienzas con 3 slots de Summons, puedes desbloquear más (6 o 9 a definir).
*   **Composición de un Deck:**
    *   **3-9 Summons** (Las unidades que pelean).
    *   **6 Consumibles.**
    *   **6 Runas.**
    *   **6 Magias.**
*   **Mazo de Batalla:** Al entrar en pelea, las 18 cartas se mezclan en un solo mazo.

### Flujo del Combate (Turno a Turno)
1.  **Robo Inicial:** Robas **3 cartas**. Mantienes siempre 3 en mano.
2.  **Fase de Planificación (Obligatoria):**
    *  **Uso de Carta:** Puedes jugar una carta de tu mano de manera opcional, solo una por turno.
    *  Debes seleccionar una acción para cada uno de tus **3 Summons**.
    *  Presionas **PLAY**.
3.  **Fase de Resolución:**
    *   **Paso 1:** El jugador con prioridad resuelve primero su carta, luego el que no tenga prioridad resuelve la carta.
    * Paso 2: Se resuelven las acciones de los 6 personajes (3 tuyos + 3 enemigos) ordenados por **Velocidad** (del más rápido al más lento).
4.  **Fase de Descarte:** Puedes tirar cartas sobrantes que no quieras(Opcional).
5.  **Siguiente Turno:** Robas hasta tener 3 cartas de nuevo. El ciclo se repite.
6. El duelo termina cuando no quedan enemigos en pie o no queden aliados en pie.
7. Cada 3 turnos, todos pierden 10% de vida maxima y ganan 10% de daño para evitar duelos infinitos.

---
## Runas, Magias, Consumibles

### A. Runas
Los Summons tienen slots (Ranuras) para equiparse con poderosas runas que le permitiran tener modificaciones en sus poderes o elementos, o atributos durante el combate.
*    **Slots:** Si bien hay muchas runas en el mundo, para combatir solo tendras un minimo de 1 y un maximo de 6 slots para equipar estas runas a tu deck, de todas las que tengas.
*   **Tipos de runas:**
    *   Runa de Ataque.
    *   Runa de Defensa.
    *   Runa de Soporte.
*   *Nota:* Los Summons entran desarmados a la batalla; debes equiparlos en combate.
### B. Magias
El heroe ira ganando poderosas magias a lo largo del juego, que podrá conjurar fuera y dentro de combate para cambiar la realidad a su favor, pero esto consumirá mana.
*   **Slots:** Si bien hay muchas cartas magias en el mundo, para combatir solo tendras un minimo de 1 y un maximo de 6 slots para equipar estas magias a tu deck, de todas las que tengas.
*   *Nota:* Solo puede haber un efecto de escenario activo por combate a la vez, si se activa otro efecto de escenario, el nuevo remplaza al viejo.
### C. Consumibles
El héroe ira ganando objetos consumibles a lo largo del mundo, como pociones, comidas, bebidas, etc., que podrá darle a sus summons para que consuman en un combate o fuera del combate, pero al usarlos, estos items se consumen y deberas comprarlos de nuevo para poder tenerlos.(si tienen mas en el inventario se autorellena el slot de consumibles que configuraste)
*   **Slots:** Si bien hay muchos consumibles en el mundo, para combatir solo tendras un minimo de 1 y un maximo de 6 slots para elegir de tus consumibles y estos se usan inmediatamente al jugarlas.
*   *Nota:* Hay efectos de consumibles que se disparan inmediatamente consumidos y otros que tienen efectos de varios turnos.


---

## Progresión Horizontal (Endgame & PvP)

El objetivo es que al **Nivel 6 (Fanatismo)**, todos los Summons alcancen un **Base Stat Total (BST)** similar, haciendo que la estrategia supere al nivel numérico.

###  Intercambio de Esencia (Nivel 6)

- **Habilidades Extraíbles:** Los 4 slots de habilidades de un Summon se pueden vaciar y convertir en ítems de inventario (_Esencias_).
    
- **Habilidades Únicas:** La **Pasiva** de cada Summon es inamovible y define su identidad competitiva ligada al NPC.
    
- **Personalización:** Permite crear combinaciones de tipo competitivo (Ej: Un defensor con pasiva de tanque usando una habilidad de curación de un soporte).
    

---

## Gestión de Libros (UI/UX)

El acceso a la gestión se realiza mediante una interfaz de libros.

| **Libro**       | **Función Principal**  | **Contenido**                                                                                         |
| --------------- | ---------------------- | ----------------------------------------------------------------------------------------------------- |
| **Summon Book** | Gestión de Unidades    | Stats, Evoluciones, Cambio de Elemento, Equipamiento de Habilidades.                                  |
| **Runes Book**  | Equipamiento Pasivo    | 2 Slots (desbloqueados en ❤️3 y ❤️6) para objetos de ataque/defensa.                                  |
| **Heart Book**  | Relaciones y Social    | Progreso de NPCs, Info de NPC's (separados en dateables y no dateables), Log de diálogos y Galería H. |
| **Spell Book**  | Magia del Protagonista | Cartas que consumen Maná del jugador.                                                                 |
| **Bolsa**       | Consumibles            | Objetos de un solo uso para aplicar a Summons en combate.                                             |

---

##  Especificaciones para el MVP (6x6x2)

Para el primer prototipo funcional:

1. **6 NPCs:** Cada uno con su historia y tabla de gustos. (y lugar dónde suele estar, ej: "lo has encontrado en: ...)
    
2. **6 Summons:** Uno por cada NPC inicial.
    
3. **2 Evoluciones:** Placeholder visual para el despertar (❤️3) y la forma final (❤️6).
    
4. **Matemática Base:** Definir un BST de 300 puntos para el nivel máximo y testear el balance de las 5 interacciones elementales básicas.
    

---

## Artefactos (Poder Pasivo)
**Artefactos Comunes:** 
Se guardan en el inventario y otorgan beneficios globales.
**Artefactos Divinos (Clave para la Progresión):**
    *   Deben colocarse en el **Templo de la Diosa**.
    *   Al colocarlos, la Diosa recupera poder y te otorga **Habilidades de Campo** (Similar a los MO de Pokémon, aumento de stats o desbloquea mapas, etc).
    *   **Ejemplos:** Cruzar mares de lava, romper rocas gigantes, abrir puertas selladas, curar la corrupción del mapa.

---
## Elementos (El Ciclo)

### Lógica de las Interacciones (Para que tenga sentido)

Para que esta tabla funcione sin parecer al azar, aquí está el razonamiento detrás de cada elemento:

1. **🔥 Fuego:**
    
    - **Fuerte contra (2.0):** Metal (lo derrite) y Madera (la quema).
    - **Débil contra (0.5):** Agua (lo apaga) y Tierra (la tierra apaga el fuego por falta de oxígeno/lo ahoga).
2. **⛏️ Metal:**
    
    - **Fuerte contra (2.0):** Madera (la corta/hachazo) y Tierra (las herramientas de metal excavan la tierra).
    - **Débil contra (0.5):** Fuego (lo derrite) y Agua (el metal se oxida/hierve).
3. **🌳 Madera:**
    
    - **Fuerte contra (2.0):** Tierra (las raíces rompen la roca) y Agua (la madera absorbe el agua/la bebe).
    - **Débil contra (0.5):** Metal (las hachas cortan la madera) y Fuego (se quema).
4. **🪨 Tierra:**
    
    - **Fuerte contra (2.0):** Agua (la tierra absorbe el agua/barro) y Fuego (la tierra sofoca el fuego).
    - **Débil contra (0.5):** Madera (las raíces la rompen) y Metal (la pica rompe la piedra).
5. **🌊 Agua:**
    
    - **Fuerte contra (2.0):** Fuego (apaga) y Metal (oxida/hunde).
    - **Débil contra (0.5):** Tierra (la tierra bebe el agua) y Madera (la madera absorbe el agua).



| Atacante \ Defensor | **🔥 Fuego** | **⛏️ Metal** | **🌳 Madera** | **🪨 Tierra** | **🌊 Agua** | **✨ Luz** | **🌑 Osc** |
| :------------------ | :----------: | :----------: | :-----------: | :-----------: | :---------: | :-------: | :--------: |
| **🔥 Fuego**        |    ⚪ 1.0     |    🟢 2.0    |    🟢 2.0     |    🔴 0.5     |   🔴 0.5    |  🔴 0.5   |   🔴 0.5   |
| **⛏️ Metal**        |    🔴 0.5    |    ⚪ 1.0     |    🟢 2.0     |    🟢 2.0     |   🔴 0.5    |  🔴 0.5   |   🔴 0.5   |
| **🌳 Madera**       |    🔴 0.5    |    🔴 0.5    |     ⚪ 1.0     |    🟢 2.0     |   🟢 2.0    |  🔴 0.5   |   🔴 0.5   |
| **🪨 Tierra**       |    🟢 2.0    |    🔴 0.5    |    🔴 0.5     |     ⚪ 1.0     |   🟢 2.0    |  🔴 0.5   |   🔴 0.5   |
| **🌊 Agua**         |    🟢 2.0    |    🟢 2.0    |    🔴 0.5     |    🔴 0.5     |    ⚪ 1.0    |  🔴 0.5   |   🔴 0.5   |
| **✨ Luz**           |    🟢 2.0    |    🟢 2.0    |    🟢 2.0     |    🟢 2.0     |   🟢 2.0    |   ⚪ 1.0   |   🟢 2.0   |
| **🌑 Oscuridad**    |    🟢 2.0    |    🟢 2.0    |    🟢 2.0     |    🟢 2.0     |   🟢 2.0    |  🟢 2.0   |   ⚪ 1.0    |





![[EstrellaElemental.png]]
### Los 2 Elementos Especiales (Raros)
*   **✨ Luz (Sol/Yang):** De la Diosa y NPCs sagrados.
*   **🌑 Oscuridad (Luna/Yin):** Del Rey Demonio y enemigos redimidos.

Estos elementos no tienen desventajas contra ningún otro elemento salvo con su contra parte.
Oscuridad es débil contra Luz y Luz es débil contra Oscuridad, pero tienen ventaja contra todo lo elemental normal.


---

## Minijuegos y Actividades

1.  **Exploración y Mazmorras:** Buscar Artefactos y pelear monstruos(estilo aun por ver)
2.  **Minijuego de Relaciones (H-Scene):**
    *   Desbloqueado al Corazón 6.
    *   El jugador siempre podrá optar por saltar las HS si así lo desea.
    *   Animaciones QTE con botones y gestión de barras.
    *   **Mejoras:** Desbloqueas buffs sexuales (Resistencia mágica, Fuerza, Tamaño, etc.) que se aplican al minijuego y pasivamente al personaje con los **Artefactos**.
3.  **Minijuegos de Recompensa:**
    *   **🎣 Pesca (Estilo Aurelia):** Línea tensable con botones.
    *   **🃏 Cartas (Estilo Triple Triad):** Encontradas explorando.
    *   **🎈 Frozen Fruit / Balloons:** Plataforma y explosión.
    *   **⌨️ Typing Combat:** Escribir palabras para cargar la barra de victoria. (nota: pensar lógica, ej: practicando hechizos)
---

## Finales y Objetivos Finales

### El Final Normal
Destruyes al Rey Demonio y expulsas la oscuridad. El mundo se salva bajo la Luz eterna.

### El Final Verdadero: La Confluencia
Logras que la Luz y la Oscuridad vivan en armonía.
*   **Condición:** Convencer al Rey Demonio y salvar a todos los Dioses Hijos de la Luz sin matar a los Dioses Hijos de la Oscuridad.
*   **Recompensas (H):**
    *   **5 Summons de Luz:** De los dioses liberados.
    *   **5 Summons de Oscuridad:** De los demonios redimidos.
    *   **Romance Supremo:** Puedes ligar con el **Rey Demonio** (si salvaste a sus hijos) y con la **Diosa de la Luz** (si salvaste a los suyos).
    *   Requisito: Cumplir misiones difíciles específicas para cada Dios y llenar sus corazones.

---



## Notas de Implementación en Godot

### Sistema de Habilidades (Keywords)

Para los ataques de área o posición, se recomienda usar un sistema de **Bitmasks** o **Offsets**:

- `target_offset = [0]` (Frente)
    
- `target_offset = [-1, 0, 1]` (AOE)
    

### Gestión de Datos

- Usar `Resource` para cada `SummonData` y `AbilityData`.
    
- El `CombatManager` debe ser un Singleton que reciba el `Loadout` (3 Summons + 6 Runas + 6 Magias + 6 Consumibles) antes de cargar la escena de batalla.
    
