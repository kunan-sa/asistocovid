# Asistiendo el acceso de información veraz con NLP: Covid19 

__Mentora: Florencia Alonso__

### Introducción:

Con el comienzo de la pandemia por coronavirus y la situación de aislamiento social, preventivo y obligatorio que comenzó a vivirse el 20 de Marzo, el equipo de Inteligencia Artificial de KUNAN junto a un grupo de voluntarios comenzó el desarrollo de un asistente virtual a través de un chat para responder las dudas que se fueran generando respecto a la cuarentena y demás medidas tomadas ante esa situación. 

Siempre con el objetivo de centralizar la información de distintas de fuentes oficiales y hacerla llegar a la gente, de una forma sencilla y directa. Algunas de ellas son: el Boletín oficial, recomendaciones de la OMS/OPS, el Ministerio de Salud de la Nación y Ministerios de salud provinciales, el Banco Central, la AFIP.

Con el pasar de los días se llegó a abarcar una amplia variedad de temas: medidas tomadas desde el gobierno, estadísticas de casos en provincias de Argentina y en países en general, recomendaciones de los principales entes de salud, también se trataron temas como la violencia de género, los estados de ansiedad y otras cuestiones psicológicas durante la cuarentena. Además hubo un esfuerzo constante por mantener el asistente actualizado con los cambios que fueran surgiendo y nuevos temas de interés.

El proyecto es sin fines de lucro y puede verse en https://asistocovid.com.ar. Se puso a libre disposición de quien quisiera colocar el asistente en su sitio web.

### Dataset:

En ésta mentoría se va a trabajar sobre un dataset conformado por todas las conversaciones que tuvo el asistente virtual con usuarios. Tanto usuarios desde la página asistocovid como de otras páginas donde fue insertado.

En https://github.com/kunan-sa/asistocovid se puede acceder al dataset. Se encuentra en formato .csv para su cómoda adquisición y análisis.

Descripción del archivo _DatasetAsistocovid.csv_:
- ID_evento: identificador para cada evento. Un evento puede ser entendido como un mensaje enviado ya sea por el usuario o por el bot.
- ID_conversacion: identificador para cada usuario que interactuó con el bot.
- evento: [user, bot] según quien envió el mensaje
- categoría: nombre de la categoría que se puede asignar a la frase del usuario.
- texto: descripción del mensaje
- fecha: formato día-mes-año. Fecha del evento
- hora: formato hora-minutos-segundos. Hora del evento

### Objetivos:

Como objetivo general se pretende integrar sobre un mismo dataset los temas vistos en las materias obligatorias de la Diplomatura y al mismo tiempo tener una primera aproximación al análisis de texto y el procesamiento del lenguaje natural.

Como puntos específicos se buscará:
- Tomar conciencia del aprendizaje y evolución continua de un asistente conversacional, ya que al ser un modelo basado en datos se va mejorando a medida que cuenta con más conversaciones con usuarios. Ésto se verá en la etapa de análisis, sobre todo de las primeras semanas de vida del asistente.
- Clasificar las frases de los usuarios como una primera aproximación a un bot.
- Descubrir tópicos en las preguntas y frases formuladas por los usuarios. Más que nada apuntando a aquellos temas de interés del público donde hay falta de información oficial. Aunque también esto es útil en el proceso de actualización de la información cubierta por el bot.
- Análisis de sentimiento para buscar indicadores de angustia y violencia en las input de usuario. Lo que permitiría detectar y tratar éstos temas en el asistente.

