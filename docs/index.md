
## **Distribución automática de chats entrantes**

- Agentes distribuidos en colas de atención.
- Administración de las colas de atención:
	- Creación de colas.
	- Modificación de membresías.
- Segmentación de clientes por medio de un menú de opciones que representan las colas de atención.
- Asignación automática de chats entre los agentes conectados, con estrategia por turnos.
- Transferencia de chats entre agentes y entre colas de atención.
- Transferencia de chats a menús
- Interfaz para establecer el enrutamiento de cada canal de la empresa (WhatsApp, Instagram, Facebook Messenger) de manera que los chats entrantes sean atendidos por un agente, una cola o un menú dependiendo del canal.
- Distribución de chats a agentes asignados específicamente aún si no están en línea.
- Límite de tiempo para el proceso de distribución, especialmente si se tiene activa la opción de invitar los agentes en lugar de unirlos forzadamente.
- Se permite asignar una prioridad al chat para que se reparta primero que los demás.


## **Contenido de los chats**

- Envío y recepción de `imágenes`, `vídeos`, `emojis`, `PDF`, `documentos de Office` y `notas de voz`.
- Se conserva el historial de la conversación sin importar el cambio de estado del chat, ni cuantas veces sea reasignado.
- Historial de archivos enviados y recibidos en el chat.
- El agente puede citar mensajes del cliente al enviarle una respuesta (sólo Api Web WhatsApp)
- El agente recibe mensajes citados por el cliente (en las dos Apis)
- Se puede compartir la ubicación y visualizar la ubicación enviada por un cliente.
- Menús con botones.
- Se ven las reacciones de los clientes a los mensajes.
- Agentes pueden ver las respuestas a estados de WhatsApp
- Envío de texto libre (además de las plantillas aprobadas) para iniciar conversaciones usando la API Business siempre y cuando esté abierta la ventana de las 24 horas.
- Posibilidad de uso de plantillas con contenido multimedia desde la API Business
- Nueva opción de configurar una espera entre mensajes enviados desde el menú (nodo de espera) para evitar enviar mensajes en desorden
- El agente puede ver las respuestas contextualizadas a mensajes publicitarios
- Nueva versión de la API de envío de mensajes que permite el envío de contenido multimedia (imágenes, videos, audios y archivos PDF)
- Opción para integrar asistentes de inteligencia artificial a las opciones del menú
- Ya no se desaparecen los mensajes que el cliente elimina desde WhatsApp
- Soporte multimedia para asistentes de Chat GPT
- Soporte para flujos de WhatsApp
- Opción para que no se eliminen del historial del chat los mensajes eliminados por los usuarios en su WhatsApp


## **Menú de opciones**

- Tipos de opciones del menú:
	- Selección de colas de atención para hablar con un agente.
	- Mensajes de texto para mostrar información de links, horarios de atención, direcciones de sedes, información de contacto, etc.
	- Consultas sencillas a servicios web externos.
	- Solicitud de información a los usuarios ya sea para consultas a servicios web externos o para dejar un registro interno de los datos.
