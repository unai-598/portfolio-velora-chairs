# Comprobaciones y límites

[Volver a la presentación](../README.md) · [Recorrer la demo](recorrido.md)

## Alcance de esta revisión

Documento una comprobación manual de la demo pública de Velora realizada el **20 de octubre de 2026**, en un navegador de escritorio. Las acciones se realizaron sobre la interfaz publicada. Este registro describe lo observado en esa revisión; no constituye una certificación del sitio ni una auditoría de su código.

## Acciones y resultados observados

| Comprobación | Acción | Resultado observado |
| --- | --- | --- |
| Inicio | Abrir la demo. | Se muestra la presentación de Velora y el aviso de proyecto de portfolio con tienda ficticia. |
| Catálogo | Abrir «Productos» con todas las categorías. | El contador indica 10 modelos y aparecen controles de precio máximo, color y soporte lumbar. |
| Categoría | Seleccionar «Compactas». | El contador cambia a 2 modelos: Noma Compact y Nube Compact. |
| Ficha | Abrir Noma Compact. | Se muestran 479 €, características, colores y una galería con cuatro vistas seleccionables. |
| Galería | Cambiar de vista frontal a lateral. | El indicador cambia de «Vista frontal 1 / 4» a «Vista lateral 2 / 4» y la imagen seleccionada cambia. |
| Variante | Elegir «Grafito» en Noma Compact. | Cambia la etiqueta de color; el carrito conserva la variante Grafito al añadir la silla. |
| Añadir al carrito | Añadir una unidad de Noma Compact. | Aparece la confirmación y el contador del carrito pasa a 1. |
| Total de una unidad | Abrir el carrito con esa selección. | Subtotal 479 €; envío ilustrativo 3 €; total 482 €. |
| Aumentar cantidad | Subir de una a dos unidades. | El contador pasa a 2; subtotal 958 € y total 961 €. |
| Reducir y eliminar | Volver a una unidad y eliminar el producto. | El carrito queda vacío y el contador vuelve a 0. |
| Idioma | En «Contacto», cambiar de ES a EN. | La navegación, los textos principales y las etiquetas del formulario pasan al inglés. |
| Contacto | Leer el aviso junto al formulario. | Indica que es una demostración y que no se envían datos. No se enviaron datos personales para esta revisión. |

Las operaciones del carrito se revisaron con un producto y dos cantidades. No se comprobó una compra real. El carrito quedó vacío al finalizar y el idioma volvió a español.

## Evidencia visual

- [Inicio](../assets/01-inicio.png).
- [Catálogo](../assets/02-catalogo.png).
- [Ficha de Noma Compact](../assets/03-producto.png).
- [Carrito con una unidad y total ilustrativo](../assets/04-carrito.png).

Las capturas corresponden a estados concretos de la demo. El registro anterior complementa las imágenes con las acciones realizadas.

## Límites conocidos

- La marca, el catálogo, los precios, la dirección y los datos de contacto son ficticios.
- No se procesan pedidos, pagos ni envíos reales. El envío de 3 € y el plazo mostrado son ilustrativos.
- El formulario avisa de que no envía datos. No se verificó una integración de correo o un sistema de atención al cliente.
- La galería utiliza un acabado de muestra. La selección de color no garantiza una imagen específica para cada variante.
- No se ha medido impacto comercial, satisfacción de usuarios ni ahorro de tiempo.

## Aspectos no verificados

No se ha auditado el código, la seguridad, el almacenamiento del carrito, una base de datos ni una integración de pagos. Tampoco se ha realizado una revisión completa de traducciones, accesibilidad, rendimiento, compatibilidad entre navegadores o dispositivos móviles.

Los controles de precio, color y soporte lumbar se observaron en el catálogo, pero no se probaron todas sus combinaciones. El cambio de idioma se comprobó en la página de contacto; no implica una validación de todos los textos del sitio.

## Cómo mantener este registro

Cuando actualice la demo, revisaré de nuevo los recorridos afectados y anotaré la fecha y el resultado real. Mantendré las mejoras propuestas separadas de las funciones ya comprobadas.
