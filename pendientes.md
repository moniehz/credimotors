## En general
- Remover los siguientes permisos en el formulario de PAGOS <br />
DELETE  <br />
UPDATE <br />

- Remover los siguientes permisos en el formulario de COBROS <br />
DELETE  <br />
UPDATE <br />

Razón: Los PAGOS y COBROS están relacionados a procesos de cancelaciones, así como registro de compras y ventas, mismos que ya tienen un proceso para la salida o ingreso de bancos.

<br />

## En cancelación de compra

- Remover los siguientes permisos en el formulario de CXP  Salidas | Compra de vehículos, por el costo de compra y comisión <br />
DELETE <br />
UPDATE <br />

Razón: Existe un proceso para cancelar la compra desde su origen, la cual actualiza los CXP a un estatus a CANCELADO, por lo que no se debe eliminar ni actualizar movimientos por separado.

<br />

## En cancelación de venta

- Remover los siguientes permisos en el formulario de CXC Entradas | Crédito directo / Contado / Crédito bancario / Enganche de autos <br />
DELETE <br />
UPDATE <br />

Razón: Existe un proceso para cancelar la venta desde su origen, la cual actualiza las CXC a un estatus a CANCELADO, por lo que no se debe poder eliminar ni actualizar movimientos por separado.

<br />

## En cancelación de préstamo a deudor

- Remover los siguientes permisos en el formulario de CXP Salidas | Préstamos a deudores <br />
DELETE <br /> 
UPDATE -> (Siempre y cuando no se haya pagado en tu totalidad) <br />

- Remover los siguientes permisos en el formulario de CXC Entradas | Créditos otros <br />
DELETE <br /> 
UPDATE <br />

Razón: Existe un proceso para cancelar el préstamo a deudor desde su origen, la cual actualiza las CXP y CXC a un estatus a CANCELADO, por lo que no se debe poder eliminar movimientos por separado.

<br />

## En cancelación de  acreeedor

- Remover los siguientes permisos en el formulario de CXC Entradas | Acreedores <br />
DELETE <br /> 
UPDATE -> (Siempre y cuando no se haya cobrado en tu totalidad) <br />

- Remover los siguientes permisos en el formulario de CXP Salidas | Acreedores <br />
DELETE <br /> 
UPDATE <br />

Razón: Existe un proceso para cancelar el acreedor desde su origen, la cual actualiza las CXC y CXP a un estatus a CANCELADO, por lo que no se debe poder eliminar movimientos por separado.

<br />

## En cancelación de cobro por enganche de venta

- Remover los siguientes permisos en el formulario de CXC Entradas | Enganche de autos  <br />
DELETE -> (Siempre y cuando no este ligando a un venta concretada) <br /> 
UPDATE -> (Siempre y cuando no este ligando a un venta concretada) <br /> 

Razón: Existe un proceso para cancelar la venta desde su origen, la cual actualiza los CXC a un estatus a CANCELADO, por lo que no se debe eliminar ni actualizar movimientos por separado.

<br />

## En cancelación de pago por compra de vehículo

- Remover los siguientes permisos en el formulario de CXP Salidas | Compra de vehículos  <br />
DELETE <br />
UPDATE <br />

Razón: Existe un proceso para cancelar la compra desde su origen, la cual actualiza los CXP a un estatus a CANCELADO, por lo que no se debe eliminar ni actualizar movimientos por separado.

<br />

## En conceptos de CXP

- Remover los siguientes permisos en el formulario Catálogos | Conceptos de CXP  <br />
DELETE -> (Siempre y cuando no este ligando a movimientos de Salidas | Pasivos) <br />
UPDATE -> (Siempre y cuando no este ligando a movimientos de Salidas | Pasivos) <br />

<br />

## Controles en grid

- Agregar un indicador en la grid de ventas, para identificar las unidades vendidas pendientes por cobrar.
- Agregar un indicador a las grids de CXCs de Entradas | Crédito directo / Contado / Crédito bancario / Enganche de autos para identificar las CXCs de ventas pendientes por cobrar.
- Agregar un indicador a la grid de CXC de Entradas | Crédito otros para identificar los deudores pendientes por cobrar.
- Agregar un indicador a la grid de CXC de Entradas | Acreedores para identificar los acreedores pendientes por cobrar.

- Agregar un indicador a la grid de CXP de Salidas | Pasivos para identificar las CXPs de pasivos pendientes por pagar.
- Agregar un indicador a la grid de CXP de Salidas | Acreedores para identificar los acreedores pendientes por pagar.
- Agregar un indicador a la grid de CXP de Salidas | Capital para identificar las CXPs de capital pendientes por pagar.
- Agregar un indicador a la grid de CXP de Salidas | Préstamos a deudores para identificar las CXPs para préstamos pendientes por pagar.
- Agregar un indicador a la grid de CXP de Salidas | Compra de vehículos para identificar las CXPs de compras pendientes por pagar.
