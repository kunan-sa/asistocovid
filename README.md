# Asistocovid
### Asistente Virtual COVID-19

Dada la situación que se esta viviendo en medio de la pandemia por coronavirus desde el equipo de Inteligencia Artificial de KUNAN decidimos aportar a la comunidad. 

Realizamos un asistente virtual a través de un chat para responder a dudas que se fueran generando respecto a la cuarentena y la situación actual. Siempre con el objetivo de hacer llegar a la gente, de una forma sencilla y directa, la información de fuentes oficiales. Se abarca una amplia variedad de temas, no solo medidas tomadas desde el gobierno sino tambien recomendaciones de los principales entes de salud como la OMS / OPS a nivel internacional y el Ministerio de Salud de la Nación a nivel nacional.

Este proyecto es sin fines de lucro. Puede verse en https://asistocovid.com.ar y quien desee puede disponer del asistente para colocarlo en su sitio web mediante el código que se proporciona en la página.

### Dataset

En el presente repositorio se puede acceder al dataset de conversaciones entre los usuarios y el asistente virtual. Se dispone de una forma conveniente en formato .csv para su adquisición y análisis. 

Éste se irá actualizando todas las semanas para agregar más data que vaya surgiendo.

Descripción del archivo __DatasetAsistocovid.csv__:
- ID_evento: identificador para cada evento. Un evento puede ser entendido como un mensaje enviado ya sea por el usuario o por el bot.
- ID_conversacion: identificador para cada usuario que interactuó con el bot.
- evento: [user, bot] según quien envió el mensaje
- texto: descripción del mensaje
- fecha: formato día-mes-año. fecha del evento
- hora: formato hora-minutos-segundos. hora del evento

Términos de uso del dataset:
* El dataset queda a disposición únicamente para fines de investigación, educativos y académicos sin fines de lucro. 
* Queda prohibido su uso con fines comerciales, como así también su modificación.
* Las respuestas dadas por el asistente se basan en fuentes oficiales, y tienen solo un fin informativo. Éstas no deben tomarse como consejo médico.
* El uso del dataset constituye la aceptación de estos términos de uso.

#### Notebooks

Se adjuntan además unas notebooks como ejemplos posibles de algunos análisis que se podrían realizar.

#### Contactos:
* Daniel Robins, CDO at Kunan S.A. daniel.robins@kunan.com.ar
* Brandon Janes, AI developer en Kunan S.A. brandon.janes@kunan.com.ar
* Karen Palacio, AI developer en Kunan S.A. karen.palacio@kunan.com.ar
* Florencia Alonso, AI developer en Kunan S.A. florencia.alonso@kunan.com.ar


