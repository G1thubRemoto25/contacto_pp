App de Contactos (PHP + MySQL + MVC y poo)

Aplicación web sencilla para gestionar contactos, hecha en PHP con MVC, PDO y MySQL.
Permite:

Registro e inicio de sesión de usuarios.

CRUD de contactos (crear, listar, editar, eliminar).


/contactos-app<br>
├── /app<br>
│   ├── /Controllers<br>
│   ├── /Models<br>
│   ├── /Views<br>
│   └── Database.php<br>
├── /public<br>
│   └── index.php<br>
├── composer.json<br>
└── contactos.sql<br>
Instalación

Clonar o descargar este repositorio.

Importar contactos.sql en MySQL.

Configurar la conexión en app/Database.php.

Instalar dependencias de Composer:

composer dump-autoload


Iniciar el servidor PHP:

php -S localhost:8000 -t public
