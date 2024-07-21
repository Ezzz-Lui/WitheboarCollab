# Pizarra Colaborativa en Tiempo Real

## Descripción

Este proyecto es una pizarra colaborativa en tiempo real que permite a múltiples usuarios dibujar simultáneamente sin necesidad de logins o inicios de sesión. La aplicación está diseñada para ser rápida y eficiente, proporcionando una experiencia de usuario fluida y sin complicaciones.

## Tecnologías Utilizadas

### Frontend

- **ReactJS**: Utilizado para construir una interfaz de usuario dinámica y reactiva.
- **Canvas API**: Utilizado para renderizar y manipular gráficos y dibujos en la pizarra.
- **Socket.io**: Utilizado para la comunicación en tiempo real entre el frontend y el backend.

### Backend

- **Node.js**: Entorno de ejecución para el servidor backend.
- **Express.js**: Framework utilizado para manejar rutas y middleware.
- **Socket.io**: Utilizado para la comunicación en tiempo real entre el servidor y los clientes.

### Base de Datos

- **MongoDB**: Utilizado para almacenar y recuperar datos de pizarras y elementos colaborativos.

## Características

### Principales

1. **Pizarra en Tiempo Real**: Permite que varios usuarios vean y dibujen simultáneamente en la misma pizarra.
2. **Dibujado Colaborativo**: Soporta herramientas de dibujo básicas como lápiz, formas geométricas, colores, etc.
3. **Interfaz Intuitiva**: Interfaz de usuario limpia y fácil de usar para la creación y manipulación de elementos en la pizarra.
4. **Persistencia Opcional**: Opción para guardar el estado actual de la pizarra localmente en el navegador del usuario.

### Secundarias

1. **Historial de Cambios**: Mantiene un historial de cambios para permitir deshacer y rehacer acciones.
2. **Chat Integrado**: Soporta un chat integrado para comunicación entre los usuarios.
3. **Exportación de Dibujos**: Capacidad para exportar la pizarra como imagen o archivo.

## Instalación y Configuración

### Requisitos

- Node.js
- npm (Node Package Manager)
- MongoDB

### Pasos para la Instalación

1. Clona este repositorio:

    ```bash
    git clone https://github.com/tu-usuario/pizarra-colaborativa.git
    cd pizarra-colaborativa
    ```

2. Instala las dependencias del backend:

    ```bash
    cd backend
    npm install
    ```

3. Instala las dependencias del frontend:

    ```bash
    cd ../frontend
    npm install
    ```

4. Configura las variables de entorno:

    Crea un archivo `.env` en el directorio `backend` con el siguiente contenido:

    ```env
    PORT=4000
    MONGO_URI=tu_conexion_mongodb
    ```

5. Inicia el servidor backend:

    ```bash
    cd backend
    npm start
    ```

6. Inicia la aplicación frontend:

    ```bash
    cd ../frontend
    npm start
    ```

7. Abre tu navegador y navega a `http://localhost:3000` para ver la aplicación en funcionamiento.

## Contribución

Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una rama con tu nueva característica (`git checkout -b feature/nueva-caracteristica`).
3. Realiza tus cambios y haz commit de los mismos (`git commit -m 'Añadir nueva característica'`).
4. Haz push a la rama (`git push origin feature/nueva-caracteristica`).
5. Abre un Pull Request.

## Licencia

Este proyecto está bajo la Licencia MIT. Puedes ver más detalles en el archivo [LICENSE](LICENSE).

## Preview de la Aplicación

