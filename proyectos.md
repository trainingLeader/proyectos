# Proyecto Nro. 1

Crear un programa en java que permita llevar el control y administración de medicamentos de una  farmacia.

## Requerimientos técnicos

1. Usar Arquitectura Hexagonal + Vertical Slicing
2. Crear base de datos relacional
3. Implementar interfaz de usuario para gestionar la información de los clientes.

## Casos de Uso

### Caso 1

El gerente desea llevar una relación de todos los clientes que realizan las compras en su establecimiento. La información que el establecimiento tiene de cada cliente es la siguiente : Nro de identificación, tipo de identificación, nombres, apellidos, edad, fecha de nacimiento, fecha de registro(La fecha de registro se debe generar de forma automatica cuando el cliente es creado), ciudad de residencia, barrio de residencia. 

### Caso 2

La persona encargada de llevar el control del inventario desea poder realizar el registro y seguimiento del inventario de todos los productos de la farmacia. La información de cada uno de los productos es la siguiente : Codigo producto, nombre del producto, registro invima del producto, via de administracion, principio activo, unidad de medida, laboratorio, proveedor, presentación, fecha de caducidad, stock, stock min, stock maximo, valor venta.

Condiciones a tener en cuenta : El valor venta dependerá del valor promedio de compra.

Precio de venta = Costo del producto × (100% + Margen de ganancia deseado).