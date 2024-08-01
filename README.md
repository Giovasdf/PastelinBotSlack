
# Este script crea un archivo README.md con la documentación para el bot de Slack.

# Code Messenger Slack Bot

Este bot para Slack está diseñado para enviar mensajes de códigos de programación desde Visual Studio Code a un canal de Slack. La integración con la extensión de VSCode [PasteLint to Slack](https://marketplace.visualstudio.com/items?itemName=GiovanniMolina.pastelintoslack) permite enviar fragmentos de código directamente desde el editor a Slack de manera sencilla.

## Características

- Envía fragmentos de código desde VSCode a Slack.
- Soporta múltiples lenguajes de programación con resaltado de sintaxis.
- Fácil integración con tu espacio de trabajo de Slack.

## Instalación

### Paso 1: Configura el Bot en Slack

1. **Instala la Aplicación**
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

