# 📚 GA7-220501096-AA5-EV01: Diseño y desarrollo de servicios web - Caso

## 📝 Descripción

Este proyecto corresponde a la evidencia solicitada en el componente formativo **"Construcción de API"**. El objetivo es diseñar y codificar un servicio web que permita el registro de usuarios y el inicio de sesión, cumpliendo con los siguientes requisitos:

- El servicio recibe un usuario y una contraseña.
- Si la autenticación es correcta, retorna un mensaje de autenticación satisfactoria.
- Si la autenticación es incorrecta, retorna un mensaje de error.
- El código contiene comentarios explicativos.
- El proyecto utiliza herramientas de versionamiento (Git).

## 🗂️ Estructura del Proyecto

El proyecto está desarrollado en Laravel e incluye:

- **Registro de usuario:** Permite crear nuevos usuarios.
- **Inicio de sesión:** Permite autenticar usuarios existentes.
- **Mensajes claros:** Respuestas diferenciadas para autenticación exitosa o fallida.
- **Comentarios:** El código fuente contiene comentarios para facilitar su comprensión.

## 🛠️ Tecnologías Utilizadas

- **PHP 8.x**
- **Laravel 10.x**
- **Jetstream** (con Livewire)
- **MySQL** (u otro motor compatible)
- **Node.js** y **NPM**
- **Tailwind CSS**
- **Laragon** (entorno de desarrollo local)

## ⚙️ Requisitos Previos

Antes de iniciar, asegúrate de tener instalado en tu equipo:

- [Laragon](https://laragon.org/download/) (recomendado para Windows, incluye Apache, MySQL, PHP y más)
- Composer
- Node.js y NPM
- Un navegador web moderno

<br>

## 🚀 Creación del Proyecto desde Cero

Si quieres crear este proyecto desde el inicio, sigue estos pasos:

### 1. **Crear el proyecto con Laragon desde la terminal**
```bash
composer create-project laravel/laravel tienda-sena
cd tienda-sena
```

### 2. **Instalar paquete Jetstream**
```bash
composer require laravel/jetstream

```

### 3. **Instalar Jetstream con Livewire**
```bash
php artisan jetstream:install livewire
```

### 4. **Instalar dependencias y construir las dependencias NPM**
```bash
npm install
npm run dev
```

### 5. **Ejecutar la migración de la base de Datos**
```bash
php artisan migrate
```

<br>

## 🔧 Instalación (Proyecto Existente) y Ejecución

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/jcardonamde/php-kasumi-web-service.git
   cd tienda-sena
   ```

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
<br>

## Pruebas del Servicio

- **Registro:** Accede a `/register` para crear un nuevo usuario. Ejemplo en el navegador usar: http://localhost/tienda-sena/public/register
- **Inicio de sesión:** Accede a `/login` para autenticarte. Ejemplo en el navegador usa: http://localhost/tienda-sena/public/login
- **Recuperar contraseña:** Accede a `/forgot-password` para recuperar el acceso al sistema mediante un enlace de restablecimiento de contraseña. Ejemplo en el navegador usa: http://localhost/tienda-sena/public/forgot-password
- El sistema mostrará mensajes claros según el resultado de la autenticación.

## 👨‍💻 Autor

**Desarrollado por:**

👥 Daniel Alejandro Vargas Uzuriaga <br>
👥 Daniela López Chica <br>
👥 Jonathan Cardona Calderon <br>
👥 Luz Eleidis Baldovino González

:computer: Programa Tecnólogo en Análisis y Desarrollo de Software
Ficha Técnica 2977435

![Logo SENA](https://docs.google.com/drawings/d/e/2PACX-1vRHtXZUAI_yYltgXtZnIChIn1CDQyMCtZJLQ8R-5TiVO_IjaDVPsQnYlPEotP63Jz_I06loshw4yA1X/pub?w=50&h=50)

---
