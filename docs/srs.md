### HU-02 – Pagar Pedido

Como usuario registrado
quiero pagar mi pedido con tarjeta
para confirmar la compra

--- 

### Criterios de Aceptación
-	Debe validarse información de la tarjeta.
-	No debe confirmarse pedido si el pago falla.
-	Debe mostrarse confirmación de pago exitoso.


## HU-03 – Seguimiento de Pedido

Como usuario registrado
quiero ver el estado de mi pedido
para saber cuándo llegará

---

### Criterios de Aceptación
- Debe mostrar estados: en preparación, en camino, entregado.
- Debe actualizarse en tiempo real.
- Solo el propietario del pedido puede verlo.

---

**RNF-01 Rendimiento:**

Las consultas de estado deben responder en menos de 2 segundos.

**RNF-02 Seguridad:**

La información de pago debe transmitirse mediante protocolo seguro.
