Para correr el docker-compose up

tener la estructura siguiente (lo necesario se encuantra en /doc)

- el archivo docker-compose
- el Dockerfile
- el directorio DemoCompose con el jar adentro que se llama demo-compose-1.0.0.jar

Luego hacer
    > docker-compose up
    > la aplicacion se levanta en el puerto 9191

Para probar que se inicia la aplicacion
    > {{ dominio donde se encuentra ejecutando el compose }}:9191/provincias
    > Nos devolverá
        [
            {
                "id": 1,
                "nombre": "Mendozaaaaaaaaaaaa"
            }
        ]