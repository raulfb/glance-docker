# Glance

Mi mplementación dockerizada de Glance, una herramienta que proporciona una interfaz de usuario configurable para mostrar información de diversas fuentes. Puedes encontrar el proyecto original en [Glance](https://github.com/glanceapp/glance).

## Estructura del Proyecto

- `docker-compose.yml`: Archivo de configuración para Docker Compose.
- `glance.yml`: Archivo de configuración de la aplicación Glance.

## Uso

### Requisitos

- Docker
- Docker Compose

### Instrucciones

1. Clona este repositorio.
2. Navega al directorio `glance`.
3. Ejecuta el siguiente comando para iniciar los servicios:

   ```sh
   docker-compose up -d
   ````

4. La aplicación estará disponible en http://localhost:8080.

## Configuración
El archivo glance.yml permite configurar la apariencia y el contenido de la aplicación.