# Trabajo-Modelado
## Indice
1. Introducción   
    * 1.1.Alcance      
    * 1.2.Objetivos  
2. Información del Dominio del Problema  
    * 2.1 Introducción al Dominio del Problema  
    * 2.2 Glosario de Términos  
3. Descripción de la Situación Actual  
    * 3.1 Pros y Contras de la Situcación Actual  
         * 3.1.1 Fortalezas de la Situcación Actual  
        * 3.1.2 Debilidades de la Situación Actual  
    * 3.2 Modelos de Procesos de Negocio Actuales  
        * 3.2.1 Descripción de los Actores de Negocio Actuales    
        * 3.2.2 Descripción de Procesos de Negocio Actuales  
    * 3.3.  Entorno Tecnológico Actual  
        * 3.3.1 Descripción del Entorno de Hardware Actual  
        * 3.3.2 Descripción del Entorno de Software Actual

4. Necesidades de Negocio  
    * 4.1 Obejtos de Negocio  
    * 4.2 Modelos de Procesos de Negocio  
        * 4.2.1 Descripción de los Actores de Negocia a Implantar  
        * 4.2.2 Descripción de Procesos de Negocio a Implantar
5. Descripcion de los Subsistemas del Sistema a Desarrollar  
6. Catalogo de Requisitos del Sistema a Desarrollar  
    * 6.1 Requisitos Generales del Sistema
    * 6.2 Casos de uso del Sistema
        * 6.2.1 Diagramas de Casos de Uso del Sistema 
        * 6.2.2 Especificación de Actores del Sistema
        * 6.2.3 Especificación de Casis de Uso del Sistema
    * 6.3 Requisitos Funcionales del Sistema  
        * 6.3.1 Requisitos de Información del Sistema  
        * 6.3.2 Requisitos de Reglas de Negocio del Sistema  
        * 6.3.3 Requisitos de Conducta del Sistema
    * 6.4 Requisitos No Funcionales del Sistema
        * 6.4.1 Requisitos de Fiabilidad  
        * 6.4.2 Requisitos de Usabilidad  
        * 6.4.3 Requisitos de Eficiencia
        * 6.4.4  Requisitos de Mantenibilidad  
        * 6.4.5 Requisitos de Portabilidad
        * 6.4.6 Requisitos de Seguridad
        * 6.4.7 Otros Requisitos No Funcionales
    * 6.5 Restricciones Técnicas del Sistema
    * 6.6 Requisitos de Integración del Sistema
    * 6.7 Información Sobre Trazabilidad
    

## 1 Introducción
Con la necesidad de ralentizar la pandemia que a todos nos afecta, el Ministerio de Sanidad, se puso en contacto con nosotros con el fin de crear una nueva aplicación de rastreo mediante la cual se tendrá localizado a todas las personas con el virus y a sus personas de contacto, para ya si de una vez dar un respiro a la economía española y salir a flote.

Para ello no solo hará falta la creación de esta plataforma de rastreo si no también la colaboración de todo el personal sanitario, las fuerzas de orden público y por último y más importante la concienciación ciudadana.  

El objetivo es mejorar la aplicación existente Radar Covid ya que, no ha dado los resultados esperados. Se necesita obtener más información de los ciudadanos y gestionar toda la infprmación de manera optima.

### 1.1 Alcance
Se pretende que la plataforma pueda llegar a toda la población española ya sean jóvenes o ancianos, por ello será multiplataforma y de fácil uso, para todos ellos que no estén familiarizados con las nuevas tecnologías.  

En principio, la aplicación se desarrollará para los sistemas operativo Android e iOS con vistas a ser ampliado en otros sistema.

Tendrá dos visiones diferentes para la población, la primera visión es la ‘usuario’ cualquier persona que acceda podrá informar y la segunda visión serán la que tengan los centros de salud, fuerzas del orden, rastreadores, Gobierno, Consejerías, Juntas, donde estos podrán manejar la aplicación y comprobar datos.

