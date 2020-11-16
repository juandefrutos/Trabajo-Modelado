### 3.2 Modelos de Procesos de Negocio Actuales
    El modelo de proceso de negocio actual es Radar COVID. Esta aplicación se enmarca en un proyecto coordinado por la Secretaria de Estado de Digitalización e Inteligencia artificial, dependiente del Ministerio de Asuntos Económicos y Transformación Digital con el apoyo del Ministerio de Sanidad y las comunidades autónomas en su implementación y evaluación.
#### 3.2.1 Descripción de los Actores de Negocio Actuales
    Esta sección contiene información sobre los actores de negocio de los modelos de procesos de negocio actuales.

|1| Ciudadanos|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| *Instalar Radar COVID *Activar app *Encender bluetooth *Recibir notificaciones *Conectarse a internet *Recibir código de positivo en COVID *Introducir código|  
|Descripción| Este actor de negocio actual representa la mayor parte de los usuarios de la app|
|Comentarios| De este actor de negocio extienden los demás actores|

|2| Desarrolladores|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| |
|Descripción| Este actor de negocio actual representa al grupo de personas encargados de definir el producto que será desarrollado|
|Comentarios | |

|3| Diseñadores|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| |
|Descripción| Este actor de      negocio actual representa al grupo de trabajo que establecerá el comportamiento del sistema|
|Comentarios | |

|4| AR|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| |
|Descripción| Este actor de negocio actual representa al analística de requisitos; aquel que establece los requisitos del sw, así como las prioridades de estos. Las reglas de negocio, se encarga de la elicitación|  
|Comentarios | |

|5| Ministerio de sanidad|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| *Financiar la app *Establecer responsables de cada comunidad autónoma *Porporcionar información a los ciudadanos *Generar estadísiticas de datos *Tomar decisiones objetivas|
|Descripción| Este actor de negocio actual representa al ministerio de sanidad|  
|Comentarios| |

|6| Centro de salud|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| |
|Descripción| Este actor de negocio actual representa al centro de salud que le corresponda a cada usuario|  
|Comentarios| |

|7| Comunidad autónoma|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| *Facilitar el código de usuario positivo en COVID|
|Descripción| Este actor de negocio actual representa a las autoridades sanitarias de cada comunidad autónoma|  
|Comentarios| |

|8| Cuerpos de seguridad del estado|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| *Rastreo *Controlar cumplimiento de la cuarentena|
|Descripción| Este actor de negocio actual representa a la policia, militares, guardia civil, aquellos actores que se encargan del cumplimiento de las normas en tiempos de COVID|  
|Comentarios| |

|9| Administradores de la app|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| |
|Descripción| Este actor de negocio actual representa al administrador de la app|  
|Comentarios |         
#### 3.2.2 Descripción de Procesos de Negocio Actuales
    
    Esta sección contiene los procesos de negocio actuales. Los procesos de negocio describen un conjunto de actividades que convergen en la obtención de un determinado resultado. Estos procesos de negocio son automatizados por el sistema software.

    ![Diagrama de actividad](https://github.com/juandefrutos/Trabajo-Modelado/Procesos de negocio.png)

|1| Identificar contactos estrechos|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| *Sistema de notificaciones|
|Descripción| Identificar los contactos estrechos de casos positivos a través del bluetooth|  
|Importancia| Alta|
|Actores| *Ciudadanos usuarios|
|Comentarios| Es el principal objetivo de la aplicación|         

|2| Sistema de notificaciones|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| *Identificar contactos estrechos|
|Descripción| Mediante el sistema de notificaciones, la app avisará a los usuarios cuando han estado expuestos a otro usuario que ha sido diagnosticado de COVID y ha introducido el código facilitado por las autoridades sanitarias de su comunidad autónoma|  
|Importancia| Alta|
|Actores| *Comunidad autónoma *Ministerio de sanidad|
|Comentarios| El usuario debe permitir el sistema de notificaciones y estar atento a ellas|         

|3| Generador de identificadores aleatorios|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| *Sistema de 
notificaciones|
|Descripción| Se generan códigos aleatorios que se intercambian con otros dispositivos que tengan la app activa y se encuentren a menos de dos metros. Cada teléfono almacena durante 14 días sus identificadores y los de los dispositivos que han estado cerca|  
|Importancia| Alta|
|Actores| *Desarrollador|
|Comentarios| El emparejamiento de estos códigos nos permitirá establecer los contactos estrechos y enviar la notificación en caso de haber estado con un usuario positivo|         

|4| Nube|
|-----------|-----------|
|Versión| 1.0 (16/11/2020)|
|Dependencias| *Gnerador de códigos aleatorios|
|Descripción| La nube almacena los identificadores generados por el dispositivo cuyo usuario ha introducido el código de positivo facilitado por las autoridades. Estos identificadores son etiquetados como positivos y posteriormente deben ser descargador por los usuarios|  
|Importancia| Alta|
|Actores| *Diseñador *AR|
|Comentarios| Los usuarios deben permitir la descarga de datos de la nube, al menos una vez al día, para ello, se conectarán a internet|         