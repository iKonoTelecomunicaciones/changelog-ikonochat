### **[ 2024 - 08 - 30 ]**
- Nuevo reporte de detalle de pausas
- Nuevo reporte de total de chats entrantes por cada canal
- Nuevo reporte de total de chats por campaña y subcampaña
- Nombre personalizado en cada nodo de la interfaz de administración de menús
- Listado de agentes en el nodo de invitación de usuarios en la interfaz de administración de menús
- Nuevo nodo de correo electrónico y asistente de inteligencia artificial en la interfaz de administración de menús
- Interfaz para construir menús con botones
- Posibilidad de gestionar los grupos de WhatsApp desde la interfaz de agente y supervisor
- Interfaz de tipificación de conversaciones
- Búsqueda mejorada para obtener más de 50 salas como resultado del filtro de la búsqueda

---

### **[ 2024 - 07 - 05 ]**
- Se agrega campaña y subcampaña a cada conversación para tener más opciones de generación de reportes
- Interfaz de creación de plantillas con imágenes, videos, audios y/o archivos PDF embebidos en el mensaje
- Campo de tiempo de primera respuesta del agente desde que se une al chat
- campo de tiempo de primera respuesta del agente desde que el chat entra a la cola
- Búsqueda rápida de plantillas utilizando el caracter /

---

### **[ 2024 - 05 - 24 ]**
- Nueva versión de la API de envío de mensajes que permite el envío de contenido multimedia (imágenes, videos, audios y archivos PDF)
- Nueva categoría de variables de contacto que cargan automáticamente la información del contacto al enviar plantillas desde la interfaz del agente.
- Opción para integrar asistentes de inteligencia artificial a las opciones del menú

---

### **[ 2024 - 05 - 10 ]**
- Nueva opción de configurar una espera entre mensajes enviados desde el menú (nodo de espera) para evitar enviar mensajes en desorden
- Verificación de optin (aceptación de contacto a través de WhatsApp) antes de iniciar una conversación
- Opción para visualizar sólo los agentes logueados en la plataforma desde el monitoreo
- El agente puede ver las respuestas contextualizadas a mensajes publicitarios
- Opción para eliminar optin (aceptación de contacto a través de WhatsApp)

---

### **[ 2024 - 04 - 15 ]**
- Agentes pueden ver las respuestas a estados de WhatsApp
- Se pueden poner colores a los tags
- Campo para asignar máximo de chats por agente en interfaz de administración de agentes
- Se puede enviar texto libre (además de las plantillas aprobadas) para iniciar conversaciones usando la API Business siempre y cuando esté abierta la ventana de las 24 horas.
- Posibilidad de hacer transferencias a menús
- Visualización en tiempo real del cambio de estado de los agentes
- Posibilidad de consultar la notificación de lectura de los mensajes enviados a través de la API Business
- Soporte para uso de API de servicios de inteligencia artificial desde el menú
- Soporte para implementación de subrutinas en el menú
- Posibilidad de uso de plantillas con contenido multimedia desde la API Business

---

### **[ 2024 - 01 - 26 ]**
- Uso de espacios para agrupar los chats que están activos en cada cola
- Nuevo campo para asignar el avatar de la cola, que también se usa para el espacio respectivo
- Sólo se permite una sesión activa por agente. Si el agente inicia una nueva sesión en otro dispositivo sin haber cerrado la anterior, se cierran todas las sesiones
- Límite de tiempo para el proceso de distribución, especialmente si se tiene activa la opción de invitar los agentes en lugar de unirlos forzadamente
- Posibilidad de configurar las opciones disponibles cuando el usuario escribe y el agente que atiende el chat no está en línea
- Nuevo recurso /redirect para verificar si hay un agente asignado al chat y decidir si se invoca /transfer_user o /assign
- Opción para enviar mensajes de texto libre además de plantillas cuando se inicia una conversación usando la API de WhatsApp Business (funciona si el mensaje se envía dentro de la ventana de las 24 horas)
- Opción para asignar un máximo de chats por agente
- Opción de asignar chats en bloque a una cola, agente o menú
- Notificación de asignación al igual que la notificación de transferencia
- Nuevo recurso web para unir y expulsar usuarios de una sala
- Opción para que el supervisor pueda pausar, despausar y desloguear agentes
- Validaciones avanzadas en el flujo de los menús
- Nuevo nodo y recurso web para asignar variables internas y externas en el menú

  ---

### **[ 2023 - 11 - 20 ]**
- Se puede ver el estado del chat (pendiente, en seguimiento, resuelto. etc) por medio de un indicador con colores sobre el avatar de cada chat.
- Soporte para envío y recepción de ubicaciones en bridge de Gupshup
- Soporte para envío y recepción de notificaiones de lectura (doble chulo azul) (sólo aplica si la aplicación está alojada en la Cloud API)
- Soporte para envío y recepción de reacciones (sólo aplica si la aplicación está alojada en la Cloud API, y el agente no puede reaccionar a mensajes que él mismo haya enviado)

  ---

