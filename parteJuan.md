|1| Fuerzas del orden  |
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias|Sistema de notificaciones y checkeo del cumplimiento de la cuarentena|                
|Descripción| Este subsistema es el encargado de checkear el cumplimiento de las cuarentenas y el cumplimiento de las restricciones impuestas por las autoridades competentes. Dicha comprobacion se realiza tras el recibo de notificaciones por parte de los centros de salud los cuales indican el positivo de la persona  |  
|Importancia| Alta |  
|Prioridad| Media |
|Comentarios| Este subsitema se encargara del control de las normas impuestas realizando controles y poniendo multas a las personas las cuales incumplan las normas|


|2| Rastreadores  |
|-----------|-----------|
|Versión| 1.0 (30/11/2020)|
|Dependencias|Sistema de notificaciones, Identificar contactos y alertas de usuarios|                
|Descripción| En este subsistema se llevara a cabo la contratacion de personal cualificado denominado rastreador encargado de realizar el seguimiento de los contagios y contactos directos el cual informara al usuario en caso de contacto con positivo|  
|Importancia| Media |  
|Prioridad| Baja |
|Comentarios| Los rastreadores se contratan con la intencion de controlar posibles personas las cuales no tengan acceso a un dispositivo smartphone |


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