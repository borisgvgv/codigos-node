# codigos-node

Para instalar una versión específica de Node.js en tu sistema, puedes utilizar un administrador de versiones de Node.js como nvm (Node Version Manager) en sistemas Unix-like (Linux y macOS) o nvm-windows en Windows. Aquí te mostraré cómo hacerlo usando nvm en sistemas Unix-like:

Paso 1: Instalar nvm (Node Version Manager)

Si aún no tienes nvm instalado, puedes hacerlo siguiendo estos pasos:

    Abre tu terminal.

    Instala nvm utilizando cURL ejecutando el siguiente comando:

bash

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

    Cierra y vuelve a abrir tu terminal o ejecuta el siguiente comando para cargar nvm:

bash

source ~/.bashrc

Paso 2: Instalar una versión específica de Node.js

Una vez que tengas nvm instalado, puedes usarlo para instalar la versión de Node.js que desees. Por ejemplo, si deseas instalar Node.js versión 14.17.6, puedes hacerlo de la siguiente manera:

bash

nvm install 16.20.2

Este comando descargará e instalará Node.js 14.17.6 en tu sistema.

Paso 3: Usar la versión específica de Node.js

Para usar la versión específica de Node.js que has instalado, simplemente ejecuta el siguiente comando:

bash

nvm use 16.20.2

Ahora estarás utilizando la versión 14.17.6 de Node.js en tu terminal. Puedes verificar la versión actual de Node.js y npm ejecutando los siguientes comandos:

bash

node -v
npm -v

Esto te mostrará la versión de Node.js y npm que estás utilizando actualmente.

Si en algún momento deseas cambiar a otra versión de Node.js que hayas instalado previamente, puedes usar el comando nvm use con la versión deseada.

Recuerda que estos pasos son específicos para sistemas Unix-like (Linux y macOS). En Windows, puedes utilizar nvm-windows o descargar la versión de Node.js directamente desde el sitio web oficial de Node.js.