### **[ 2023 - 10 - 20 ]**
- Se tiene soporte para envío y recepción de chats utilizando la **WhatsApp Business API Cloud**, incluyendo mensajes interactivos con botones y listas.
- Opción para eliminar contactos

  ---

### **[ 2023 - 10 - 06 ]**
- Ver y exportar los contactos de cada empresa desde el listado de empresas.
- Opción para iniciar conversación desde el listado de contactos.
- Reestructuracioń de listas negras para incluir el contacto completo y no sólo el número telefónico.

  ---

### **[ 2023 - 09 - 08 ]**
- Búsqueda mejorada en el listado de contactos.
- Visualización de cuentas en nueva columna del listado de contactos.
- Mejora en la distribución al visualizar las cuentas de un contacto.
- Estilos diferenciados en la interfaz de inicio de sesión del supervisor y del agente.
- Nuevo diseño de la interfaz para iniciar una conversación con un contacto, que permite agregar contactos, agregar cuentas a contactos y seleccionar una de las cuentas del contacto.
- Opción para importar contactos desde archivos de Excel.

  ---

### **[ 2023 - 07 - 17 ]**
- Se agrega opción para que luego de un máximo de intentos al ingresar un dato en un chat, se pueda ejecutar alguna opción deseada como por ejemplo repartir el chat.
- Se agrega opción para que al transferir un chat a una sala sin agentes disponibles, el chat quede encolado y se atienda cuando se encuentre un agente disponible.
- Gestión del permiso de consentimiento para contacto a través de WhatsApp en diferentes niveles: general para todas las cuentas, específico por canal, y específico por canal y cuenta.
- Se agrega opción para exportar los contactos creados en la plataforma, tanto en formato estándar como en un formato que permite importarlos desde la aplicación de contactos de Google.
- Se agrega opción para que los contactos exportados desde Google se puedan importar en la plataforma.
- Se permite mezclar contactos para unificar sus cuentas.
- Opción para crear plantillas generales a todos las canales creados en la empresa.
- Creación, modificación y eliminación de negocios.

  ---

### **[ 2023 - 03 - 17 ]**
- Se agrega interfaz para establecer el enrutamiento de cada canal de la empresa (WhatsApp, Instagram, Facebook) de manera que los chats entrantes sean atendidos por un agente, una cola o un menú, dependiendo del canal.
- Distribución de chats a agentes asignados específicamente aún si no están en línea.
- Las opciones de los menús ahora pueden enviar imágenes, videos, audios y archivos.

  ---

### **[ 2023 - 02 - 16 ]**
- Interfaz de gestión de colas de atención, que permite asignar y remover agentes de cada cola.
- Opción para visualizar las colas en las que está un agente.
- Opción para visualizar los agentes asignados a una cola.
- Monitoreo de agentes para conocer su estado, tiempo de pausa y motivo de pausa.
- Integración con Facebook Messenger.

  ---

### **[ 2022 - 12 - 22 ]**
- Resolución de chats en bloque no sólo por parte del supervisor sino también por parte del agente.
- Opción para repartir el chat a una cola de agentes no sólo al seleccionar una opción del menú sino también cuando el cliente responde correctamente una o varias preguntas.
- Nueva distribución del menú de administración en la interfaz del supervisor.
- Se deshabilitan operaciones sobre el chat cuando el agente lo transfiere, para que ya no tenga gestión sobre él.
- Opción para poner emojis de los números en las opciones del menú en lugar de texto plano.
- Mejora en el servicio de la base de datos y adaptación de cambios en los scripts de instalación automática de nuevos clientes.
- Corrección de bugs en la creación de listas negras.
- Interfaz de creación de motivos de pausa.
- Opciones de pausa y despausa en la interfaz del agente.

  ---

### **[ 2022 - 11 - 21 ]**
- Resolución de chats en bloque.
- Nombre de los chats de WhatsApp puede ser el mismo del contacto guardado en el celular empresarial.
- Opción para asignar un agente o un grupo de agentes específicamente para la atención de un cliente.
- Opción de configuración de las líneas para que los chats entrantes sean repartidos directamente a un agente o a un grupo de agentes
- Opción para que agentes no puedan editar ni borrar mensajes.
- Interfaz de administración de canales de Web WhatsApp, WhatsApp Business e Instagram, que permite vincular y desvincular las líneas.
- Interfaz de administración de listas negras para evitar escribir a contactos a los que no esté permitido enviar mensajes.

  ---

