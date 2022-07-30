# Cancelación de préstamo a deudor

#### Roles autorizados
- Dirección
- Tesorería

#### Menú autorizados
- Salidas | Préstamos a dedudores

#### ¿Qué hace la cancelación de préstamo?    
    1.- Se identifica la CXC del deudor corresponiente en el menú [Entradas | Crédito otros]
    2.- Se identifica si existen cobros registrados a la CXC del deudor.
        - Por cada cobro, se realiza la salida de dinero a la cuenta de banco correspondiente.
        - Se actualiza el estatus de los cobros a CANCELADO.
    3.  Se actualiza el estatus de la CXC a CANCELADO.
        
 ####
  
    4.- Se identifica la CXP por el préstamo corresponiente en el menú [Salidas | Préstamos a dedudores]
    5.- Por cada pago, se realiza el ingreso de dinero a la cuenta de banco correspondiente.
        - Se actualiza el estatus de los pagos a CANCELADO.
    6.  Se actualiza el estatus de la CXP a CANCELADO.
    
    
###### CXC: Cuenta por cobrar
###### CXP: Cuenta por pagar
