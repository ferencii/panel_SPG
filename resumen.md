# Resumen de cambios

## 2025-10-31
- Herramientas de formas: corregido el arranque/cierre de trazos y normalizado el cálculo de rectángulos y círculos.
- Panel de iconos: añadido selector lateral con los recursos de `iconos/` y soporte para colocarlos en el lienzo con escala controlada y caché en memoria.
- Interfaz: botón para limpiar selección de icono (inicia deshabilitado) y estados visuales en `icon-clear`, `icon-grid` y nuevos estilos `.icon-button`.
- Lógica general: se integró la herramienta `icon`, se evita interferir con los trazos activos y se refuerza el historial/undo tras colocar gráficos.
- Documentación: este registro (`resumen.md`) mantiene el detalle de ajustes aplicados.

### Pendientes / ideas futuras
- Ajustar redimensionado del historial al cambiar el tamaño de la ventana (actualmente `putImageData` depende del canvas fijo).
- Permitir variaciones de tamaño/rotación al insertar iconos.