### **[ 2022 - 09 - 08 ]**
- Notificaciones de desconexión de WhatsApp para impedir errores en el envío y recepción de mensajes.
- Opción del menú para envío de correos con la respuesta recibida por parte del cliente.
- Opción del menú para envío de imágenes.
- Opción para mostrar mensaje de despedida cuando un usuario no acepta optin para no permitirle navegar por el menú.
- Opción para no guardar optin y mostrarlo siempre que el cliente escribe al chat aunque ya lo haya aceptado.

  ---

### **[ 2022 - 07 - 27 ]**
- Implementación de manejo especial cuando un usuario escribe al chat por fuera de los horarios de atención.
- Creación de aplicación de escritorio de iKono Chat.
- Dashboard para que el agente pueda ver la información de sus chats.

  ---

### **[ 2022 - 06 - 06 ]**
- Interfaz mejorada de creación de plantillas, con funcionalidad de solicitud de aprobación de plantillas a Facebook para la API Business y creación de categorías por empresa.
- Corrección de bug de filtro de plantillas en algunos clientes en los que está fallando.
- Directorio de clientes al iniciar una conversación por parte del agente, para los casos en los que no está disponible el número telefónico.
- En los chats se puede ocultar toda la información de eventos de invitaciones, entradas y salidas, cambio de nombre y cambio de avatar, para que sólo se vean los mensajes.
- Se corrige bug que permitia a los agentes entrar en la interfaz de supervisor.
- El `Widget iKono Chat` ahora permite chats con agentes o sin agentes y la sesión de un cliente se preserva por x cantidad de tiempo configurable.

  ---

### **[ 2022 - 05 - 06 ]**

- El menubot se detiene y reanuda con una frase clave.
- El chat es resuelto automáticamente cuando el usuario seleciona una opción que solo muestra un texto
o que consulta un recurso web.
- La API de WhatsApp Business con el BSP Gupshup soporta mensajes con botones. Ahora se pueden construir menús con botones.
- Actualización de la interfaz web para incorporar los cambios del motor de chat original. Se unifican los estilos en todos los niveles de la plataforma.
- Ahora se puede compartir la ubicación y visualizar la ubicación enviada por un cliente.
- Creación de una interfaz de administración de plantillas.
- Optimización de la implementación de clientes nuevos.
- Se agrega nueva columna a todos los reportes para mostrar el número telefónico del contacto.
 ---

### **[ 2022 - 02 - 11 ]**

- Nuevo servicio API (`WAPI`) que expone un recurso web para hacer login y logout a través de WhatsApp.
- `WAPI` permite crear sesiones con WhatsApp solo con el correo electrónico del usuario.
- Nueva integración -> `Widget iKono Chat` que permite a invitados escribir en una sala de `iKono Chat`, esta sala puede tener un chatbot o agentes dentro.
- El supervisor ahora puede ejecutar comandos de los bridges.
- *Corrección:* Se corrige el mensaje de que no se reciben llamadas por WhatsApp.
- *Corrección:* Se corrige el cambio de nombre de las salas cuando se tiene habilitado el campo `private_chat_portal_meta` de la API web WhatsApp.

 ---

### **[ 2022 - 01 - 28 ]**

- Envío y recepción de videos desde la aplicación móvil.
- Se habilita la administración del consentimiento de contacto a través de WhatsApp por cada número que tenga la empresa y no globalmente.
- Se eliminan idiomas de los cuales no tenemos soporte en la plataforma `iKono Chat` -> tenemos **inglés** y **español**.
- Se agrega la columna de tiempo promedio de respuesta por agente a la tabla de reportes por agente.
- Se agrega un proceso automático de copias diarias de las bases de datos de la plataforma `iKono Chat`.
- Ahora la `API Sender` puede notificar si un número no existe en WhatsApp.
- Ahora `iKono Chat` notifica al agente si un número no existe en WhatsApp al iniciar una conversación.

 ---

### **[ 2022 - 01 - 14 ]**

- Envío y recepción de chats de Instagram a través de la plataforma de `iKono Chat`.
- Se corrige inconveniente con el certificado SSL de las URLs de acceso para supervisor y agente, creando un certificado global que facilita la administración de la seguridad.
- Se agrega la columna de chats entrantes por agente a la tabla de reportes por agente.
- Ahora la `API Sender` funciona con la versión multi dispositivo de WhatsApp.

 ---

### **[ 2021 - 11 - 26 ]**

- Ahora supervisor y agente pueden agregar tags a un chat para clasificar las conversaciones.
- Ahora se puede utilizar la nueva versión de WhatsApp multidevice para la comunicación con los clientes.

 ---

### **[ 2021 - 10 - 29 ]**

- Ahora los bots podrán reaccionar ante envío de stickers.
- Se agrega una nueva herramienta para monitorear el estado del bridge no oficial.
- El agente ahora podrá elegir por cual número quiere contactar a un cliente.
- Se crea nueva página que almacenará todas las características de `iKono Chat` y sus nuevos cambios.
