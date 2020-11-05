# ENTREVISTA RadarCovid
[plataforma de rastreo para tiempos de pandemia]

## Entrevista entre el ministro de sanidad: **Salvador Illa** y **nuestro equipo de desarrollo**

Illa quiere una plataforma que permita rastrear y gestionar la información de los ciudadanos de la próxima pandemia.

***PREGUNTA(equipo)***: Entonces, señor ministro, Radar Covid no ha dado los resultados esperados. En primer lugar, aclaremos cómo funciona Radar Covid y establezcamos sus puntos fuertes y débiles. Nuestro objetivo es subsanar esos puntos débiles y mejorar la aplicación existente.
¿cuáles son los principales problemas que han surgido?
***RESPUESTA(Illa)***: Bueno, el principal objetivo de la aplicación móvil Radar Covid es ayudar a controlar la propagación del COVID – 19 a través de la identificación de los posibles contactos estrechos de casos confirmados a través de la tecnología Bluetooth.
***P***: ¿Qué es un contacto estrecho?
***R***: Un contacto estrecho es aquella persona que ha estado en el mismo lugar que un infectado a una distancia menor de 2 metros y durante más de 15 min. Se buscan a los contactos estrechos con los que ha estado el infectado desde 2 días antes de ser confirmado.
***P***: Y a estos contactos estrechos, la aplicación les envía una notificación, ¿no?
***R***: Así es.
El sistema de notificaciones de exposición de Radar COVID tiene como objetivo avisar a los usuarios cuando han estado expuestos a otro usuario de la aplicación que ha sido diagnosticado de COVID-19 y ha introducido un código facilitado por las autoridades sanitarias de su comunidad autónoma.
Cada dispositivo que tenga la aplicación instalada y el Bluetooth activado, genera de forma continua identificadores aleatorios, que se intercambian con otros dispositivos que también la tengan activa y se encuentren a menos de dos metros. Cada teléfono almacena durante los siguientes 14 días sus propios identificadores generados, así como los identificadores de los dispositivos que han estado cerca. Cuando un usuario recibe un diagnóstico positivo de COVID-19, los servicios de salud deben facilitarle un código numérico de caso positivo que la persona deberá introducir en la aplicación si es usuaria de la misma. En este momento, los identificadores aleatorios generados por ese dispositivo durante los 5 días previos a ese momento se etiquetan como positivos y se lanzan a la nube con consentimiento del usuario. Por su parte, periódicamente, todos los dispositivos descargan los identificadores etiquetados como positivos de la nube y realizan un cruce de datos o emparejamiento con los identificadores almacenados en sus dispositivos. La aplicación genera una señal de alerta si estos identificadores positivos se encuentran entre los almacenados como contactos y si suponen un tiempo de exposición superior a 15 minutos. Se ha determinado que la búsqueda de contactos se realice hasta 5 días antes del momento de la introducción del código de caso positivo ya que el retraso medio entre la fecha de inicio de síntomas y la fecha de diagnóstico es de 3 días y la búsqueda tiene que ampliarse hasta 2 días antes de la fecha de inicio de síntomas.
***P***: ¿Cómo mide la aplicación la distancia? ¿Si hay una pared en medio o un cristal deja de funcionar? 
***R***: Los dispositivos móviles no pueden medir directamente la distancia a la que se produce un contacto ni determinar si existe alguna barrera física en medio. Por lo tanto, Radar COVID toma como referencia la atenuación de la señal de Bluetooth Low Energy (de baja energía) para realizar una estimación. Se han realizado varios estudios científicos en los que se analizaron diferentes umbrales de Bluetooth demostrando que esta tecnología es capaz de discriminar contactos a través de determinados elementos divisores como por ejemplo paredes o coches, por lo tanto, si hay algún elemento que separe dos dispositivos que atenúe suficientemente la señal ese contacto se ignorará.
***P***: ¿Cómo se protege la privacidad de los usuarios? 
***R***: Durante todo el proceso de diseño y desarrollo de Radar COVID, la protección de la privacidad ha sido una prioridad. Estas son algunas de las medidas con las que Radar COVID protege tus datos: 
    * La aplicación no recopila ningún dato que permita rastrear tu identidad. Por ejemplo, no te preguntará y no podrá conocer tu nombre, apellidos, dirección, número de teléfono o dirección de correo electrónico. 
    * La aplicación no puede determinar el lugar en el que se produjo un contacto ni quiénes estaban presentes. 
    * La aplicación no recopila ningún dato de geolocalización, incluidos los del sistema GPS. Además, tampoco realiza ningún seguimiento de tus desplazamientos. 
    * El código de Bluetooth Low Energy (de baja energía) que se transmite a través de la aplicación se genera aleatoriamente y no contiene ninguna información sobre tu dispositivo móvil ni sobre ti. Además, este código cambia varias veces cada hora para proteger aún más tu privacidad.
    * Los datos que se guardan en tu teléfono móvil están cifrados. 
    * Las conexiones entre la aplicación y el servidor están cifradas. 
    * Todos los datos, incluidos los que se guardan en tu dispositivo (códigos intercambiados con otros teléfonos móviles) y los recogidos en el servidor (procedentes de los teléfonos móviles donde se ha reportado un diagnóstico positivo) son eliminados al cabo de 14 días. 
    * El sistema de salud no guarda los códigos positivos que se generan asociados a un diagnóstico positivo ni en la historia clínica ni en otro emplazamiento. 
    * Ningún dato almacenado en los teléfonos móviles o en el servidor permite la identificación ni del dispositivo móvil ni del usuario del mismo. 
    * Radar COVID no maneja información susceptible de ser vendida o utilizada para ningún objetivo comercial, incluyendo la creación de perfiles con fines publicitarios. Este proyecto no tiene ningún ánimo de lucro, siendo creado exclusivamente para ayudar a combatir la epidemia.
