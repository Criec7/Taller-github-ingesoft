### HU-02 – Pagar Pedido


Como usuario registrado
quiero pagar mi pedido con tarjeta
para confirmar la compra

--- 

### Criterios de Aceptación
-	Debe validarse información de la tarjeta.
-	No debe confirmarse pedido si el pago falla.
-	Debe mostrarse confirmación de pago exitoso.
**RNF-01 Rendimiento:**

Las consultas de estado deben responder en menos de 2 segundos.

**RNF-02 Seguridad:**

La información de pago debe transmitirse mediante protocolo seguro.

### Tabla de contenido

| Integrante | Responsabilidad                     |
|------------|--------------------------------------|
| 1          | HU-01 – Crear Pedido                |
| 2          | HU-02 – Pago del Pedido             |
| 3          | HU-03 – Seguimiento de Pedido       |
| 4          | Requerimientos No Funcionales (RNF) |
| 5          | Tabla de Contenido (TOC)            |
| 6          | Tabla de Trazabilidad               |

### Tabla de trazabilidad

| HU              | RF            | Caso de Prueba                               | Estado     |
|:--------------- |:-------------:| --------------------------------------------:|:-----------|
|  HU1            | RF-01         |  Crear un pedido                             |  Pendiente |
|  HU2            | RF-02         |  Validar el pago del pedido                  |  Pendiente |
|  HU3            | RF-03         |  Validar el seguimiento del pedido           |  Pendiente |
