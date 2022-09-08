
## **Colas de atención**

- Agentes distribuidos en colas de atención.
 - Administración de las colas de atención:
	 - Creación de colas.
	 - Modificación de membresías.
- Segmentación de clientes por medio de un menú de opciones que representan las colas de atención.
- Asignación automática de chats entre los agentes conectados, con estrategia por turnos.
- Transferencia de chats entre agentes y entre colas de atención.


## **Contenido de los chats**

- Envío y recepción de `imágenes`, `vídeos`, `emojis`, `PDF`, `documentos de Office` y `notas de voz`.
- Se conserva el historial de la conversación sin importar el cambio de estado del chat, ni cuantas veces sea reasignado.
- Historial de archivos enviados y recibidos en el chat.
- El agente puede citar mensajes del cliente al enviarle una respuesta (sólo `API` no oficial)
- El agente recibe mensajes citados por el cliente (en las dos `APIs`)
- Se puede compartir la ubicación y visualizar la ubicación enviada por un cliente.
- Menús con botones.


## **Menú de opciones**

- Tipos de opciones del menú:
	- Selección de colas de atención para hablar con un agente.
	- Mensajes de texto para mostrar información de links, horarios de atención, direcciones de sedes, información de contacto, etc.
	- Consultas sencillas a servicios web externos.
	- Solicitud de información a los usuarios ya sea para consultas a servicios web externos o para dejar un registro interno de los datos.
- Posibilidad de tener menú con opciones, o no tener menú y hacer la asignación de un agente directamente.
- Configuración de menús de 1, 2 y 3 niveles.
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

## **Gestión de chats**

- Monitoreo de los chats en tiempo real.
- Los chats entrantes cuando no hay agentes disponibles se dejan en espera para ser asignados tan pronto como se conecte un agente.
- Opción para iniciar una conversación con un cliente por medio de plantillas aprobadas en la api oficial o con un texto libre en la `API` no oficial.
- Interfaz para el uso de respuestas rápidas que facilitan la reutilización de frases comúnmente enviadas en los chats.
- Clasificación de plantillas y respuestas rápidas, y posibilidad de filtrar por categoría, y buscar por nombre, título o texto.
- Opción configurable para manejo de chat cuando el agente asignado no está en línea:
	- No hacer nada.
	- Transferencia automática a otro agente de la misma área.
	- Menú para que el usuario decida si desea ser transferido o si desea ver el menú y elegir otra opción.
- Notas privadas en los chats para agregar información interna que sólo puede ver el agente y el supervisor.
- Posibilidad de tener chats entre agentes para tener conversaciones internas.
- Notificación al usuario de que no se reciben llamadas de WhatsApp (sólo no oficial)
- Posibilidad de manejar varios números de WhatsApp.
- Posibilidad de conocer cuantos chats entrantes tiene cada agente.
- El menubot se detiene y reanuda con una frase clave.
- El chat es resuelto automáticamente cuando el usuario seleciona una opción que solo muestra un texto
o que consulta un recurso web.
- Directorio de clientes al iniciar una conversación por parte del agente, para los casos en los que no está disponible el número telefónico.
- Implementación de manejo especial cuando un usuario escribe al chat por fuera de los horarios de atención.

## **Gestión de clientes**

- Creación y modificación de información básica del cliente.
- Administración de permiso de consentimiento para contacto a través de WhatsApp.
- Interfaz para almacenar masivamente el permiso de consentimiento para contacto a través de WhatsApp, por medio de un archivo con el listado de contactos.


## **Gestión de agentes**

- Interfaz de administración de agentes (creación y modificación)
- Posibilidad de crear una cantidad limitada de agentes y un límite independiente de agentes con sesiones activas.


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
- Opción para mostrar u ocultar toda la información de eventos de invitaciones, entradas y salidas, cambio de nombre y cambio de avatar, para que sólo se vean los mensajes en los chats.
- Notificaciones de desconexión de WhatsApp para impedir errores en el envío y recepción de mensajes.

## **Reportes**

- **Chats pendientes:** Chats en los que el cliente está a la espera de respuesta por parte del agente.
- **Chats en seguimiento**: Chats no resueltos, respondidos por un agente, a la espera de respuesta por parte del cliente.
- **Chats abiertos:** Chats no resueltos, sin agente asignado. Normalmente son chats en los que el cliente no ha seleccionado ninguna opción del menú.
- **Chats nuevos:** Chats entrantes de nuevos números telefónicos consultados entre dos fechas.
- **Chats resueltos:** Chats marcados como resueltos por parte del agente o supervisor entre dos fechas.
- Para cada una de las categorías se muestra el total y se permite ver el listado detallado de chats.
- Se puede monitorear el estado del bridge no oficial.
- Se tiene una pagina que almacena todas las características de `iKono Chat` y sus nuevos cambios.
- Tabla de agentes con cantidad de chats activos discriminados en chats pendientes y chats en seguimiento. También se muestra los chats resueltos, chats entrantes y tiempo promedio de respuesta por agente, en un rango de fechas.
- Tabla de opciones del menú con cantidad de chats activos discriminados en chats pendientes y chats en seguimiento. También se muestra los chats resueltos y chats entrantes por opción del menú, en un rango de fechas.
- Dashboard para que el agente pueda ver la información de sus chats.

## **Bridge**

- Se tiene soporte con la API oficial de **Gupshup** para la comunicación con WhatsApp.
- Se tiene soporte con la API no oficial **WhatsApp** multi dispositivo.
- Se tiene soporte con la API oficial de **Twilio** para la comunicación con WhatsApp.
- Se tiene soporte con **Instagram** para envío y recepción de chats a través de la plataforma de `iKono Chat`.

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