### 1.2 Objetivos
Nuestro principal objetivo es paralizar la expansión del virus y que poco a poco vaya disminuyendo los contagios comunitarios, por medio de los contactos estrechos, pero también sabemos que esta plataforma no funciona sola, hace falta personas que la den su uso y sin esas personas que puedan informar esta no servirá para nada.  

Otro objetivo que contemplamos es la de tener localizados mediante localización GPS a los positivos por el COVID-19 y también los posibles positivos, con esto nos referimos a las personas de contacto con dichas personas 7 días antes.  
Gracias a ese objetivo podemos comprobar que las personas cumplan su respectiva cuarentena y tambien se logra conseguir con quien se ha encontrado en esos 7 días anteriores al positivo.

El sistema de notificaciones de la aplicación avisará a los usuarios cuando hayan estado expuestos a otro usuario de la aplicación que haya sido diagnosticado de COVID y ha introducido un código facilitado por las autoridades sanitarias de su comunidad autónoma.

## 2 Información del Dominio del Problema
Esta aplicación surgió, con el problema de poder gestionar y rastrear la información de los ciudadanos durante la pandemia mundial que se sufre actualmente, con el fin de poder minimizar contagios y fallecidos.
Gracias a esta aplicaion se podra identificar de manera más rápida y eficaz los contagios y/o posibles contagios con las personas de contacto.  

Cuando un usuario ha sido diagnosticado de COVID y ha introducido un código proporcionado por las autoridades sanitarias, la aplicación informará mediante el sistema de notificaciones a los usuarios de la aplicación que están en riesgo de haber sido contagiados. Estas personas serán contactadas por los responsables de la comunidad autónoma en la que se encuentren y se le realizarán las pruebas pertinentes.

### 2.1 Introducción al Dominio del Problema
•	La dificultad que genera esta situación de pandemia por la COVID es el no poder controlar los contagios que se generan ya que existen personas asintomáticas, que pueden ser positivos y sin que ellas se den cuenta y contagiar otras personas.  
•	El otro gran problema es el control de las personas de contacto con las que ha estado un positivo en los anteriores 7 días.
•	También hay gente que puede saltarse las cuarentenas impuestas por las autoridades sanitarias con el fin de que el virus no se extienda y a esto se le suma la Ley de Protección de Datos con la que debes garantizar la privacidad e intimidad de las personas entre otras cosas.  
•	En un momento de esta pandemia, se realizaron pruebas médicas masivas para poder tener controlado el virus en las zonas que se realizaba a las que las personas no acudían.  
•	Otro de los problemas seria la deteccion de los contactos estfrechos se realiza a traves de bluetooth por lo tanto debe estar activado de forma continua.
•	El problema mas importante radica en que no es obligatorio el uso de la aplicacion por lo que mucha gente no se ha descargado la aplicación

Estos son los problemas que existen en cuanto al COVID, pero tambien existen otros problemas que hay en cuanto a la aplicación.  

•	Las personas cuando sale una aplicación nueva pueden tardar en entenderla, pero nuestro objetivo es hacerla sencilla y clara. Este punto va destinado a las personas mayores que tienen menos funcionalidad con los smartphones y pueden tener problemas para poner en funcionamiento la aplicación.  
•	Otro de los problemas más relevantes y el de hacer una aplicación que esté funcionando en segundo plano, que no tenga que estar abierta de continuo, y que todo el mundo puede que no tenga acceso a zonas de cobertura para actualizar la información.

El máximo problema que tiene el crear una aplicación en cualquier categoría es que hay que pensar que NO TODAS LAS PERSONAS TIENEN SMARTPHONE.

### 2.2 Glosario de Términos
**Asintomático**: persona que no muestra síntomas de una enfermedad o virus y pueden contagiárselo a los demás.  

**Alerta sanitaria**: este término hace referencia a una situación excepcional que la debe declarar el ministro de sanidad.  

**App en Segundo Plano**: significa que dicha app puede realizar diferentes funcionalidades sin que el usuario este interactuando con la app.  

