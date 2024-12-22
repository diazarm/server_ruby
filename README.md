
# Crear el proyecto Rails con PostgreSQL como base de datos


## Primero: creacion del proyecto


 rails new proyecto --database=postgresql


## Configurar la contraseña en database.yml:


Editar la sección development para incluir username, password y host.
## Crear las bases de datos:

 rails db:create


## Generar un CRUD automáticamente (modelo, controlador y vistas):

 rails generate scaffold Post title:string body:text


## Aplicar las migraciones para crear las tablas en la base de datos:

 rails db:migrate


## Iniciar el servidor para probar el CRUD:

 rails server


## Ahora puedes acceder al CRUD en http://localhost:3000/posts.

## Autor

- [Marcelo Diaz](https://www.github.com/diazarm)

