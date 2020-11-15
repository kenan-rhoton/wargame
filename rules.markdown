# Wargame (Versión 6)

## Tiradas

La mecánica base de tirada es sencilla: cada vez que se deba hacer una tirada, se lanzan 2 dados de 6 caras y se suman sus valores.
Un resultado de 7 o superior significa un acierto.
A esta tirada se le aplican los bonificadores y penalizadores pertinentes de la acción.

## Preparación

El Escenario identificará las áreas de despliegue y condiciones de victoria. Los jugadores tiran un dado, y el ganador elige quien será el primer jugador.

## Ronda

Una Ronda consta de dos Fases: la Fase de Movimiento y la Fase de Acción.

### Fase de Movimiento

Empezando por el primer jugador, los jugadores alternan mover cada modelo bajo su control hasta su movimiento máximo, sea horizontal o verticalmente, colocando un marcador de Movimiento a su lado para indicarlo.
Este movimiento puede ignorar cualquier obstáculo con menos de 3cm de altura.
Existe la posibilidad de decidir que un modelo va a Prepararse en lugar de mover.
En ese caso el jugador coloca un marcador de Preparación a su lado para indicarlo.

### Fase de Acción

Empezando por el primer jugador, los jugadores alternan la posibilidad de activar modelos Preparados, quitando su marcador de Preparación y colocando un marcador de Activación.
Si a un jugador no le quedan modelos Preparados, se salta su activación.
Una vez no haya modelos Preparados en la mesa, se procede al mismo proceso con el resto de modelos no Preparados.
Cuando todos los modelos en la mesa hayan activado, se procede a la siguiente ronda, siendo ahora el otro jugador quien toma el rol de primer jugador.

Las Acciones básicas disponibles a todos los modelos son:
- Atacar: Con Disparo o Combate. En caso de utilizar Combate puede mover primero hasta la mitad de su movimiento.
- Correr: Volver a mover una distancia igual a su movimiento.

## Atacar

Para realizar un ataque, se debe elegir a un combatiente enemigo como defensor.
El defensor debe estar dentro de la distancia de ataque (en el caso de Combate es típicamente contacto base con base y en el caso de Disparo vendrá especificado por la habilidad) y ser visible por el atacante (que haya alguna línea no obstruida entre ambas miniaturas).

En caso de haber dudas razonables sobre la visibilidad de una miniatura, se tirará un dado de 6 caras.
En un resultado de 4 o más, la miniatura es visible.

Los ataques se resuelven mediante tiradas de dados.
El atacante realiza una tirada de Impacto, sumando su habilidad de Impacto en Combate o Disparo (según sea relevante) y restando la habilidad de Defensa correspondiente de su oponente.
En caso de obtener un acierto, el atacante realiza una tirada de Daño, sumando su habilidad de Daño en Combate o Disparo y restando la habilidad de Armadura de su oponente.
Si hiere a su oponente, este es *eliminado* a menos que tenga un Aliado con la habilidad de Sanar a menos de 20cm de distancia.

Aparte de las habilidades que especifican un bonificador o penalizador a estas tiradas, se aplican los siguientes modificadores:

**Modificadores de Disparo**:

- El defensor está a cubierto (a menos de 5cm de una pieza de escenografía que obstruye visión): -1
- El defensor está a distancia larga (mayor de la mitad del alcance): -1
- El defensor está a menos de 5cm de otro aliado del atacante: No se puede realizar el disparo
- 

**Modificadores de Combate**:

- El defensor está a menos de 5cm de otro aliado del atacante: +1
- El atacante está a menos de 5cm de otro aliado del defensor: -1

