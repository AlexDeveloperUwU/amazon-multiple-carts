# Better Amazon Carts

Un pequeño proyecto personal para poder tener múltiples "carritos" de compra de Amazon.

## Descripción
Este proyecto surge de la necesidad de gestionar múltiples carritos de compra en Amazon, especialmente cuando se comparte una única cuenta familiar con Amazon Prime. En mi familia, todos utilizamos la misma cuenta, lo que genera un caos cuando cada uno añade productos al carrito.

Normalmente, utilizo una WishList para organizar mis cosas o lotes de productos que quiero comprar. Sin embargo, esto no resulta muy conveniente, especialmente en el caso de los lotes. Si hago una lista para un lote de productos, es porque quiero ahorrar para comprar todo lo que está en esa lista. Pero, tal como está diseñado Amazon, no puedo ver el precio total ni añadir todo de golpe al carrito.

Por eso, he decidido iniciar este proyecto. El objetivo es poder crear múltiples carritos de compra personalizados, agregar productos a estos carritos y ver el precio total de cada uno. Esto facilitará la gestión de compras familiares en una cuenta compartida, mejorando la organización y el proceso de compra.

## Dev Stack
- Node.js V22 (Next LTS)
- Express.js
- Enmap (SQLite)
- TailwindCSS

> El stack se irá actualizando poco a poco a medida que el proyecto avance.

## Características
- **Múltiples Carritos**: Crear y gestionar varios carritos de compra independientes.
- **Cálculo del Precio Total**: Ver el precio total de los productos en cada carrito.
- **Añadir Todo al Carrito**: Opción para añadir todos los productos de un carrito personalizado al carrito de compra de Amazon de una sola vez.
- **Gestión de Productos**: Añadir, eliminar y visualizar productos en cada carrito.

## Instalación

1. Clona el repositorio:
    ```sh
    git clone https://github.com/alexdeveloperuwu/better-amazon-carts.git
    cd better-amazon-carts
    ```

2. Instala las dependencias:
    ```sh
    npm install
    ```

3. Inicia la aplicación:
    ```sh
    npm start
    ```

## Uso

1. Abre tu navegador y ve a `http://localhost:3000`.
2. Crea un nuevo carrito de compra.
3. Añade productos al carrito ingresando los enlaces o identificadores de productos de Amazon.
4. Visualiza el precio total del carrito.
5. Añade todos los productos del carrito al carrito de compra de Amazon de una sola vez.

## Contribución

Las contribuciones son bienvenidas. Puedes ayudar de las siguientes maneras:

1. **Reportar Errores**: Si encuentras algún error, por favor, ábre un issue en GitHub.
2. **Solicitudes de Funcionalidades**: Si tienes ideas para nuevas características, también puedes abrir un issue.
3. **Enviar Pull Requests**: Si deseas contribuir con código, haz un fork del repositorio y envía un pull request con tus cambios.