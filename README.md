# Proyecto de Web Cloud

## Descripción

Este es un proyecto autónomo que se centra en la creación de una herramienta de almacenamiento en la nube accesible tanto a través de la web como de Telegram. El objetivo principal del proyecto es facilitar la subida y descarga de archivos, ofreciendo una solución práctica y fácil de usar para la gestión de datos.

## Tecnologías

El proyecto utiliza una variedad de tecnologías modernas, que incluyen:

- **Front-end:** React
- **Back-end:** Node.js, Express
- **Gestión de mensajes:** Kafka
- **Contenedores:** Docker

Además, se ha realizado una integración con la API de Telegram para permitir la subida de archivos directamente a través de la plataforma de Telegram.

## Funcionalidades

1. **Subir archivos:** Los usuarios pueden subir archivos a través de la interfaz web o directamente desde Telegram.
2. **Descargar archivos:** Los archivos se pueden descargar fácilmente a través de la interfaz web.
3. **Integración de Telegram:** Los usuarios pueden interactuar con el servicio a través de Telegram, proporcionando una capa adicional de accesibilidad y conveniencia.

## Futuro del proyecto

Actualmente, estoy trabajando en la integración con Google Drive para expandir aún más las capacidades de almacenamiento y compartir archivos de la herramienta.

## Instalación

Para clonar y ejecutar este proyecto, necesitarás [Git](https://git-scm.com) y [Node.js](https://nodejs.org/en/download/) (que viene con [npm](http://npmjs.com)) instalados en tu ordenador. 

El proyecto se encuentra dividido en microservicios y se podrá desplegar facilmente.

[Git](https://github.com/MiguelSOAT/cloud-front)
[Core](https://github.com/MiguelSOAT/cloud-core)
[Telegram integration](https://github.com/MiguelSOAT/telegram-bot)
[Docker](https://github.com/MiguelSOAT/docker)

Para ello tendremos que ejecutar el siguiente comando en todos los servicios.
```bash
$ npm install
```

Posteriormente podremos levantar los microservicios con docker mediante:

```bash
# Despliegue docker
$ docker-compose up -d --build

