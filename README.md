# keepcoding-bd-architecture
Repositorio para la práctica de bd architecture

Contexto

Antes de explicar el proceso de creación de mi datalake para obtener información útil, pongamos en contexto la utilidad.

Jugando a juego llamado Dragon Ball Legends, actualmente la cantidad de personajes se está incrementando semanalmente. Además de eso, necesitas saber que personajes encajan mejor en un grupo de combate, ya que si mezclas habilidades en común sus atributos se multiplican.

Es por eso que cada vez resulta más dificil obtener esta información tanto buscando en el propio juego, como en la wiki. Es por eso que mi intención es obtener los datos básicos que enlazan los atributos básicos como : fusión, o futuro, buscarlos, y buscar la media de sus puntos de habilidad para encontrar los mejores combatientes en el modo jugador vs jugador.

Sprint 1.

Para ello adjunto un documento con la arquitectura planteada y un poco la explicación de los pasos para montarla y actualizarla automáticamente.

Sprint 2.

Una vez tenemos montada la arquitectura, pasaremos a extraer la información con un crawler de la wiki.

https://legends.dbz.space

A modo de resumen: sacamos las propiedades básicas de cada personajes, habilidades, técnicas, tags, nombres, y puntos de habilidad a través del css de la web. Para ello en el siguiente link se encuentra el collaboratory

https://colab.research.google.com/drive/1d8PYQJZlv_K9C4w0s5Vw9qiXnoDjNJ9s

Además, a modo de ejemplo en este repositorio están los ficheros data_test.csv y data.txt donde se pueden ver los datos a analizar.

Sprint 3

Una vez tenemos los datos guardados en sus respectivos ficheros los añadimos manualmente al google cloud platform.

En el siguiente link podemos ver los pasos para poder montar la arquitectura para procesar los datos.

https://colab.research.google.com/drive/1zTRRh7NIySzXmPmWLcgr-oTa13Sbx-G3



