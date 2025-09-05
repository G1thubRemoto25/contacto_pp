App de Contactos (PHP + MySQL + MVC)

Aplicación web sencilla para gestionar contactos, hecha en PHP con MVC, PDO y MySQL.
Permite:

Registro e inicio de sesión de usuarios.

CRUD de contactos (crear, listar, editar, eliminar).


/contactos-app
├── /app
│   ├── /Controllers
│   ├── /Models
│   ├── /Views
│   └── Database.php
├── /public
│   └── index.php
├── composer.json
└── contactos.sql
Instalación

Clonar o descargar este repositorio.

Importar contactos.sql en MySQL.

Configurar la conexión en app/Database.php.

Instalar dependencias de Composer:

composer dump-autoload


Iniciar el servidor PHP:

php -S localhost:8000 -t public
