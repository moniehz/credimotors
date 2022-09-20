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

Razón: Existe un proceso para cancelar la compra desde su origen, la cual actualiza los CXP a un estatus a CANCELADO, por lo que no se debe eliminar movimientos por separado.

<br />

## En cancelación de venta

- Remover los siguientes permisos en el formulario de CXC Entradas | Crédito directo / Contado / Crédito bancario / Enganche de autos <br />
DELETE <br />
UPDATE <br />

Razón: Existe un proceso para cancelar la venta desde su origen, la cual actualiza las CXC a un estatus a CANCELADO, por lo que no se debe poder eliminar movimientos por separado.


<br />

## En cancelación de préstamo a deudor
