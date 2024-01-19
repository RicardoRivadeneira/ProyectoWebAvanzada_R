# Proyecto Web con Arquitectura de 3 Capas

## Objetivo
Aplicar los principios de diseño de 3 capas en un proyecto web específico.

## Instrucciones

### Estructura de Carpetas
La estructura de carpetas refleja la separación de capas de la siguiente manera:

- **frontreact:** Carpeta del front-end que contiene el componente desarrollado para interactuar con el back-end.
- **node:** Carpeta del back-end (Nota: originalmente llamada 'node' debido a cambios en la estructura del proyecto).
- **database:** Carpeta que representa la base de datos, donde se gestionan y almacenan los datos.

### Desarrollo Front-end
Se ha desarrollado un componente front-end que se comunica con un controlador en la capa back-end. Este componente permite ingresar títulos y contenido, y realizar acciones como editar o borrar.

### Implementación Back-end
En la capa back-end, se ha implementado un servicio que interactúa con la base de datos. Este servicio gestiona las operaciones relacionadas con la manipulación de datos, como la inserción, actualización y eliminación.

## Ejecución del Proyecto

Para ejecutar el proyecto, sigue estos pasos:

1. **Front-end (frontreact):**
    - Abre una terminal y navega a la carpeta del front-end: `cd frontreact`
    - Instala las dependencias: `npm install`
    - Inicia el servidor de desarrollo: `npm start`

2. **Back-end (node):**
    - Abre otra terminal y navega a la carpeta del back-end: `cd node`
    - Instala las dependencias: `npm install`
    - Instala nodemon (si no está instalado): `npm install -g nodemon`
    - Inicia el servidor con nodemon: `nodemon app.js`

Una vez que ambos servidores estén en ejecución, podrás interactuar con la aplicación accediendo a la página desde tu navegador.

**Nota:** Asegúrate de tener Node.js y npm instalados en tu sistema antes de ejecutar el proyecto.

Este proyecto, aunque sencillo, es parte del desarrollo continuo que se está llevando a cabo, en línea con el proyecto del 2do parcial que aún está en desarrollo. El programa permite realizar acciones básicas como ingresar títulos y contenido, y se espera que evolucione como parte de futuras iteraciones del proyecto.

## Evidencia
![Evidencia](./Evidencia/Ejecucion.png)
