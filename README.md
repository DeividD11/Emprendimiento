# Tienda Online

Este es un proyecto de tienda online desarrollado utilizando la arquitectura MVC (Modelo-Vista-Controlador) con PHP, HTML, CSS y JavaScript.

## Estructura del Proyecto

El proyecto está organizado en las siguientes carpetas:

- **src**: Contiene el código fuente de la aplicación.
  - **controllers**: Controladores que manejan la lógica de la aplicación.
    - `CarritoController.php`: Maneja las operaciones del carrito de compras.
    - `ProductoController.php`: Gestiona las operaciones relacionadas con los productos.
    - `UsuarioController.php`: Maneja las operaciones de usuario.
  - **models**: Modelos que representan los datos de la aplicación.
    - `Carrito.php`: Modelo del carrito de compras.
    - `Producto.php`: Modelo de un producto.
    - `Usuario.php`: Modelo de un usuario.
  - **views**: Vistas que presentan la interfaz de usuario.
    - **carrito**: Vistas relacionadas con el carrito de compras.
      - `index.php`: Muestra el contenido del carrito.
    - **producto**: Vistas relacionadas con los productos.
      - `detalle.php`: Muestra los detalles de un producto.
      - `lista.php`: Muestra una lista de productos.
    - **usuario**: Vistas relacionadas con la gestión de usuarios.
      - `login.php`: Permite a los usuarios iniciar sesión.
      - `registro.php`: Permite a nuevos usuarios registrarse.
  - **public**: Archivos públicos accesibles desde el navegador.
    - **css**: Archivos de estilo CSS.
      - `style.css`: Estilos para la aplicación.
    - **js**: Archivos de JavaScript.
      - `main.js`: Código JavaScript para interacciones dinámicas.
    - `index.php`: Punto de entrada de la aplicación.
  - **config**: Configuración de la aplicación.
    - `database.php`: Configuración de la base de datos.

## Instalación

1. Clona el repositorio en tu máquina local.
2. Navega a la carpeta del proyecto.
3. Configura la base de datos en `src/config/database.php`.
4. Instala las dependencias utilizando Composer:
   ```
   composer install
   ```
5. Abre `src/public/index.php` en tu navegador para acceder a la tienda online.

## Uso

- Los usuarios pueden registrarse y acceder a su cuenta.
- Los productos pueden ser visualizados en una lista y se pueden ver sus detalles.
- Los usuarios pueden agregar productos a su carrito y gestionar su contenido.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, por favor abre un issue o envía un pull request.

## Licencia

Este proyecto está bajo la Licencia MIT.