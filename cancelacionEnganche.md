# Cancelación de cobro por enganche de venta

#### Roles autorizados
- Dirección
- Tesorería

#### Menú autorizados
- Entradas | Enganches de autos

#### ¿Qué hace la cancelación de enganche?  
    Si el enganche aún no está ligado a una venta:
    
    1.- Se identifica la CXC del enganche corresponiente en el menú [Entradas | Enganches de autos]
    2.- Se identifica el cobro registraso a la CXC del enganche.
        - Se realiza la salida de dinero a la cuenta de banco correspondiente.
        - Se actualiza el estatus del cobro a CANCELADO.
    3.- Se actualiza el monto cobrado y monto pendiente de la CXC del enganche.
        - En caso de que el monto del cobro sea igual al monto total del enganche, se actualiza el estatus de CXC a CANCELADO.
 
 ####
    
    Si el enganche está ligado a una venta:
    
    1.- Se identifica la CXC del enganche corresponiente en el menú [Entradas | Enganches de autos]
    2.- Se identifica el cobro registraso a la CXC del enganche.
        - Se realiza la salida de dinero a la cuenta de banco correspondiente.
        - Se actualiza el estatus del cobro a CANCELADO.
    3.- Se identifica la venta en el menú [ventas] y se realiza la salida del enganche por el monto del cobro correspondiente.
    4.- Se actualiza el precio de venta de la unidad en el menú [ventas], tomando en cuenta el nuevo valor del enganche.
    5.- Se actualiza el monto cobrado y monto por cobrar de la CXC del enganche.
        - En caso de que el monto del cobro sea igual al monto total del enganche, se actualiza el estatus de la CXC a CANCELADO.
     
     
###### CXC: Cuenta por cobrar