- Posibilidad de tener menú con opciones, o no tener menú y hacer la asignación de un agente directamente.
- Encabezados personalizados por cada submenú en los menús de varios niveles.
- Mensaje general y/o personalizado por opción del menú cuando se asigna un agente al chat.
- Posibilidad de devolverse al menú anterior.
- Recordatorios opcionales al usuario para que seleccione alguna opción del menú cuando ha pasado más de cierto tiempo.
- Resolución automática de chats cuando el usuario no selecciona ninguna opción del menú después de cierto tiempo.
- Opciones al terminar una consulta en el menú, que permite ver de nuevo el menú, hablar con un asesor o finalizar la conversación.
- Mensaje opcional de despedida cuando se termina una consulta en el menú.
- Posibilidad de tener una frase especial a la cual se responde con la asignación del chat a un agente, por ejemplo, si se presenta un link para hacer un pedido y luego se retorna al chat con la información del pedido.
- Solicitud al usuario de consentimiento para ser contactado a través de WhatsApp antes de presentarle el menú de opciones. En Gupshup también se almacena la información si es el caso.
- Opción para mostrar mensaje de despedida cuando un usuario no da su consentimiento de contacto, para no permitirle navegar por el menú.
- Opción para no guardar el consentimiento de contacto y solicitarlo siempre que el cliente escribe al chat aunque ya lo haya aceptado.
- Los bots pueden reaccionar ante envío de stickers.
- Se pueden construir menús con botones.
- Opción del menú para envío de correos con la respuesta recibida por parte del cliente.
- Opción del menú para envío de imágenes.
- Opción para poner emojis de los números en las opciones del menú en lugar de texto plano.
- Las opciones de los menús pueden enviar imágenes, videos, audios y archivos.
- Opción para que luego de un máximo de intentos al ingresar un dato en un chat, se pueda ejecutar alguna opción deseada como por ejemplo repartir el chat.
- Listado de agentes en el nodo de invitación de usuarios en la interfaz de administración de menús.
- Nuevo nodo de correo electrónico y asistente de inteligencia artificial en la interfaz de administración de menús.
- Interfaz para construir menús con botones.
- Los flujos de los menús se pueden dividir en secciones cuando son muy grandes.
- Procesador de entradas del usuario en el menú para no tener que digitar exactamente el número de la opción. Opción para configurar un asistente que reconozca las entradas.
- Uso de middlewares para comunicación del nodo de asistente virtual con servicios de conversión de voz a texto y de texto a voz.
- Configuración del mensaje de resolución del chat por parte del supervisor en los nodos de resolución del chat.
- Configuración de la tipificación a asignarse cuando se usa el nodo de resolución del chat.
- Nodos de diferentes colores para identificarlos más fácilmente.
- Se recuerda zoom y posición de los módulos.
- Se permite importar y exportar módulos y flujos completos.
- Nuevo nodo de chequeo de festivos.
- Se puede invitar a un menú diferente si el chat queda encolado


## **Gestión de chats**

- Monitoreo de los chats en tiempo real.
- Los chats entrantes cuando no hay agentes disponibles se dejan en espera para ser asignados tan pronto como se conecte un agente.
- Opción para iniciar una conversación con un cliente por medio de plantillas aprobadas en la Api Business o con un texto libre en la Api Web WhatsApp.
- Interfaz para el uso de respuestas rápidas que facilitan la reutilización de frases comúnmente enviadas en los chats.
- Clasificación de plantillas y respuestas rápidas, y posibilidad de filtrar por categoría, y buscar por nombre, título o texto.
- Posibilidad de configurar las opciones disponibles cuando el usuario escribe y el agente que atiende el chat no está en línea.
- Notas privadas en los chats para agregar información interna que sólo puede ver el agente y el supervisor.
- Posibilidad de tener chats entre agentes para tener conversaciones internas.
- Notificación al usuario de que no se reciben llamadas de WhatsApp (sólo Api Web WhatsApp).
- Posibilidad de manejar varios números de WhatsApp.
- Posibilidad de conocer cuantos chats entrantes tiene cada agente.
- El menubot se detiene y reanuda con una frase clave.
- El chat es resuelto automáticamente cuando el usuario seleciona una opción que solo muestra un texto
o que consulta un recurso web.
- Directorio de clientes al iniciar una conversación por parte del agente, para los casos en los que no está disponible el número telefónico.
- Implementación de manejo especial cuando un usuario escribe al chat por fuera de los horarios de atención.
- Resolución de chats en bloque por parte del supervisor y del agente.
- Opción de configuración de las líneas para que los chats entrantes sean repartidos directamente a un agente o a un grupo de agentes.
- Opción para que agentes no puedan editar ni borrar mensajes.
- Interfaz de administración de listas negras para evitar escribir a contactos a los que no esté permitido enviar mensajes.
- Opción para repartir el chat a una cola de agentes no sólo al seleccionar una opción del menú sino también cuando el cliente responde correctamente una o varias preguntas.
- Opción para que al transferir un chat a una sala sin agentes disponibles, el chat quede encolado y se atienda cuando se encuentre un agente disponible.
- Opción para iniciar conversación desde el listado de contactos.
- Opción de asignar chats en bloque a una cola, agente o menú
- Posibilidad de consultar la notificación de lectura de los mensajes enviados a través de la API Business.
- Soporte para uso de API de servicios de inteligencia artificial desde el menú.
- Verificación de optin (aceptación de contacto a través de WhatsApp) antes de iniciar una conversación.
- Interfaz de tipificación de conversaciones.
- Uso de espacios para agrupar los chats. Cada chat queda con una etiqueta de color que permite identificar a qué espacio pertenece.
- Interfaz de administración de etiquetas/espacios.
- Actualización en tiempo real de las estadísticas del dashboard.
- Interfaz para que el supervisor puede configurar el mensaje de resolución del chat.


