# Cancelación de compra

#### Roles autorizados
- Dirección

#### Menú autorizados
- Compras

#### ¿Qué hace la cancelación de compra?    
    Si la compra no se ha autorizado:
      1.- Se actualiza el estatus de la solicitud de compra a CANCELADO.
      2.- Se actualiza el estatus del vehículo a CANCELADO.

####

    Si la compra se ha autorizado:
      1.- Identificar si existen pagos registrados a la compra.
          - Por cada pago, se realiza el retorno de dinero a la cuenta de banco correspondiente.
          - Se actualiza el estatus de los pagos a CANCELADO.
      2.- Se actualiza el estatus de las CXPs por costo de compra y/o comisión a CANCELADO.
      3.- Se actualiza el estatus de la solicitud de compra a CANCELADO.
      4.- Se actualiza el estatus del vehículo a CANCELADO.
          