***P***: ¿Qué dispositivos y sistemas operativos son compatibles con Radar COVID?
***R***: La aplicación no es compatible con todos los dispositivos.
    * Teléfonos con iOS
    Solo se puede descargar a partir de la versión 13.5.
    * Teléfonos con Android
    Solo se puede descargar para Android 6 o superior y desde Google Play Services 20.18.13 o superior.
    Por otro lado, no se recomienda usarla en dispositivos que no sean móviles, por ejemplo en una Tablet.
***P***: Entiendo. Si no tenemos Android o Iphone con estas características no podemos usar la app.
***R***: Eso es, Radar COVID utiliza la tecnología para las notificaciones de exposición que proporcionan Apple y Google.
***P***: ¿Qué se debe hacer para usar bien la aplicación?
***R***: Lo principal es tener el móvil encendido, la aplicación y el bluetooth activado, y dar los permisos para las notificaciones de la app.
***P***: Otro inconveniente que veo es la no obligatoriedad de usar la aplicación.
***R***: Eso es, es uno de los principales puntos en los que hay que trabajar.
***P***: Una de las cosas que tiran hacia tras a los posibles usuarios de Android para usar la app es que al activar el Bluetooth, se pide que actives la geolocalización, ¿para qué?
***R***: En los dispositivos móviles Android, debido a una limitación del sistema operativo, el servicio de ubicación debe estar habilitado para permitir que el sistema de notificaciones de exposición de Google busque señales de Bluetooth Low Energy y guarde los identificadores aleatorios de los teléfonos de los usuarios que estén cerca de ti. Sin embargo, como puedes ver en la lista de permisos que solicita RadarCOVID, la aplicación no tiene autorización para acceder a ningún dato relacionado con la ubicación (incluidos los del GPS) y, por lo tanto, no puede saber dónde te encuentras.
***P***: Por otro lado, Radar COVID, ¿consume mucha batería?
***R***: No, la app usa Bluetooth Low Enegry (bluetooh de baja energía), es una tecnología creada para ser particularmente eficiente en cuanto a ahorro de energía.
***P***: Otra cuestión a tratar, entiendo que los usuarios no tienen un perfil de usuario establecido, por lo que si instalo la app en otro dispositivo móvil, Radar COVID me considerará otra persona y se perderá el rastro de los contactos de los últimos días y por lo tanto, no podré avisar de un posible contagio.
***R***: Exactamente, es otro de los grandes puntos a mejorar.
***P***: ¿Y si el teléfono está en modo avión?
***R***: No es problema siempre que tengas el Bluetooth activado y la opción radar COVID situada en la página de inicio de la aplicación activada.
***P***: También debemos descargar datos de la nube, por lo que tendremos que conectarnos a internet mínimo una vez al día para descargar la información correspondiente. Quien no tenga acceso al menos una vez al día a internet no le sirve casi de nada tener esta aplicación.
***R***: Así es, las personas que no tengan acceso a este recurso tienen una gran limitación.
***P***: ¿Consume datos Radar COVID?
***R***: Muy pocos. Todos los días, la aplicación descarga las nuevas claves criptográficas de los dispositivos de los usuarios que han dado positivo en COVID-19 para verificar si has tenido algún contacto con ellos y, en caso necesario, notificártelo. Esto consumirá unos cuantos kilobytes (KB) al día, más o menos lo mismo que se necesita para cargar una página web con algunas fotos. De todas formas, esta acción la puedes hacer utilizando una red Wi-Fi en tu hogar o en algún establecimiento que disponga de ella.
***P***: ¿Se deben descargar todas las actualizaciones de la aplicación?
***R***: Si, estas están destinadas a mejorar la eficacia del sistema y corregir defectos. La aplicación te notificará la necesidad de actualización. Sin embargo, el usuario decide si la instala o no.
***P***: ¿El usuario que de positivo y tenga la app instalada que debe hacer?
***R***: Debe introducir un código en el apartado correspondiente en la app. Este código que es de un solo uso y no va asociado a ningún dato personal del usuario, llega a través de los responsables de tu comunidad autónoma. Una vez introducido el código, la app mostrará el estado de confirmado y deberá estar en aislamiento. Una vez introducido el código de caso confirmado, el dispositivo de ese usuario deja de emitir identificadores que puedan generar nuevos contactos de riesgo.
***P***: Entonces si este usuario positivo en Covid no hace cuarentena, la aplicación no tendrá en cuenta los posibles contagios nuevos.
***R***: Así es, necesitamos un sistema que garantice que la persona infectada cumple con las medidas pertinentes.
***P***: Por otro lado, si esta persona no introduce ese código en la aplicación, tampoco se detectarán contactos de riesgo.
***R***: Si, hay muchas cosas que mejorar.
***P***: Si un usuario es identificado por la app como contacto de riesgo en vez de ser identificado manualmente, ¿Por qué no se hacen las mismas recomendaciones?
***R***: Cuando se detecta un contacto de riesgo a través de la aplicación, y para preservar al máximo la privacidad y protección de los datos del usuario, no se dispone de información de la persona ni del contexto en el que ha ocurrido el contacto de riesgo. En el rastreo de contactos manual es posible obtener información más exhaustiva sobre la exposición y graduar el riesgo de transmisión de la infección dependiendo de la situación. Por tanto, las recomendaciones podrían ser diferentes en función de la forma con la que se haya identificado al contacto y de la evaluación realizada.
***P***: Tras ser declarado un usuario como contacto de riesgo y después de realizarse las pruebas dar negativo, ¿cómo puede volver al estado sin contacto de riesgo identificado?
***R***: Deberá desinstalar la aplicación y volverla a instalar.
***P***: Respecto a los sanitarios, los cuales pasan gran parte del día con los infectados, ¿cómo deben usar la aplicación?
***R***: Para obtener un mejor rendimiento de la app, pueden desactivar el Bluetooth o la app directamente (no desinstalarla) durante las horas de contactos con los casos de COVID. Una vez finalizada la exposición volver a activar el Bluetooth y Radar COVID.
***P***: Esta app tampoco determina el nivel de riesgo, ya que no puede distinguir cuando un usuario cumple las indicaciones sanitarias o no.
***R***: Claro el Bluetooth no distingue. La valoración final del nivel de riesgo relativa a la alerta de contacto generada por la aplicación deberá ser cuantificada por los responsables del sistema sanitario.
***P***: ¿Puede conectarse Radar COVID con otras aplicaciones para el rastreo de contactos? Por ejemplo las desarrolladas fuera de España.
***R***: No, solo funciona con usuarios de la misma aplicación, en otros países se usan otras aplicaciones con el mismo funcionamiento. Queremos desarrollar una interoperabilidad entre ellas.

> BIBLIOGRAFIA
https://www.mscbs.gob.es/profesionales/saludPublica/ccayes/alertasActual/nCov/documentos/Preguntas_y_respuestas_RADAR-COVID.pdf
