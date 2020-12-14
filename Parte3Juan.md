|1| Informar de Cuarentenas |
|---------------|------------|
|[Versión] |1.0 15/12/2020| 
|Dependencias| Sistema de Notificaciones, Sistema de identificacion de posibles contagios y sistema de control de cuarentena|
|Precondidcion| Usuario positivo |
|Descripción| Se invova cuando un usuario es positivo y es posible informar a las fuerzas del orden para comprobrar el cumplimiento |
|Secuencia Normal|1.Usuario se encuentra en lista de pruebas.  2.Usuario acude a prueba medica.  3.Usuario Positivo  4. Informar de cuarentena.|
|Postcondicion| Cumplir o no cumplir la cuarentena  |
|Excepciones| Si Usuario no es Positivo no tiene que guardar cuarentena|
|Importancia| Alta  |
|Prioridad| Alta |
|Comentarios| |

Requisitos de Usuario para los Centros de Salud  
1. Enviar Datos a las Autonomias
2. Añadir Usuario a la Lista Pruebas Medicas
3. Recibir Informacion
4. Informar Fuerzas del Orden
5. Uusario Positivo
6. Informar a Contactos Estrechos
7. Asignar Codigo
8. Comprobrar Lista Pruebas
9. Informar Cuarentenas

Requisitos de Usuario para las Autonomias  
1. Recoger Datos
2. Notificar Ministerio de Sanidad
3. Realizar Estadistica
4. Comprobar datos
5. Enviar Datos y Estadistica
6. Nuevas normas
7. Informar Usuarios
8. Informar Centros de Salud


Requisitos Funcionales Centros de Salud  
1. El sistema enviara un codigo al usuario cuando sea positivo
2. El sistema informara al usuario de la prueba medica
3. El sistema informara a las fuerzas del orden de la no presencia del usuario convocado para la prueba medica
4. El sistema permitira el registro de todos los usuarios
5. El sistema permitira enviar notificaciones a las fuerzas del orden
6. El sistema visualizara el check del cumplimiento de las cuarentenas comprobadas por las fuerzas del orden
7. El sistema permitira introdrucir usuarios a lista de pruebas medicas
8. El sistema permitira localizar los usuarios en la lista de la pruebas medicas 
9. El sistema enviara una notificacion a los usuarios positivos
10. El sistema enviara una notificacion a los contactos estrechos de un usuario positivo
11. El sistema notificara a las fuerzas del orden la comprobacion de las cuarentenas
12. El sistema tendra acceso al checkeo de las comprobacion de cuarentenas
13. El sistema creara codigos aleatorios y unicos
14. El sistema se comunicara con las autonomias
15. El sistema recogera informacion de diferentes actores
16. El sistema enviara datos a las autonomias

|1| El sistema enviara un codigo al usuario cuando sea positivo|
|---------------|------------|
|[Versión] |1.0 15/12/2020| 
|Dependencias| Sistema de control de PCR|
|Descripción| El sistema debe enviar un codigo cuando un usuario es positivo, para tener localizado al usuarios con ese codigo unico|
|Importancia| Alta|
|Prioridad| Alta |
|Estado| Aprobado|
|Comentarios| Este codigo sera unico y se generara de forma automatia|

|2| El sistema informara al usuario de la prueba medica |
|---------------|------------|
|[Versión] |1.0 15/12/2020| 
|Dependencias|Sistema de control de PCR,Sistema de identificacion de posibles contagios,sistema de localizacion,sistema de notificaciones|
|Descripción|Se debera informar al usuario de que debera acudir al centro de salud a realizarse la PCR.|
|Importancia| Alta|
|Prioridad| Alta |
|Estado| Aprobado|
|Comentarios|Solo se le informar, pero el usuario podra acudir o no.|


Requisitos Funcionales Autonomias

1. El sistema se comunicara con el Ministerio de Sanidad
2. El sistema se comunicara con los centros de la salud respectivos
3. El sistema recogera todos los resultados de los usuarios
4. El sistema creara una estadistica con los datos recogidos
5. El sistema evaluara las estadistica, con el fin de edurecer las restricciones o ablandarlas
6. El sistema enviara los datos y estadisticas realizadas
7. El sistema informara a los usuarios de las nuevas normas
8. EL sistema informara a los centros de salud de las nuevas normas




# 6.6 Requisitos de Integracion del Sistema

|1|El sistema usara Base de Datos|
|---------------|------------|
|[Versión] |1.0 15/12/2020| 
|Dependencias| Sistema de creacion de estadistica y Sistema de identificacion de posibles contagios |
|Descripción| Todo el sistema tendra una base de datos general donde se guardara la informacion de los usuarios, hasta que sea insignificante donde se realizara la eliminacion de dicha informacion |
|Importancia| Alta  |
|Prioridad| Alta |
|Estado| Aprobado |
|Comentarios| La informacion sera eliminada cuando la pandemia finalice o sea irrelevante |

|2|EL sistema usara uso de datos del movil|
|---------------|------------|
|[Versión] |1.0 15/12/2020| 
|Dependencias| Todo el sistema  |
|Descripción| Los datos del movil se usuaran para tener la app actualizada en todo momento,para saber si existe un usuario que pueda ser contacto estrecho |
|Importancia| Alta  |
|Prioridad| Alta |
|Estado| Aprobado|
|Comentarios| |

|3|El sistema tenrda que disponer del GPS|
|---------------|------------|
|[Versión] |1.0 15/12/2020| 
|Dependencias| Todo el sistema|
|Descripción| Es la intregacion mas importante ya que es como se identifican los contactos estrechos, se tiene controlodo un usuario positivo, sabiendo que el usuario se encuentra en su domicilio.|
|Importancia| Alta  |
|Prioridad| Alta |
|Estado| Aprobado|
|Comentarios| Para el control de las cuarentenas se impondra un rango de 20 metros|

|4|El sistema cumplira la Ley de Proteccion de Datos |
|---------------|------------|
|[Versión] |1.0 15/12/2020| 
|Dependencias| Todo el sistema |
|Descripción| La ley de proteccion se cumplira en todo momento actualizancion la aplicacion si es necesario en los momentos en los que la ley pueda cambiar |
|Importancia| Alta  |
|Prioridad| Alta |
|Estado| Aprobado |
|Comentarios|El Gobierno cambiara la Ley de Proteccion de Datos a nuestra disposicion |

|5|El sistema no permite usuarios duplicados y eliminacion de usuarios|
|---------------|------------|
|[Versión] |1.0 15/12/2020| 
|Dependencias| Todo el sistema |
|Descripción| No se permite eliminacion ni usuarios duplicados, con esto se realiza que los usuarios no puedan eliminar la informacion hacia el o saltarse las cuarentenas|

|Importancia| Alta  |
|Prioridad| Alta |
|Estado| Aprobado |
|Comentarios| |