**Autonomías**: es una entidad del territorio nacional, el cual delega sobre la zona en la que esta. Por ejemplo, las normas sanitarias de Castilla y León las designara la Consejería de Sanidad de Castilla y León.  

**Bluetooth**: es un protocolo de comunicación que permite conectar los distintos móviles, con un radio de 10 metros a través de las señales de radio.  

**Contacto estrecho**: es aquella persona que ha estado en el mismo lugar que un infectado a una distancia menor de 2 metros y durante más de 15 min. Se buscan a los contactos estrechos con los que ha estado el infectado desde 2 días antes de ser confirmado.  

**Covid**: es el nuevo virus el cual afecta de maneras diferentes a las personas y tiene un alto contagio.  

**Cuarentena**: periodo de tiempo con restricción de movimiento en el que puede incubar una enfermedad y trasmitirla por la población.  

**Falsos Positivos**: son las personas que por una primera prueba ha dado positivo del CoVid-19, pero en una segunda es negativo, esto ocurre porque algunos fragmentos del virus se mantienen en tu organismo.  

**Fuerzas del Orden**: es cualquier agencia, como puede ser Policía Nacional, Local, Guardia Civil, etc, que es la responsable de que se cumplan las leyes.  

**GPS**: es un sistema de navegación que proporciona servicios fiables de posicionamiento, navegación y cronometría de continuo a todos los usuarios.  

**Ley de Protección de Datos**: fue una norma creada con el fin de, garantizar y proteger, las libertades y derechos fundamentales de las personas.  

**Pandemia**: es una infección vírica entre las personas en una extensión geográfica extensa.  

**Positivo Serológico (Serológico+)**:  esta prueba consiste en la búsqueda de anticuerpos frente al virus, por una muestra de sangre. Esta prueba no sirve para detectar el virus, pero es efectivo para calcular cuanta población ha pasado el virus.  

**Positivo en PCR (PCR+)**: significa Reacción en Cadena de la Polimerasa, es una prueba de diagnóstico que permite detectar fragmento de la enfermedad en nuestro caso el CoVid-19 pero tambien puede existir los falsos positivos. El resultado tarda entre 3 y 6 horas.  

**Positivo en Test de Antígenos (Antígenos+)**: las pruebas de antígenos, que se sabe el resultado en unos 15 minutos detectan si actualmente eres positivos del virus.  

**Pruebas médicas**: con este término nos referimos a las pruebas CoVid, seria las muestras que toman los sanitarios, para detectar el virus y tenerle controlado, mediante las dichas cuarentenas.  

**Rastreo**: para nuestro caso, consiste en localizar a las personas que puedan haber estado expuestas al virus y seguirlas durante el periodo de incubación del virus, serán 10 días a partir del ultimo día en el que ha estado expuesto.

## 3 Descripción de la Situación Actual
Actualmente disponemos en España de la aplicación Radar COVID. Dada la situación excepcional que vivimos; una pandemia mundial, no se había planteado anteriormente la necesidad de una aplicación como esta. Radar COVID es una tecnología muy novedosa la cual necesita muchas mejoras y cambios. En esta sección se expondrán los aspectos a mejorar de esta aplicación. 
### 3.1 Pros y Contras de la Situación Actual
Últimamente con la crisis del covid-19 hemos estado obligados a estar encerrados en casa (mucha gente sin poder trabajar, otros con teletrabajo), ha mueto mucha gente por causa del virus, situaciones precarias de trabajadores del ámbito sanitario, muchos negocios y empresas han cerrado lo cuál vemos como un punto negativo para la economía tanto mundial como nacional,pero también, gracias a la crisis sanitaria muchas empresas en vez de desaparecer para siempre han conseguido reinventarse para poder dar un servicio el cual es necesario en estos tiempos ya puede ser creación de mascarillas por distintas fabricas, teletrabajos, repartos a domicilio de empresas que no lo hacían, maypr uso de las tecnologías, como por ejemplo las consultas médicas a distancia, crecimiento de juegos y formas de comunicación interactivas, etc, por lo que la pandemia nos ha traído a la vez que puntos negativos tambien puntos positivos como este último.
#### 3.1.1 Fortalezas de la Situación Actual
Pandemio llega para sustituir a RadarCovid mejorando muchos aspectos en lo que a RadarCovid se refiere. En los siguientes cuadros vamos a mostrar muchas ventajas de Pandemio frente a otras aplicaciones de control de pandemia y por que debe ser la número 1 en todos los aspectos.