## **Gestión de clientes**

- Creación y modificación de información básica del cliente.
- Administración de permiso de consentimiento para contacto a través de WhatsApp.
- Interfaz para almacenar masivamente el permiso de consentimiento para contacto a través de WhatsApp, por medio de un archivo con el listado de contactos.
- Gestión del permiso de consentimiento para contacto a través de WhatsApp en diferentes niveles: general para todas las cuentas, específico por canal, y específico por canal y cuenta.
- Nombre de los chats de WhatsApp puede ser el mismo del contacto guardado en el celular empresarial.
- Opción para asignar un agente o un grupo de agentes específicamente para la atención de un cliente.
- Opción para exportar los contactos creados en la plataforma, tanto en formato estándar como en un formato que permite importarlos desde la aplicación de contactos de Google.
- Se agrega opción para que los contactos exportados desde Google se puedan importar en la plataforma.
- Se permite mezclar contactos para unificar sus cuentas.
- Creación, modificación y eliminación de negocios.
- Ver y exportar los contactos de cada negocio desde el listado de negocios.
- Búsqueda mejorada en el listado de contactos.
- Visualización de cuentas en nueva columna del listado de contactos.
- Mejora en la distribución al visualizar las cuentas de un contacto.
- Opción para importar contactos desde archivos de Excel.
- Opción para eliminar contactos
- Opción para eliminar optin (aceptación de contacto a través de WhatsApp)


## **Gestión de agentes**

- Interfaz de administración de agentes (creación y modificación)
- Posibilidad de crear una cantidad limitada de agentes y un límite independiente de agentes con sesiones activas.
- Monitoreo de agentes para conocer su estado, tiempo de pausa y motivo de pausa.
- Visualización en tiempo real del cambio de estado de los agentes
- Opción para asignar un máximo de chats por agente
- Opción para visualizar sólo los agentes logueados en la plataforma desde el monitoreo
- Se puede asignar una campaña y subcampaña por defecto a cada agente


## **Operaciones de agente**

- Interfaz de creación de motivos de pausa.
- Opciones de pausa y despausa en la interfaz del agente.
- Sólo se permite una sesión activa por agente. Si el agente inicia una nueva sesión en otro dispositivo sin haber cerrado la anterior, se cierran todas las sesiones
- Opción para que el supervisor pueda pausar, despausar y desloguear agentes


## **Interfaz web**

- Interfaz web diferenciada para el agente y el supervisor.
- Notificaciones de mensajes nuevos en la interfaz web.
- Temas claro y oscuro disponibles en la interfaz web.
- Color de fondo en los mensajes diferenciado para cada integrante del chat.
- Logo personalizable en las páginas de inicio del agente y del supervisor.
- Posibilidad de poner nombre personalizado a los chats.
- Búsqueda de chats por número telefónico y por nombre del usuario si está disponible.
- Dashboard de reportes generales, por sala y por agentes, y detalle de chats en cada categoría.
- Plataforma en inglés y español.
- El agente puede elegir por cual numero quiere contactar a un cliente.
- Supervisor y agente pueden agregar tags a un chat para clasificar las conversaciones.
- Interfaz de administración de plantillas y de gestión de aprobación de las mismas por parte de Facebook.
- Opción para crear plantillas generales a todos las canales creados en la empresa.
- Opción para mostrar u ocultar toda la información de eventos de invitaciones, entradas y salidas, cambio de nombre y cambio de avatar, para que sólo se vean los mensajes en los chats.
- Notificaciones de desconexión de WhatsApp para impedir errores en el envío y recepción de mensajes.
- Interfaz de administración de canales de Web WhatsApp, WhatsApp Business e Instagram, que permite vincular y desvincular las líneas.
- Estilos diferenciados en la interfaz de inicio de sesión del supervisor y del agente.
- Nuevo diseño de la interfaz para iniciar una conversación con un contacto, que permite agregar contactos, agregar cuentas a contactos y seleccionar una de las cuentas del contacto.
- Nuevo campo para asignar el avatar de la cola, que también se usa para el espacio respectivo
- Nueva categoría de variables de contacto que cargan automáticamente la información del contacto al enviar plantillas desde la interfaz del agente.
- Interfaz de creación de plantillas con imágenes, videos, audios y/o archivos PDF embebidos en el mensaje.
- Búsqueda rápida de plantillas utilizando el caracter / .
- Búsqueda mejorada para obtener más de 50 salas como resultado del filtro de la búsqueda
- Posibilidad de gestionar los grupos de WhatsApp desde la interfaz de agente y supervisor
- Los grupos de WhastApp están en una sección diferenciada del listado de chats
- El agente puede ver los miembros de las salas (sólo puede ver agentes y clientes)
- Interfaz de administración de campañas y subcampañas
- Se permite activar y desactivar canales desde la interfaz de administración de canales.



