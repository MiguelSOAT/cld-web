## Web Cloud Project

## Description.

This is a standalone project that focuses on creating a cloud storage tool accessible through both the web and Telegram. The main goal of the project is to facilitate the uploading and downloading of files, offering a practical and easy to use solution for data management.

## Technologies

The project uses a variety of modern technologies, which include:

- **Front-end:** React
- **Back-end:** Node.js, Express
- **Message handling:** Kafka
- **Containers:** Docker

In addition, an integration with the Telegram API has been done to allow file uploads directly through the Telegram platform.

## Functionalities.

1. **File upload:** Users can upload files through the web interface or directly from Telegram.
2. **Download files:** Files can be easily downloaded through the web interface.
3. **Telegram integration:** Users can interact with the service through Telegram, providing an additional layer of accessibility and convenience.

## Future of the project.

Currently, I am working on integration with Google Drive to further expand the storage and file sharing capabilities of the tool.

## Installation

To clone and run this project, you will need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. 

The project is divided into microservices and can be easily deployed.

- [Git](https://github.com/MiguelSOAT/cloud-front)
- [Core](https://github.com/MiguelSOAT/cloud-core)
- [Telegram integration](https://github.com/MiguelSOAT/telegram-bot)
- [Docker](https://github.com/MiguelSOAT/docker)

To do this we will need to run the following command on all services.
```bash
  $ npm install
```

Subsequently we will be able to raise the microservices with docker by means of:

```bash
# docker deployment
$ docker-compose up -d --build
```
