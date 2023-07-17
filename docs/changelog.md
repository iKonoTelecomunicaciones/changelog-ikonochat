  ---

### **[ 2023 - 07 - 17 ]**
- Se agrega opción para que luego de un máximo de intentos al ingresar un dato en un chat, se pueda ejecutar alguna opción deseada como por ejemplo repartir el chat.
- Se agrega opción para que al transferir un chat a una sala sin agentes disponibles, el chat quede encolado y se atienda cuando se encuentre un agente disponible.
- Gestión de optin del los clientes en diferentes niveles: general para todas las cuentas, específico por canal, y específico por canal y cuenta.
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
