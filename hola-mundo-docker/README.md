# Proyecto Hola Mundo en Docker

Este proyecto es una simple aplicación de Python que imprime "Hola, Mundo!" y "Hola, Mundo2!" en la consola. La aplicación está contenida en un contenedor Docker, lo que facilita su ejecución en cualquier entorno que soporte Docker.

## Estructura del Proyecto

```
hola-mundo-docker
├── app
│   └── hola_mundo.py
├── Dockerfile
├── .dockerignore
├── .gitignore
└── README.md
```

## Archivos del Proyecto

- **app/hola_mundo.py**: Contiene el código de la aplicación.
- **Dockerfile**: Define la imagen de Docker para la aplicación.
- **.dockerignore**: Especifica los archivos que deben ser ignorados por Docker.
- **.gitignore**: Especifica los archivos que deben ser ignorados por Git.

## Instrucciones para Construir y Ejecutar

1. **Clonar el Repositorio**:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd hola-mundo-docker
   ```

2. **Construir la Imagen de Docker**:
   ```bash
   docker build -t hola-mundo .
   ```

3. **Ejecutar el Contenedor**:
   ```bash
   docker run hola-mundo
   ```

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, por favor abre un issue o envía un pull request.