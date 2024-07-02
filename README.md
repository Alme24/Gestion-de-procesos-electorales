
# Sistema de Administrador de Procesos Electorales en la Universidad Mayor de San Simón 

El sistema desarrollado en Laravel tiene como objetivo principal asistir en las fases administrativas del proceso de elecciones dentro de la Universidad Mayor de San Simón (UMSS). Este sistema ofrece un sitio web para gestionar eficientemente todas las etapas del proceso electoral, garantizando transparencia, accesibilidad y eficiencia. 


## 📝 Características

El sistema desarrollado en Laravel para la gestión de elecciones en la UMSS ofrece funcionalidades completas y eficientes para asegurar un proceso electoral transparente y organizado. A continuación, se describen las principales características:

#### Funcionalidades Principales

1. **Inicio**
    * Página de inicio con acceso rápido a todas las funcionalidades.

2. **Elecciones**
    * Listado de elecciones activas con detalles.
    * Botones para crear nuevas elecciones, añadir votantes y comités electorales.
    * Barra de búsqueda y acciones para cada elección.

3. **Formularios de Registro**
    * **Elecciones:** Nombre, motivo, cargo, gestión, tipo de votante, convocatoria (PDF), tipo de elección y descripción.
    * **Votantes:** Elección, nombre, apellidos, código SIS, CI, tipo de votante, carrera, facultad, celular y email.
    * **Comités Electorales:** Elección, nombres, apellidos, fecha de nacimiento, carrera, cargo y tipo de comité.
    * **Frentes:** Nombre del frente, elección asociada, cargo, logo y candidatos.
    * **Mesas:** Número de mesas y elección asociada.
    * **Jurados:** Nombre, apellidos y tipo de jurado.
    * **Comunicados:** Nombre, apellidos y tipo de comunicado.

4. **Boletas y Resultados**
    * Crear boletas con detalles como nombre de la elección, título, fecha, logo y casillas.
    * Registrar resultados de elecciones con nombres de frentes y votos obtenidos.

5. **Actas y Reportes**
    * Crear actas de apertura y cierre.
    * Generar reportes de elecciones activas y descargar backups de la base de datos.

6. **Acceso y Seguridad**
    *  Distinción entre accesos de usuario y administrador.
    *  Registro de acciones en una bitácora.

7. **Historial de Elecciones**

    *  Lista de elecciones pasadas con nombre, fecha, cargo y resultados.

## 📋 Requisitos

![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Xampp](https://img.shields.io/badge/Xampp-FF7139?style=for-the-badge&logo=xampp&logoColor=white)
![Composer](https://img.shields.io/badge/Composer-FFFFFF?style=for-the-badge&logo=composer&logoColor=black)
![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)

## 🔧 Instalación

### Clonar el repositorio

```bash
git clone https://github.com/tu_usuario/tu_repositorio.git
cd tu_repositorio
```
### Intalar dependencias de PHP

```bash
composer install
```
> [!IMPORTANT]  
> Asegúrate de ejecutar `composer install` desde la raíz del proyecto. Si la carpeta `vendor` no se crea, verifica que no haya errores en la instalación de Composer o en el archivo `composer.json`.

### Configuración de variables de entorno

Renombra el archivo .env.example a .env y configura tus variables de entorno, especialmente la conexión a la base de datos:

```bash
cp .env.example .env
```

Editar el archivo ´.env´ y agrega la configuración de tu base de datos:

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nombre_de_tu_base_de_datos
DB_USERNAME=tu_usuario
DB_PASSWORD=tu_contraseña
```

### Generar clave de aplicación

```bash
php artisan key:generate
```

### Migrar la base de datos

```bash
php artisan migrate
```

### Instalar dependencias de Node.js y compilar assets

```bash
npm install
npm run dev
```

## ⚙ Uso

Para iniciar el servidor de desarrollo, ejecuta:

```bash
php artisan serve
```

La aplicación estará disponible en `http://localhost:8000`.

## 🛠 Herramientas
![Javascript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![html](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Css](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)

## 🖋 Autores

**GRUPO-EMPRESA:** DevGenius 
* **Mauricio Ramos Crespo** 
* **Jael Alejandra Avendaño Fernandez** - [Alme24](https://github.com/Alme24)
* **Sergio Andres Veizaga Sanchez**
* **Aylin Nicol Garcia Mancilla**
* **Pablo Enrique Delgadillo Fernandez**
* **Elias Renterias Arce**
