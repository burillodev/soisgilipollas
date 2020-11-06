# Sois Gilipollas
Proyecto para jugar online a un juego con la misma filosofia que Absolutas Idioteces. Desplegado en cloud

##Objetivo del juego
El juego consiste en partidas de varios jugadores en los que en cada turno, uno de los jugadores
selecciona una tarjeta y elige un tipo de pregunta dentro de cada tarjeta, lee el tipo de 
pregunta y el resto tienen que inventar una respuesta basada en la pregunta. El jugador que
dirige la pregunta en el turno, recibe las respuestas de los otros jugadores, e incluye 
la respuesta original que viene en la tarjeta, numerando cada respuesta. Después de leer cada
respuesta, los jugadores tienen que elegir una, excepto el que dirige la pregunta, intentando
elegir la respuesta que viene en la tarjeta. Por cada respuesta acertada, el jugador que la haya
escrito recibe 1 punto. Por cada jugador que ha elegido la respuesta de la tarjeta, recibe 2 puntos.
Si ningún jugador elige la pregunta del jugador que dirige, este gana 3 puntos.

Gana el jugador que primero llegue a 40 puntos.

El comienzo del primer turno es aleatorio.

### Implementación
El proyecto está implementado con Python 3.6 y Flask. Desplegado en functions serverless en Azure Funtions. 
Puedes obtener una suscripción de Azure, para usar Azure Functions, durante un año.
El almacenamiento de las imágenes es en Azure Storage y los datos en un MongoDB manejado
con Azure Cosmos DB.

#### Construcción del proyecto
PENDING

#### Despliegue del proyecto
PENDING

#### Pruebas

## Modelo de Dominio

- Jugadores
- Tarjetas
- Respuestas
- Partidas
- Turnos