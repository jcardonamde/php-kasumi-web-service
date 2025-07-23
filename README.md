# GA7-220501096-AA5-EV01: Diseño y desarrollo de servicios web - Caso

## Descripción

Este proyecto corresponde a la evidencia solicitada en el componente formativo **"Construcción de API"**. El objetivo es diseñar y codificar un servicio web que permita el registro de usuarios y el inicio de sesión, cumpliendo con los siguientes requisitos:

- El servicio recibe un usuario y una contraseña.
- Si la autenticación es correcta, retorna un mensaje de autenticación satisfactoria.
- Si la autenticación es incorrecta, retorna un mensaje de error.
- El código contiene comentarios explicativos.
- El proyecto utiliza herramientas de versionamiento (Git).

## Estructura del Proyecto

El proyecto está desarrollado en Laravel e incluye:

- **Registro de usuario:** Permite crear nuevos usuarios.
- **Inicio de sesión:** Permite autenticar usuarios existentes.
- **Mensajes claros:** Respuestas diferenciadas para autenticación exitosa o fallida.
- **Comentarios:** El código fuente contiene comentarios para facilitar su comprensión.

## Instalación y Ejecución

1. Clona el repositorio o descarga el archivo ZIP/RAR.
2. Instala las dependencias de PHP y JavaScript:
   ```bash
   composer install
   npm install
   ```
3. Configura el archivo `.env` con los datos de tu base de datos.
4. Ejecuta las migraciones:
   ```bash
   php artisan migrate
   ```
5. Inicia el servidor de desarrollo:
   ```bash
   npm run dev
   ```

## Pruebas del Servicio

- **Registro:** Accede a `/register` para crear un nuevo usuario.
- **Inicio de sesión:** Accede a `/login` para autenticarte.
- El sistema mostrará mensajes claros según el resultado de la autenticación.

## Versionamiento

Este proyecto utiliza Git para el control de versiones. Se recomienda revisar el historial de commits para ver la evolución del desarrollo.

## Entrega

- Puedes entregar este proyecto como archivo ZIP, RAR o mediante un enlace al repositorio.
