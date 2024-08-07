# Angular Ionic Project with JSON Server

Este proyecto utiliza Angular e Ionic para la creación de una aplicación móvil y JSON Server para la simulación de una API REST.

## Requisitos Previos

- Node.js (https://nodejs.org/)
- Ionic CLI (Instalar con `npm install -g @ionic/cli`)
- JSON Server (Instalar con `npm install -g json-server`)

## Instalación

### Paso 1: Clonar el repositorio

Clona este repositorio en tu máquina local utilizando Git.

```
git clone https://github.com/JimRoMa123/AngularIonicProyect.git
cd repo

Paso 2: Instalar dependencias
Ejecuta el siguiente comando en la carpeta raíz del proyecto para instalar las dependencias de Node.js necesarias.


Copiar código
npm install

Paso 3: Configurar JSON Server
Navega a la carpeta database y ejecuta el siguiente comando para instalar JSON Server globalmente.


Copiar código
cd database
npm install -g json-server
Paso 4: Iniciar JSON Server
Ejecuta el script startDB.bat para iniciar JSON Server. Este script debe estar configurado para iniciar el servidor JSON con tu archivo de configuración de base de datos.


Copiar código
start startDB.bat
Paso 5: Iniciar la aplicación Ionic
Abre una nueva terminal, navega a la carpeta raíz del proyecto y ejecuta el siguiente comando para iniciar el servidor de desarrollo de Ionic.


Copiar código
ionic serve
Estructura del Proyecto
src/: Contiene los archivos fuente del proyecto Angular/Ionic.
database/: Contiene los archivos de configuración y datos para JSON Server.
startDB.bat: Script para iniciar JSON Server.
Uso
Una vez que ambos servidores estén corriendo (JSON Server y el servidor de desarrollo de Ionic), puedes acceder a la aplicación en tu navegador en la siguiente URL:

arduino
Copiar código
http://localhost:8100
La API de JSON Server estará disponible en:

arduino
Copiar código
http://localhost:3000