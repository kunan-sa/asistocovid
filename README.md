# Asistocovid
### Asistente Virtual COVID-19

Dada la situación que se esta viviendo en medio de la pandemia por coronavirus desde el equipo de Inteligencia Artificial de KUNAN decidimos aportar a la comunidad. 

Realizamos un asistente virtual a través de un chat para responder a dudas que se fueran generando respecto a la cuarentena y la situación actual. Siempre con el objetivo de hacer llegar a la gente, de una forma sencilla y directa, la información de fuentes oficiales. Se abarca una amplia variedad de temas, no solo medidas tomadas desde el gobierno sino tambien recomendaciones de los principales entes de salud como la OMS / OPS a nivel mundial y el Ministerio de Salud de la Nación a nivel nacional.

Este proyecto es sin fines de lucro, y está disponible para quien desee agregar el asistente a su sitio web. Se puede ver en https://asistocovid.com.ar

### Dataset

Los datos recolectados de las conversaciones se disponen de forma libre en el repo como un csv. Éste se irá actualizando con el tiempo para agregar más data que vaya surgiendo.

Descripción del archivo __DatasetAsistocovid.csv__:
- ID_evento: identificador para cada evento. Un evento puede ser entendido como un mensaje enviado ya sea por el usuario o por el bot.
- ID_conversacion: identificador para cada usuario que interactuó con el bot.
- evento: [user, bot] según quien envió el mensaje
- texto: descripción del mensaje
- fecha: formato día-mes-año. fecha del evento
- hora: formato hora-minutos-segundos. hora del evento


