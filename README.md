# taskbot
Chatbot para registro de tareas en el Google Calendar.

## Requisitos
* Python > 3.6
* La herramienta de administración de paquetes pip.
* Un proyecto de Google Cloud Platform con la API habilitada. Consulta https://developers.google.com/workspace/guides/create-project
* Credenciales de autorización para una aplicación de escritorio. Para crear credenciales para una aplicación de escritorio, consulta https://developers.google.com/workspace/guides/create-credentials
  * NOTA: Renombrar el archivo JSON obtenido en este paso a 'credentials.json'.
* Una cuenta de Google con Google Calendar habilitado

## Uso
Después de cumplir con los requisitos, se puede ejecutar la conversación de manera habitual.
NOTA: Si al ejecutar la conversación el programa quickstart.py no encuentra el archivo credentials.json, poner el path completo hacia este archivo dentro de quickstart.py en la línea 30.
