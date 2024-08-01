
# Este script crea un archivo README.md con la documentación para el bot de Slack.

# Code Messenger Slack Bot

Este bot para Slack está diseñado para enviar mensajes de códigos de programación desde Visual Studio Code a un canal de Slack. La integración con la extensión de VSCode [PasteLint to Slack](https://marketplace.visualstudio.com/items?itemName=GiovanniMolina.pastelintoslack) permite enviar fragmentos de código directamente desde el editor a Slack de manera sencilla.

## Características

- Envía fragmentos de código desde VSCode a Slack.
- Soporta múltiples lenguajes de programación con resaltado de sintaxis.
- Fácil integración con tu espacio de trabajo de Slack.

## Instalación

### Paso 1: Configura el Bot en Slack

1. **Crea una Aplicación en Slack**
   - Ve a [Slack API](https://api.slack.com/apps) y haz clic en "Create New App".
   - Elige "From scratch" y proporciona un nombre para tu app y selecciona el espacio de trabajo de Slack.

2. **Configura los Permisos**
   - Ve a "OAuth & Permissions" en la configuración de la aplicación.
   - Añade los permisos necesarios para que el bot pueda enviar mensajes. Usualmente, necesitarás permisos como \`chat:write\`.

3. **Añade la URL de Redirección**
   - En la sección "OAuth & Permissions", añade la URL de redirección que se usará después de la instalación del bot. Esta URL debe apuntar a una página web donde los usuarios sean redirigidos después de autorizar la aplicación.

4. **Instala la Aplicación**
   - Usa el botón de "Install App" para instalar la aplicación en tu espacio de trabajo de Slack.

### Paso 2: Configura la Extensión en VSCode

1. **Instala la Extensión**
   - Abre Visual Studio Code.
   - Ve a la pestaña de Extensiones (Ctrl+Shift+X) y busca "PasteLint to Slack".
   - Instala la extensión [PasteLint to Slack](https://marketplace.visualstudio.com/items?itemName=GiovanniMolina.pastelintoslack).

2. **Configura la Extensión**
   - Ve a la configuración de la extensión en VSCode y añade el Token de OAuth proporcionado por Slack.
   - Configura el canal de Slack donde quieres que se envíen los mensajes de código.

## Uso

1. **Envía Fragmentos de Código**
   - Copia el fragmento de código en VSCode.
   - Usa el comando de la extensión (\`PasteLint to Slack\`) para enviar el código al canal de Slack configurado.

2. **Recibe Confirmación en Slack**
   - Después de enviar el código, recibirás una notificación en el canal de Slack con el fragmento de código y su resaltado de sintaxis.



## Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).

