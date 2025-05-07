# Release Notes - Abril 2025

## Invu POS

### New Features
- **Integraciones de Pago**: Ahora Invu POS es compatible con los métodos de pago ADYEN y BOLD (Colombia).
- **Confirmación de Número de Invitados**: Al abrir una orden en el iPad, se muestra una alerta de confirmación al ingresar más de 15 invitados.
- **Eliminar cliente de una orden**: Se añadió un botón para eliminar al cliente directamente desde la orden.
- **Reporte de Cierre del Día**: Nuevo informe que permite ver toda la actividad financiera del día y realizar acciones clave como cierre de turno y registro de depósitos bancarios.

### Improvements
- **Apertura de caja**: Ahora se muestra automáticamente la suma total del efectivo ingresado.
- **Facturación electrónica**: Se actualizó para incluir descripción del producto, precio unitario, cantidad y valor total.
- **Edición de descripciones de ítems**: Al editar, se muestra el texto anterior como referencia.
- **Sumatoria total en órdenes divididas**: Se muestra el total individual por suborden y la suma total de la orden padre.

### Bug Fixes
- **Ítems bloqueados por cantidad**: Ahora el sistema controla la cantidad total acumulada y bloquea automáticamente al alcanzar el límite.

---

## ADMIN

### New Features
- **Importador Masivo de Imágenes**: Permite subir imágenes en lote utilizando una plantilla Excel.
- **Promociones por Descuento %**: Se habilitó la opción de configurar promociones con descuentos por porcentaje.
- **Revertir Orden de Compra Parcial**: Nueva funcionalidad para revertir órdenes de compra parcialmente recibidas.

### Improvements
- **Orden de modificadores**: El campo fue renombrado y ahora los cambios se replican automáticamente en todas las sucursales.
- **Pantalla de Productos en negocios Retail**: Se añadió información detallada sobre productos e ítems.
- **Excel de Requisiciones – Columna de Estatus**: Se añadió una columna de estatus para mejorar el seguimiento.
- **Impuesto incluido en archivo de productos**: Soporte para manejar el campo de impuesto incluido en plantillas.

### Bug Fixes
- **Información de recetas muy largas**: Se corrigió un problema que impedía exportar recetas extensas.
- **Orden de compra no muestra proveedores**: Se solucionó un error donde los proveedores no aparecían correctamente.
- **Error en unidad en requisición**: Se resolvió un problema donde las unidades mostradas no coincidían con las configuradas.

---

## REPORTES

### New Features
- **Reporte de Tasa de cambio**: Nuevo reporte para consultar la tasa de cambio utilizada en operaciones en moneda extranjera.

### Improvements
- **Reporte de Categorías**: Ahora el subtotal muestra los montos después de aplicar descuentos, alineándose con el Reporte Z.

### Bug Fixes
- **Correos fin de día**: Se solucionó un problema que impedía el envío correcto de correos automáticos de cierre.
- **Usuarios inactivos siguen recibiendo reportes beta**: Se bloqueó el envío de reportes beta a usuarios inactivos.
- **Reporte de Comisiones – Falla con notas de crédito**: Se corrigió un error donde las notas de crédito no se reflejaban correctamente.

*Release Date: April XX, 2025*
