# Ruta Clara — borrador de guía de uso y validación

Equipo: Los 6 indecisos · Liderazgo y Emprendimiento · UNIAJC

## 1. Objetivo

Probar si una persona puede registrar y consultar información básica de inventarios, pedidos y despachos con facilidad. La aplicación contiene datos ficticios para explorar. Todavía no se ha demostrado una mejora de tiempo: esa conclusión depende de las pruebas que realice el equipo.

## 2. Antes de empezar

- Abre el enlace de la aplicación cuando se publique, o abre `index.html` en un navegador actualizado.
- Cada navegador guarda sus propios cambios. Otra persona que abra el enlace verá su copia, no los pedidos que tú creaste.
- Los registros pueden perderse si se borran los datos del navegador. Usa solo información ficticia.
- El inventario se modifica manualmente; crear o entregar un pedido no descuenta unidades automáticamente.
- Almacenamiento local no es una base de datos compartida ni una solución final para operar una empresa.

## 3. Recorrido para el usuario

1. **Resumen:** identifica cuántos productos, pedidos activos y alertas aparecen. Selecciona la campana para consultar los avisos.
2. **Inventario:** busca “Cinta de embalaje”. Observa que tiene 12 unidades y un mínimo de 20. En Editar, cambia las unidades a 40 y guarda. Revisa que el estado cambie a Disponible y que desaparezca su alerta.
3. **Pedidos y despachos:** selecciona Nuevo pedido. Usa cliente ficticio “Tienda Prueba”, producto “Cajas de cartón medianas”, cantidad 3 y fechas coherentes. Guarda, busca el pedido y cámbialo de Pendiente a En preparación, Enviado y Entregado.
4. **Reportes:** crea “Pedidos por cliente”, agrupa por cliente y guarda. Identifica el pedido nuevo en el gráfico. Edita el reporte, prueba otro filtro y expórtalo a CSV.
5. **Restaurar:** en Guía de uso selecciona Restaurar datos de ejemplo si necesitas repetir todo desde cero. Se borrarán los cambios guardados en ese navegador.

## 4. Propuesta para validar con una persona

Inviten, si es posible, a una persona relacionada con una pequeña distribuidora. También pueden hacer una simulación con un compañero y declararlo expresamente. Expliquen que se evalúa el prototipo, no a la persona. Pídanle que intente las tareas sin instrucciones adicionales y registren:

| Actividad | ¿La completó? | Tiempo opcional | Dificultad o comentario | Evidencia autorizada |
|---|---|---|---|---|
| Identificar producto con existencias bajas | | | | |
| Actualizar las existencias | | | | |
| Crear y localizar un pedido | | | | |
| Cambiar el estado a Entregado | | | | |
| Crear un reporte y entender el resultado | | | | |

Preguntas: ¿Qué fue fácil? ¿En qué parte dudó? ¿Qué información faltó? ¿En qué parte considera que podría ahorrar pasos? ¿Qué cambiaría antes de usarlo en su trabajo?

Para comparar tiempos, usen exactamente el mismo escenario ficticio en el proceso actual y en el prototipo, registren los pasos y tiempos observados y expliquen que el resultado corresponde a esa prueba, no a una mejora general demostrada. Registren fecha, modalidad, rol de la persona, acciones, resultado, problema y ajuste; pidan autorización antes de guardar imágenes o testimonios.

## 5. Relación con la rúbrica

- Ejecución: registrar tareas desarrolladas y fecha.
- Evidencia: capturas del prototipo, anotaciones de las pruebas y cambios verificables.
- Situaciones reales: describir lo ocurrido, por qué, decisión y ajuste, solo si sucedió.
- Aprendizaje: resumir lo observado y próximos cambios.
- Aportes: cada uno de los seis integrantes registra su participación real, evidencia, dificultad y reflexión.

## 6. Puesta en línea

La carpeta `web` contiene el sitio estático. Puede alojarse en Vercel desde un repositorio. La aplicación no requiere base de datos ni claves para esta versión. Compartir el enlace da acceso a una copia del prototipo; no sincroniza los datos entre visitantes.