|1| Consumo de batería|
|---------------|------------|
|[Versión] |1.1 14/11/2020|
|Descripción| El consumo de batería para la aplicación pandemio es reducido gracias a su perfecta optimización de cara a dispositivos moviles tanto de IOS como de Android.
|Comentarios| Mejora futura en el caso de actualizaciones de dispositivos.  |

|2| Uso de datos|
|---------------|------------|
|[Versión] |1.2 14/11/2020|
|Descripción| Uso de datos reducido lo cual provoca un gasto minimo en tu tarifa.|
|Comentarios| Mejora de consumo de datos en un futuro.|

|3| Uso en segundo plano reducido.|
|---------------|------------|
|[Versión] |1.3 14/11/2020|
|Descripción| La aplicación esta todo el rato funcionando lo que provoca que este siempre enviando información y a su vez nos proporciona actualización en tiempo real y preciso.|
|Comentarios| |

|4| Ubicación|
|---------------|------------|
|[Versión] |1.4 14/11/2020|
|Descripción| Uso de la ubicación para informar mediante notificaciones si la zona en la que te encuentras esta afectada o si esta libre de covid para evitar contagios. |
|Comentarios| Mejorar en tal caso la precision y la ubicación.|


#### 3.1.2 Debilidades de la Situación Actual
La aplicación de Pandemio también por su parte tiene distintos problemas los cuales debemos tener en cuenta para la creación de esta. Muchos problemas vienen asociados a la tecnología que tenemos ahora mismo la cual en muchas zonas sobre todo rurales no han llegado a entrar de la forma que debería. En los cuadros a continuación contamos con los distintos problemas que podemos encontrar.

|1| Zonas muertas|
|---------------|------------|
|[Versión] |1.1 14/11/2020|
|Descripción| Zonas en las que la cobertura no llega de forma correcta y no podemos acceder a los servicios que ofrece Pandemio. |
|Comentarios| Por ejemplo a zonas rurales en los que la cobertura no llega |


|2| Personas de avanzada edad o sin dispositivos actuales|
|---------------|------------|
|[Versión] |1.2 14/11/2020|
|Descripción| Zonas en las que la cobertura no llega de forma correcta y no podemos acceder a los servicios que ofrece Pandemio. |
|Comentarios| Por ejemplo a zonas rurales en los que la cobertura no llega |  


|3| Falta de datos|
|---------------|------------|
|[Versión] |1.4 14/11/2020|
|Descripción| Mucha gente solo usa su smartphone con conexión a internet cuando disponen de una red wifi para acceder a servicios en linea por lo que es necesario tener en cuenta a este tipo de personas para el uso diario de la aplicación. |
|Comentarios| |  
### 3.2 Modelos de Procesos de Negocio Actuales
El modelo de proceso de negocio actual es Radar COVID. Esta aplicación se enmarca en un proyecto coordinado por la Secretaria de Estado de Digitalización e Inteligencia artificial, dependiente del Ministerio de Asuntos Económicos y Transformación Digital con el apoyo del Ministerio de Sanidad y las comunidades autónomas en su implementación y evaluación.
#### 3.2.1 Descripción de los Actores de Negocio Actuales
Esta sección contiene información sobre los actores de negocio de los modelos de procesos de negocio actuales.

|1| Ciudadanos|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| • Instalar Radar COVID • Activar app • Encender bluetooth • Recibir notificaciones • Conectarse a internet • Recibir código de positivo en COVID • Introducir código|  
|Descripción| Este actor de negocio actual representa la mayor parte de los usuarios de la app|
|Comentarios| De este actor de negocio extienden los demás actores|

