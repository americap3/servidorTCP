# Mi primer servidor TCP

El protocolo TCP es el responsable de dividir la información en pequeñas unidades llamadas paquetes antes de que puedan ser enviados por medio de la red y una vez al haber llegado a su destino volverlos a ensamblar. Adicionalmente le coloca a cada paquete una dirección de destino y lo pasa a la siguiente capa del protocolo TCP/IP.

### Pre-requisitos 📋

- node.js

## Probando la práctica

1. Abrimos la carpeta "tcp" en una terminal y ejecutamos el archivo "server.js" con el siguiente comando:

```
node server.js
```

Observaremos que el archivo se esta ejecutando

2. En otra terminal, abrimos de nuevo nuestra carpeta "server" y ahora ejecutaremos el archivo "client.js" con el comando:

```
node client.js
```

### Analizando

Si la conexión se realizó de manera correcta:

- En la primer terminal nos aparecerá:

```
----------- conexión -----------------

```

- Y en la segunda terminal nos imprimirá esto:

```
---------- Conexión TCP exitosa -----------
INFO= He recibido una conexión

```

## Construido con

* Node.js - Lenguaje utilizado
* Visual Studio Code - Editor de texto
* Terminal del sistema - Pruebas de la práctica

## Autores

* **América G. Martínez Cano** - *348810* - [https://github.com/americap3]

## Basado en:

Clase del 20/04/2023 de Desarrollo Basado en Plataformas

**Docente: Ing. Luis Antonio Ramírez Martínez** 

## Información

6CC2 | Facultad de Ingeniería

Universidad Autónoma de Chihuahua
