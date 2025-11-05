##Titulo del proyecto: Monitoreo de seguridad en archivos del sistema



##Fichas Tecnicas##

-----------------------
#Tarea 1 (Titulo): Lectura y Registro de archivos criticos

Función, rol o área de la ciberseguridad relacionada: Modulo encargado en la deteccion de cambios en archivos criticos del sistema y del registro de eventos con fecha y hora.

Entradas esperadas: lectura de todos los archivos dentro del directorio base, incluyendo las subcarpetas.

Salidas esperadas: informacion de cuando y que cambio ocurrio, con fecha y hora del evento.

Descripción del procedimiento: Se leen los archivos criticos y anota cualquier cambio detectado en un archivo de texto, indicando el archivo modificado con su fecha y hora del cambio.

Complejidad técnica: Conocimiento basico en la lectura de archivos, comparar su estado actual con ela archivo previo y registrar los cambios en un archivo txt. Tener un conocimiento en el manejo de rutas y recorre las subcarpetas del misimo directorio.

Controles éticos: Garantizar la confidencialidad de los archivos críticos al no modificar su contenido durante la lectura.

Dependencias: Sistema operativo con permisos adecuados y herramienta de registro para almacenar cambios.

-----------------------


-----------------------
#Tarea 2 (Titulo): Detección de intentos de acceso sospechosos en logs

Función, rol o área de la ciberseguridad relacionada:  Módulo encargado del monitoreo y detección de intentos de acceso no autorizados en registros del sistema, con el objetivo de identificar posibles ataques de fuerza bruta o accesos indebidos.

Entradas esperadas: Archivos de logs con registros de autenticación y eventos del sistema.

Salidas esperadas: Archivo JSON con eventos sospechosos detectados y reporte en formato Markdown con resumen de hallazgos.

Descripción del procedimiento: El sistema analiza los registros del sistema para identificar múltiples intentos fallidos de acceso desde una misma IP. Los eventos sospechosos se clasifican por severidad y se guardan en archivos estructurados y reportes legibles.

Complejidad técnica: Procesamiento y parsing de texto, correlación de eventos, y automatización con Python utilizando librerías estándar.

Controles éticos: Se emplean únicamente datos sintéticos; no se usan registros reales ni información sensible.

Dependencias: Python 3.10+, librerías estándar (re, datetime, json, logging) y entorno local controlado.

-----------------------


-----------------------
#Tarea 3 (Titulo):

Función, rol o área de la ciberseguridad relacionada: 
Entradas esperadas:
Salidas esperadas:
Descripción del procedimiento:
Complejidad técnica:
Controles éticos:
Dependencias:

-----------------------


-----------------------
#Tarea 4 (Titulo):

Función, rol o área de la ciberseguridad relacionada: 
Entradas esperadas:
Salidas esperadas:
Descripción del procedimiento:
Complejidad técnica:
Controles éticos:
Dependencias:

-----------------------

##Roles del equipo: Este proyecto se llevará a cabo respetando la confidencialidad y privacidad de la información del sistema, garantizando no se modifiquen los archivos del sistema durante el proceso de supervisión.

Ana Naybeth Medina Perez| Lectura y registro de archivos criticos
Angel Gabriel Cruz Velazquez| Detección de intentos de acceso sospechosos en logs

##Declaracion Etica y Legal:


-----------------------