|2| Ministerio de sanidad|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| • Establecer responsables de cada comunidad autónoma • Porporcionar información a los ciudadanos • Generar estadísiticas de datos • Tomar decisiones en base a resultados|
|Descripción| Este actor de negocio actual representa al ministerio de sanidad|  
|Comentarios| |

|3| Ministerio de economía|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| • Financiar la app|
|Descripción| Este actor de negocio
actual representa al ministerio de
sanidad|  
|Comentarios| |

|4| Centro de salud|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| |
|Descripción| Este actor de negocio actual representa al centro de salud que le corresponda a cada usuario|  
|Comentarios| |

|5| Comunidad autónoma|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| • Facilitar el código de usuario positivo en COVID|
|Descripción| Este actor de negocio actual representa a las autoridades sanitarias de cada comunidad autónoma|  
|Comentarios| |

|6| Cuerpos de seguridad del estado|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| • Rastreo • Controlar cumplimiento de cuarentena|
|Descripción| Este actor de negocio actual representa a la policia, militares, guardia civil, aquellos actores que se encargan del cumplimiento de las normas en tiempos de COVID|  
|Comentarios| |

#### 3.2.2 Descripción de Procesos de Negocio Actuales
    
Esta sección contiene los procesos de negocio actuales. Los procesos de negocio describen un conjunto de actividades que convergen en la obtención de un determinado resultado. Estos procesos de negocio son automatizados por el sistema software.

|1| Identificar contactos estrechos|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| • Sistema de notificaciones|
|Descripción| Identificar los contactos estrechos de casos positivos a través del bluetooth|  
|Importancia| Alta|
|Actores| • Ciudadanos usuarios|
|Comentarios| Es el principal objetivo de la aplicación|

|2| Uso de bluetooth|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| • Sistema de 
notificaciones|
|Descripción| Identificar los 
contactos estrechos de casos 
positivos a través del bluetooth|  
|Importancia| Alta|
|Actores| • Ciudadanos usuarios|
|Comentarios| |

|3| Sistema de notificaciones|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| • Identificar contactos estrechos|
|Descripción| Mediante el sistema de notificaciones, la app avisará a los usuarios cuando han estado expuestos a otro usuario que ha sido diagnosticado de COVID y ha introducido el código facilitado por las autoridades sanitarias de su comunidad autónoma|  
|Importancia| Alta|
|Actores| • Comunidad autónoma • Ministerio de sanidad • Ciudadanos|
|Comentarios| El usuario debe permitir el sistema de notificaciones y estar atento a ellas|