## **Reportes**

- **Chats pendientes:** Chats en los que el cliente está a la espera de respuesta por parte del agente.
- **Chats en seguimiento**: Chats no resueltos, respondidos por un agente, a la espera de respuesta por parte del cliente.
- **Chats abiertos:** Chats no resueltos, sin agente asignado. Normalmente son chats en los que el cliente no ha seleccionado ninguna opción del menú.
- **Chats nuevos:** Chats entrantes de nuevos números telefónicos consultados entre dos fechas.
- **Chats resueltos:** Chats marcados como resueltos por parte del agente o supervisor entre dos fechas.
- Para cada una de las categorías se muestra el total y se permite ver el listado detallado de chats.
- Se puede monitorear el estado de las conexiones de los canales con la Api Web WhatsApp.
- Se tiene una pagina que almacena todas las características de `iKono Chat` y sus nuevos cambios.
- Tabla de agentes con cantidad de chats activos discriminados en chats pendientes y chats en seguimiento. También se muestra los chats resueltos, chats entrantes y tiempo promedio de respuesta por agente, en un rango de fechas.
- Tabla de opciones del menú con cantidad de chats activos discriminados en chats pendientes y chats en seguimiento. También se muestra los chats resueltos y chats entrantes por opción del menú, en un rango de fechas.
- Dashboard para que el agente pueda ver la información de sus chats.
- Se agrega campaña y subcampaña a cada conversación para tener más opciones de generación de reportes.
- Campo de tiempo de primera respuesta del agente desde que se une al chat.
- campo de tiempo de primera respuesta del agente desde que el chat entra a la cola.
- Nuevo reporte de detalle de pausas
- Nuevo reporte de total de chats entrantes por cada canal
- Nuevo reporte de total de chats por campaña y subcampaña
- Nombre personalizado en cada nodo de la interfaz de administración de menús
- Se puede seleccionar una campaña y subcampaña al iniciar conversación para ver estos datos en los reportes
- Filtros de fechas en reportes que se conservan para todos los dashboards
- Dashboard de nivel de servicio y dashboard mensual
- Reporte de tipificaciones y reporte de estados de entradas a cola



## **Bridges**

- Se tiene soporte con la Api Business **Gupshup** para la comunicación con WhatsApp.
- Se tiene soporte con la Api Web WhatsApp **WhatsApp** multi dispositivo.
- Se tiene soporte con la Api Business de **Twilio** para la comunicación con WhatsApp.
- Se tiene soporte con **Instagram** para envío y recepción de chats a través de la plataforma de `iKono Chat`.
- Se tiene soporte con **Facebook Messenger** para envío y recepción de chats a través de la plataforma de `iKono Chat`.
- Se tiene soporte para envío y recepción de chats utilizando la **WhatsApp Business API Cloud**, incluyendo mensajes interactivos con botones y listas.


## **APIs**
- ### API Sender
    - Funciona con la versión multi dispositivo de **WhatsApp**.
    - Se pueden enviar mensajes de texto mediante WhatsApp usando un usuario registrado en la plataforma `iKono Chat`.
- ### WAPI
    - Se pueden crear usuarios utilizando el correo electrónico.
    - Permite a cada usuario iniciar sesión con su número personal o de empresa en la API web de WhatsApp solicitando un código QR.
    - Permite a cada usuario cerrar sesión con WhatsApp e iniciar sesión con otro número.
    - No hay límite en la cantidad de usuarios.
    - Funciona con la versión multi dispositivo de **WhatsApp**.


## **Integraciones**

- `Widget iKono Chat`: Permite insertar una sala donde usuarios pueden hablar con un chatbot o un agente.
- Creación de aplicación de escritorio de `iKono Chat`.
