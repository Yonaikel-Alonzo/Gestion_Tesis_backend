EJECUTAR EL PROYECTO DE LARAVEL

1. Instalar dependencias

composer install

2. Configurar el archivo .env

	* Copiar el archivo de configuración de ejemplo:

		cp .env.example .env

	* Editar el archivo .env para configurar las variables de entorno, como la conexión a la base de datos.

		DB_CONNECTION=pgsql
		DB_HOST=localhost
		DB_PORT=5432
		DB_DATABASE=nombre_base_datos
		DB_USERNAME=usuario
		DB_PASSWORD=contraseña

3. Generar la clave de la aplicación

php artisan key:generate

4. Migrar la base de datos

php artisan migrate

5. Iniciar el servidor local

php artisan serve

El proyecto estará disponible en http://127.0.0.1:8000.

------------------------------------------------------------