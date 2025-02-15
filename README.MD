# GERMAN ALVARADO GEIDE MICHELL

# Actividad Gestión de Libros

Este proyecto es un sistema web en PHP para la gestión de libros y autores.

## Funcionalidades:
- Registro de libros con título, autor, precio y cantidad.
- Edición y eliminación de libros.
- Listado de libros con opciones de gestión.
- Menú de navegación en todas las páginas.

## Instalación

1. **Clone este repositorio** en su máquina local.
Copie la carpeta del proyecto ACTIVIDAD-LIBROS-AUTORES, en la carpeta htdocs de XAMPP (usualmente está en `C:\xampp\htdocs`).
2. **Inicie XAMPP**:
   - Asegúrese de que Apache y MySQL están corriendo en el panel de control de XAMPP.
3. **Importe la base de datos**:
   - Acceda a `http://localhost/phpmyadmin/`.
   - Cree una nueva base de datos llamada `biblioteca`.
   - Importe el archivo SQL, este se encuentra en la carpeta `sql` y lleva como nombre `biblioteca.sql`
4. **Configure la conexión** en `includes/database.php` con los datos de su servidor de base de datos.
**En ESTE caso, usuario: root y la contraseña queda vacía. Esto se encuentra explicado en el database.php**
5. **Acceda al proyecto**:
   - Abra `http://localhost/biblioteca/index.php` en su navegador.

## Estructura del Proyecto
- `index.php`: Página de inicio.
- `registro.php`: Formulario para registrar libros.
- `listado.php`: Muestra todos los libros registrados.
- `editar.php`: Permite editar los datos de los libros registrados.
- `eliminar.php`: Elimina los libros registrados.
- `contacto.php`: Contacto con la biblioteca.
- `css/styles.css`: Estil general.
- `includes/database.php`: Establece una conexión a una base de datos MySQL llamada "biblioteca" y gestiona errores en caso de que la conexión falle. Es una parte fundamental para cualquier aplicación web que necesite interactuar con una base de datos.
- `includes/header.php`:  Establece una sesión y crea un menú de navegación con enlaces a diferentes secciones de un sitio web relacionado con libros.
