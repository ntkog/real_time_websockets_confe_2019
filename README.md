# Prerequisitos

- [NodeJS](https://nodejs.org/en/download/)
- [http-server](https://www.npmjs.com/package/http-server)


# Instrucciones para los ejemplos

## Instalar dependencias del servidor de websockets

```bash
cd ejemplos/ws_server
npm i
```

## Arrancar el Servidor de websockets

```bash
node simple.js
```
> Dependiendo del ejemplo, sustituiremos **simple.js** por el fichero indicado en cada ejemplo.

## Arrancar el servidor HTTP

Abre otro terminal y ejecuta

```bash
cd ejemplos
http-server .
```

> Este paso solo lo tienes que hacer una vez . Se levantará un servidor HTTP estático en la direccion [http://localhost:8080](http://localhost:8080)


# Ejemplos

## Ejemplo simple de websockets sin mapas

- Servidor de websockets

```bash
node simple.js
```

- Dirección

[http://localhost:8080/simple.html](http://localhost:8080/simple.html)

## Ejemplo con mapas

- Servidor de websockets

```bash
node red_buses_serial.js
```

- Dirección

[http://localhost:8080/red_buses_mod.html](http://localhost:8080/red_buses_mod.html)


## Ejemplo del widget de Tracking

- Servidor de websockets

```bash
node track.js
```

- Dirección

[http://localhost:8080/widgets-track.html](http://localhost:8080/widgets-track.html)
