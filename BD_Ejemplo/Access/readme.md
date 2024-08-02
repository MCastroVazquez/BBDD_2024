# Base de Datos Neptuno

La base de datos Neptuno es una base de datos de ejemplo proporcionada por Microsoft para aprender y practicar habilidades en Microsoft Access. Es una herramienta educativa diseñada para demostrar cómo funcionan las bases de datos relacionales y cómo se pueden usar en aplicaciones comerciales.

## Estructura de la Base de Datos Neptuno

### Tablas Principales

- **Productos**: Contiene información sobre los productos que la empresa vende, incluyendo detalles como el nombre del producto, el proveedor, la categoría, la cantidad por unidad, el precio unitario, las unidades en stock, las unidades en pedido y el nivel de pedido mínimo.
- **Proveedores**: Incluye información sobre los proveedores de los productos, como el nombre del proveedor, la dirección, la ciudad, la región, el código postal, el país, el teléfono, el fax y la página web.
- **Categorías**: Describe las diferentes categorías de productos, incluyendo el nombre de la categoría y una descripción.
- **Clientes**: Contiene datos sobre los clientes, incluyendo el nombre del cliente, el nombre del contacto, el título del contacto, la dirección, la ciudad, la región, el código postal, el país, el teléfono y el fax.
- **Pedidos**: Registra las órdenes de compra realizadas por los clientes, incluyendo el ID del pedido, el ID del cliente, el ID del empleado que gestionó el pedido, la fecha del pedido, la fecha de entrega, la fecha de envío, el método de envío, el coste del envío y la dirección de envío.
- **Detalles de Pedidos**: Detalla los productos incluidos en cada pedido, incluyendo el ID del pedido, el ID del producto, el precio unitario, la cantidad, el descuento aplicado y el importe total.
- **Empleados**: Contiene información sobre los empleados de la empresa, como el nombre del empleado, el título, la fecha de nacimiento, la fecha de contratación, la dirección, la ciudad, la región, el código postal, el país, el teléfono, el teléfono de emergencia, el jefe directo y notas adicionales.
- **Transportistas**: Incluye información sobre las empresas de transporte utilizadas para enviar los pedidos, como el nombre del transportista y el teléfono.

### Relaciones

- **Productos y Categorías**: Relación uno a muchos entre Categorías y Productos. Una categoría puede tener múltiples productos, pero un producto pertenece a una sola categoría.
- **Productos y Proveedores**: Relación uno a muchos entre Proveedores y Productos. Un proveedor puede suministrar múltiples productos, pero un producto tiene un solo proveedor.
- **Pedidos y Clientes**: Relación uno a muchos entre Clientes y Pedidos. Un cliente puede hacer múltiples pedidos, pero un pedido es realizado por un solo cliente.
- **Pedidos y Empleados**: Relación uno a muchos entre Empleados y Pedidos. Un empleado puede gestionar múltiples pedidos, pero un pedido es gestionado por un solo empleado.
- **Pedidos y Transportistas**: Relación uno a muchos entre Transportistas y Pedidos. Un transportista puede enviar múltiples pedidos, pero un pedido es enviado por un solo transportista.
- **Pedidos y Detalles de Pedidos**: Relación uno a muchos entre Pedidos y Detalles de Pedidos. Un pedido puede tener múltiples detalles de pedido, pero un detalle de pedido pertenece a un solo pedido.
- **Productos y Detalles de Pedidos**: Relación uno a muchos entre Productos y Detalles de Pedidos. Un producto puede estar en múltiples detalles de pedido, pero un detalle de pedido se refiere a un solo producto.

## Propósito y Uso

La base de datos Neptuno se utiliza para:
- Aprender y practicar la creación de consultas en SQL.
- Diseñar formularios y reportes en Access.
- Entender cómo se estructuran y gestionan las bases de datos relacionales.
- Realizar ejercicios y proyectos en cursos de bases de datos.

Es una herramienta valiosa para estudiantes, instructores y cualquier persona interesada en aprender sobre bases de datos relacionales y su aplicación en un entorno comercial.


## neptuno.mdb
Versión de MS Access 2000.
## neptuno.accdb
Versión de MS Access 2007-2016