|4| No identificación de usuarios|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| |
|Descripción| No se trabaja con datos personales de los usuarios|  
|Importancia| Alta|
|Actores| |
|Comentarios| |

    ![Diagrama de actividad](https://github.com/juandefrutos/Trabajo-Modelado/Procesos de negocio.png)

### 3.3 Entorno Tecnológico Actual
El entorno tecnológico es todo aquello que rodea nuestra aplicación. En nuestra sociedad cada vez se implementan las TIC en los aspectos cotidianos y la llegada de la COVID-19 ha acelerado la implementación delas TIC como posibles soluciones al problema y con las cuales seremos capacesde avanzar y superar la pandemia actual.
#### 3.3.1 Descripción del Entrno de Hardware Actual
El entorno hardware de la aplicación viene dado principalmente por toda la red de comunicación española ya que esta a través de los teléfonos móviles nos permitirá la recopilación de datos y su retransmisión para poder almacenar dichos datos y ser capaces de usarlos de forma adecuada.
Este entorno hardware está limitado a que todas las personas usemos dispositivos móviles con conexión a internet y que este realmente funcione de forma correcta. Por otro lado también debemos de tener en cuenta otros dispositivos que podamos usar en sustitución de móviles ya sean tablets, smartbands, smartwachs o cualquier otro dispositivo.

#### 3.3.2 Descripción del Entorno de Software Actual
El software utilizado en esta aplicación se basa básicamente en la utilización del API de rastreo de contactos creada conjuntamente por Google y Apple. Que básicamente es una función añadida para poder realizar esta función de rastreo sin necesidad de crear una de cero. La creación de esta API nos facilita el funcionamiento tanto en sistemas operativos de Android como de IOs.
    
## 4.Necesidades de Negocio  
Esta sección incluye los objetivos de negocio de clientes y usuarios, incluyendo los modelos de proceso de negocio a implantar.

### 4.1 Objetivos de Negocio  
Objetivos que se esperan conseguir mediante el uso de Pandemio.

|1|Verificar realización de PCR|
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias| • identificación de usuarios • identificar contactos estrechos • obtener listado de personas que deben hacerse pcr |
|Descripción| El usuario podrá informar de la realización de su pcr, asi como el centro de salud, de esta manera los cuerpos de seguridad podrán controlar los contactos estrechos que se realizan el test|
|Subojetivos| • notificación de incumplimiento de normas |  
|Importancia| Alta|
|Prioridad| Alta|
|Comentarios||

|2|Verificar cumplimiento de cuarentena|
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias| • identificación de usuarios • verificar realización de pcr • obtener listado de personas que deben hacer cuarentena|
|Descripción| los cuerpos de seguridad podrán verificar que el positivo cumple cuarentena mediante la localización, en caso de que este usuario salga de casa, saltará una alarma|
|Subojetivos| • notificación de incumplimiento de normas |  
|Importancia| Alta|
|Prioridad| Alta|
|Comentarios||

|3|Obtener listado de personas que deben hacerse PCR|
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias| • identificación de usuarios |
|Descripción| Los cuerpos de seguridad y los centros sanitarios tendrán acceso a una lista con aquellos usuarios que deben realizarse la prueba|
|Subojetivos| • verificar realización de PCR |  
|Importancia| Alta|
|Prioridad| Alta|
|Comentarios||

|4|Obtener listado de personas en cuarentena|
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias| • identificación de usuarios |
|Descripción| Los cuerpos de seguridad tendrán acceso a un listado de aquellos de usuarios que deben realizar cuarentena con el fin de poder verificar el cumplimiento de esta|
|Subojetivos| • notificación incumplimiento de normas • verificar realización de cuarentena|  
|Importancia| Alta|
|Prioridad| Alta|
|Comentarios||

|5|Notificación de incumplimiento de normas|
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias| • verificar realización pcr • verificar realización de cuarentena|
|Descripción| el centro de salud podrá informar de la no realización de la pcr por parte de un usuario, asi los cuerpos de seguridad obtendran esta notificación. También si el usuario no cumple la cuarentena|
|Subojetivos| |  
|Importancia| Alta|
|Prioridad| Alta|
|Comentarios||

|6|Desistalación de la app|
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias| • |
|Descripción| En caso de cambio de leyes (que la aplicación deje de ser obligatoria) se dará la posibilidad de la desactivación de la app|
|Subojetivos| |  
|Importancia| Alta|
|Prioridad| Alta|
|Comentarios||

### 4.2 Modelos de Procesos de Negocio  
Esta sección incluye las mejoras respecto a los modelos de procesos de negocio de radar covid.

#### 4.2.1 Descripción de los Actores de Negocia a Implantar  

|1|Rastreadores|
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias| • |
|Descripción| |
|Comentarios|| 

#### 4.2.2 Descripción de Procesos de Negocio a Implantar  

|1|Uso de GPS|
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias| • uso de bluetooth |
|Descripción| Los contactos estrechos se identificarán por medio
del GPS en vez de por el bluetooth. Gracias al sistema de
localización, los cuerpos de seguridad y los centros sanitarios
podrán tener control sobre aquellas personas que deben realizarse
la pcr, asi como los que deben cumplir cuarentena |
|Importancia| Alta |
|Actores| usuarios, centros sanitarios, cuerpos de seguridad |
|Comentarios| |

|2|Uso de satélite|
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias| • |
|Descripción| para las zonas sin cobertura se usará el envío de datos por satélite en lugar de internet|
|Importancia| Alta|
|Actores| todos los usuarios|
|Comentarios| |

|3|Transferencia de datos entre actores|
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias| • |
|Descripción| Los actores se transfieren datos entre sí para comunicarsey gestionar la información |
|Importancia| |
|Actores| • todos |
|Comentarios| |

|4|Identificación de usuarios|
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias| • no identificación de usuarios |
|Descripción| mediante la identificación de los usuarios, se podrá por ejemplo, tener acceso a su historia clínico para estabelecer el nível de riesgo que tiene, también facilita su localización (dirección)|
|Importancia| Alta |
|Actores| • usuarios |
|Comentarios| |

|5|Crear estadísticas|
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias| • |
|Descripción| mediante la identificación de los usuarios, se podrá 
por ejemplo, tener acceso a su historia clínico para estabelecer 
el nível de riesgo que tiene, también facilita su localización 
(dirección)|
|Importancia| Alta |
|Actores| • usuarios |
|Comentarios| |

## 5.Descripcion de los Subsistemas del Sistema a Desarrollar  

|1| Fuerzas del orden  |
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias|Sistema de notificaciones y checkeo del cumplimiento de la cuarentena|                
|Descripción| Este subsistema es el encargado de checkear el cumplimiento de las cuarentenas y el cumplimiento de las restricciones impuestas por las autoridades competentes. Dicha comprobacion se realiza tras el recibo de notificaciones por parte de los centros de salud los cuales indican el positivo de la persona  |  
|Importancia| Alta |  
|Prioridad| Media |
|Comentarios| Este subsitema se encargara del control de las normas impuestas realizando controles y poniendo multas a las personas las cuales incumplan las normas|

![Arbol de Carcteristicas](https://github.com/juandefrutos/Trabajo-Modelado/PoliciaArbolCaracteristicas.png)  
![Diagrama de Flujo](https://github.com/juandefrutos/Trabajo-Modelado/PoliciaFlujo.png)

|2| Rastreadores  |
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias|Sistema de notificaciones, Identificar contactos y alertas de usuarios|                
|Descripción| En este subsistema se llevara a cabo la contratacion de personal cualificado denominado rastreador encargado de realizar el seguimiento de los contagios y contactos directos el cual informara al usuario en caso de contacto con positivo|  
|Importancia| Media |  
|Prioridad| Baja |
|Comentarios| Los rastreadores se contratan con la intencion de controlar posibles personas las cuales no tengan acceso a un dispositivo smartphone |

![Arbol de Carcteristicas](https://github.com/juandefrutos/Trabajo-Modelado/RastreadorArbolCaracteristicas.png)  
![Diagrama de Flujo](https://github.com/juandefrutos/Trabajo-Modelado/RastreadorFlujo.png)

|3| Centos de salud  |
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias|Sistema de Notificaciones, Generador de identificadores aleatorios y Control de Test |                
|Descripción| Este subsistema se encargara de toda la gestion de la pandemia, controlara quien acude o no a la realizacion de test, ya sean masivos o no,notificara a los usuarios si deben cumplir cuarentenas y a las fuerzas de los orden quien y cuanto tiempo debe estar un usuario en cuarentena, con tal de que no se salte la cuarentena.  |  
|Importancia| Alta |  
|Prioridad| Alta |
|Comentarios| En este subsistema se daran de alta los positivos y se les asiganra un codigo unico para el usuario. Tambien sera la conexion entre las autonomias y las fuerzas del orden y usuarios.|


![Arbol de Carcteristicas](https://github.com/juandefrutos/Trabajo-Modelado/CentrodeSalud.png)  
![Diagrama de Flujo](https://github.com/juandefrutos/Trabajo-Modelado/CentrosdeSaludFlujo.png)

|4| Autonomias |
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias| Sistema de Notificaciones,Alerta de Restricciones,Comprobrar Datos y Crear Estadisticas | 
|Descripción| Con las autonomias lo que se pretende es tener un control mas aislado para diferentes comunidades autonomas, asi cada comunidad comprobando los datos, asigara nuevas restricciones si los contagios suben y endurecera las restricciones si los contagios disminuyen.  |
|Importancia| Alta|  
|Prioridad| Media |
|Comentarios| Las autonomias consiste en un via conductora entre las normas dictadas a nivel nacional por el Ministerio de Sanidad y los Centros de Salud|
![Arbol de Carcteristicas](https://github.com/juandefrutos/Trabajo-Modelado/Autonomias.png)  
![Diagrama de Flujo](https://github.com/juandefrutos/Trabajo-Modelado/AutonomiaFlujo.png)


|5	|Usuario|
|---------------|------------|
|Versión|	1.0 (30/11/2020)|
|Dependencias|	Sistema de notificaciones , Rastreo de casos cercanos al usuario de forma anónima, Introducción de código en caso de positivo, actualización de datos|
|Descripción|	Este subsistema se encargara de ofrecer al usuario información de todos los casos alrededor suyo, información sobre si esta en una zona segura o si alguna persona cercana ha sido positivo. En caso de dar positivo el usuario deberá introducir un código que le ofrecen en los centros de salud para indicar al resto de usuarios que han estado con el que deben permanecer en cuarentena. |
|Importancia|	Alta|
|Prioridad|	Alta|
|Comentarios	|El usuario deberá ser responsable y si es positivo permanecer en casa en cuarentena, a su vez, deberá mantener la ubicación activada para tener control sobre la zona en la que está si es peligrosa o no.|

![Arbol de Carcteristicas](https://github.com/juandefrutos/Trabajo-Modelado/ArbolcaracteristicasUsuariodaniel.png)  
![Diagrama de Flujo](https://github.com/juandefrutos/Trabajo-Modelado/FlujousuarioDaniel.png)


|6	|Ministerio de Sanidad|
|---------------|------------|
|Versión|	1.0 (30/11/2020)|
|Dependencias|	Sistema de Notificaciones,Alerta de Restricciones,Comprobrar Datos y Crear Estadisticas|
|Descripción|	Este subsistema se encargará de controlar la situación de formal global, es decir, las autonomías se encargan de cada una la suya pero el gobierno recoge información de todas ellas y lo junta para un estudio global.|
|Importancia|	Alta|
|Prioridad|	Media|
|Comentarios	|El gobierno recopila todos los datos referentes de todas las autonomías.|

![Arbol de Carcteristicas](https://github.com/juandefrutos/Trabajo-Modelado/Arbolcaracteristicasgobiernodaniel.png)  
![Diagrama de Flujo](https://github.com/juandefrutos/Trabajo-Modelado/Diagramadeflujogobiernodaniel.png)

## 6.Catalogo de Requisitos del Sistema a Desarrollar  

### 6.1 Requisitos Generales del Sistema  
### 6.2 Casos de uso del Sistema  
#### 6.2.1 Diagramas de Casos de Uso del Sistema   
#### 6.2.2 Especificación de Actores del Sistema  
#### 6.2.3 Especificación de Casis de Uso del Sistema  
### 6.3 Requisitos Funcionales del Sistema  
#### 6.3.1 Requisitos de Información del Sistema  
#### 6.3.2 Requisitos de Reglas de Negocio del Sistema  
#### 6.3.3 Requisitos de Conducta del Sistema  
### 6.4 Requisitos No Funcionales del Sistema  
#### 6.4.1 Requisitos de Fiabilidad  
#### 6.4.2 Requisitos de Usabilidad  
#### 6.4.3 Requisitos de Eficiencia  
#### 6.4.4  Requisitos de Mantenibilidad  
#### 6.4.5 Requisitos de Portabilidad  
#### 6.4.6 Requisitos de Seguridad  
#### 6.4.7 Otros Requisitos No Funcionales  
### 6.5 Restricciones Técnicas del Sistema  
### 6.6 Requisitos de Integración del Sistema  
### 6.7 Información Sobre Trazabilidad  
    