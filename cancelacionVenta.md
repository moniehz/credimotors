
# Cancelación de venta

#### Roles autorizados
- Dirección

#### Menú autorizados
- Ventas

#### ¿Qué hace la cancelación de venta?    
    Las ventas pueden generar CXCs con el siguiente origen:
      - Venta de contado
      - Venta a crédito directo
      - Venta a crédito bancario
      - Venta a crédito directo y crédito bancario
      
     Para cualquier origen, el proceso de cancelación es el mismo. Estás CXCs se pueden visualizar en el menú [Entradas].

####

      1.- Por cada CXC se identifica si existen cobros registrados a la venta.
          - Por cada cobro, se realiza la salida de dinero de la cuenta de banco correspondiente.
          - Se actualiza el estatus de los cobros a CANCELADO.
      2.- Se actualiza el estatus de las CXCs por la venta a CANCELADO.
      3.- Se actualiza el estatus del vehículo a CANCELADO.
      4.- Se actualiza el estatus de la solicitud de venta a CANCELADO.
      5.- Se actualiza el estatus de la venta a CANCELADO.


###### CXCs: Cuentas por cobrar
