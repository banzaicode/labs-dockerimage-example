# Generando imagenes Docker y publicandolas con GitHub Actions

Me impulso a escribir este ejemplo el mostrar lo simple que podemos implementar integración continua utilizando una de tantas herramientas que tenemos disponibles en el mercado, esta vez me volqué a usar las posibilidades que nos da GitHub con sus Actions.

Para este ejemplo vamos a crear un dockerfile muy simple que con una imagen minima de linux alpine vamos a provocar una salida `Hello Docker image with GitHub Actions!` desde el mismo entrypoint de la definición.

Los siguientes pasos seran explicados en los mismos Pull Requests que vamos a ir generando con las funcionalidades que agregaremos a nuestro ejemplo didactico.