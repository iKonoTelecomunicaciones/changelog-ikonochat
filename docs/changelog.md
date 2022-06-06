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
- El `Widget iKono Chat` ahora permite chats con agentes o sin agentes y la sesión de un cliente se preserva por x cantidad de tiempo configurable.
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
