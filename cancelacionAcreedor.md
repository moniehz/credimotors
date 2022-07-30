# Cancelación de acreeedor

#### Roles autorizados
- Dirección
- Tesorería

#### Menú autorizados
- Entradas | Acreedores

#### ¿Qué hace la cancelación de acreedor?    
    1.- Se identifica la CXP del acreeedor corresponiente en el menú [Salidas | Acreedores]
    2.- Se identifica si existen pagos registrados a la CXP del acreedor.
        - Por cada pago, se realiza el ingreso de dinero a la cuenta de banco correspondiente.
        - Se actualiza el estatus de los pagos a CANCELADO.
    3.-  Se actualiza el estatus de la CXP a CANCELADO.
        
 ####
  
    4.- Se identifica la CXC por el acreedor corresponiente en el menú [Entradas | Acreedores]
    5.- Por cada cobro, se realiza la salida de dinero a la cuenta de banco correspondiente.
        - Se actualiza el estatus de los cobros a CANCELADO.
    6.-  Se actualiza el estatus de la CXC a CANCELADO.
    
    
###### CXP: Cuenta por pagar
###### CXC: Cuenta por cobrar
