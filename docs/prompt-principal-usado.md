# Prompt principal usado con Lovable

Este archivo conserva el PRD inicial enviado a Lovable. El proyecto evolucionó en iteraciones posteriores; por eso, algunas decisiones de esta primera versión no describen la demo actual.

## Texto original
Velora
1. Rol del Asistente (Meta Prompting)
Eres un diseñador/desarrollador experto en UI/UX y Mobile-First, centrado en la estética, la conversión y la experiencia visual, y experto en el entorno nativo de Lovable (React, TypeScript, Tailwind CSS).

2. Descripción General y Visión
Velora es una tienda escaparate ficticia de sillas de oficina premium. Está dirigida a autónomos, personas que trabajan desde casa y nómadas digitales que buscan comodidad y diseño para su espacio de trabajo.

El sitio presentará diez modelos de sillas de oficina, con precios entre 450 y 900 €. La página de inicio destacará cuatro de esos modelos. La navegación permitirá explorar el catálogo completo, consultar los detalles de cada modelo y contactar con Velora. No se procesarán compras ni pagos en la web.

Eslogan: «Tu espacio de trabajo merece una silla a la altura».

Objetivo de conversión: animar a los visitantes a explorar los modelos y consultar sus detalles mediante llamadas a la acción destacadas, especialmente en la página de inicio.

3. Stack y Restricciones Técnicas
Frontend: React + TypeScript + Tailwind CSS, componentes shadcn/ui, Mobile-First.
Backend: Sin backend. El catálogo utilizará datos de demostración. El formulario mostrará una confirmación visual, pero no enviará ni guardará los datos.
Autenticación: No requerida. No habrá inicio de sesión ni cuentas de usuario.
Integraciones: No aplica. No incluir pagos online.
4. Flujo de Usuario y Estructura de Navegación
Páginas/secciones:
Inicio: hero con carrusel de sillas, eslogan, llamadas a la acción y cuatro modelos destacados.
Productos: catálogo completo con diez sillas, categorías y filtros.
Detalle de producto: una página para cada modelo con imagen, precio y características.
Quiénes somos: historia ficticia de Velora.
Contacto: formulario y datos ficticios de contacto, visibles también en el pie de página.
Flujo hasta la conversión: el visitante llega a Inicio → explora las imágenes del carrusel y los cuatro modelos destacados → pulsa «Comprar ahora» → consulta la página de detalle de la silla. También puede entrar en «Productos» desde el menú, filtrar el catálogo y abrir cualquier modelo. El formulario permite simular el envío de una consulta.
5. Funcionalidades Clave
Inicio y llamadas a la acción: mostrar el eslogan, un carrusel de sillas con flechas laterales y cuatro modelos destacados. Incluir botones visibles como «Descubre las sillas» y «Comprar ahora». El botón «Comprar ahora» abre el detalle del modelo correspondiente.
Menú y selección de idioma: colocar en la parte superior derecha un menú de tres barras con enlaces a Inicio, Productos, las categorías y Quiénes somos. Añadir un control visible para cambiar entre español e inglés. Traducir todos los textos y conservar la sección actual al cambiar de idioma.
Catálogo y filtros: mostrar los diez modelos con sus imágenes, categorías, colores, precios y características. Permitir filtrar por precio, color y tipo de soporte lumbar. Las categorías serán:
Compactas
Ergonómicas
Ejecutivas
Modelos de demostración:
Velora Noma Compact — 479 €: silla compacta, disponible en arena y grafito, con respaldo de malla y altura regulable.
Velora Luma — 549 €: silla ergonómica en crema, verde oliva y grafito, con soporte lumbar ajustable.
Velora Forma Air — 629 €: silla ergonómica en arena y carbón, con respaldo de malla y reposabrazos regulables.
Velora Axis Pro — 699 €: silla ergonómica en verde oscuro y negro, con respaldo reclinable y ajuste de profundidad del asiento.
Velora Sora Executive — 829 €: silla ejecutiva en marrón y negro, con asiento acolchado y respaldo reclinable.
Velora Atelier — 899 €: silla ejecutiva en crema y marrón oscuro, con respaldo alto y reposabrazos regulables.
Velora Nube Compact — 519 €: silla compacta en marfil y verde oscuro, con respaldo ventilado y soporte lumbar integrado.
Velora Luma Pro — 589 €: silla ergonómica en azul acero, negro y arena, con soporte lumbar y reposabrazos regulables.
Velora Balance — 749 €: silla ergonómica en grafito y verde bosque, con respaldo reclinable y profundidad de asiento regulable.
Velora Arden Executive — 859 €: silla ejecutiva en caramelo y crema, con respaldo alto acolchado y reposabrazos regulables.
Detalle de producto: cada modelo tendrá imágenes, precio, categoría, colores disponibles y una descripción de sus características. Incluir un botón «Comprar ahora» que lleve a esa página de detalle. No debe abrir un carrito ni iniciar un pago.
Envíos: mostrar que Velora vende en toda Europa, con un coste de envío de 3 € y un plazo de entrega de 3 días.
Quiénes somos: contar una historia ficticia sobre el origen de Velora y su interés por combinar comodidad y diseño para trabajar desde casa.
Formulario de contacto: incluir los campos nombre, email y mensaje. Al pulsar «Enviar», mostrar una confirmación visual. No enviar ni almacenar los datos.
Pie de página: mostrar el formulario de contacto y estos datos ficticios de demostración:
Dirección: Carrer del Disseny 24, 08018 Barcelona, España.
Teléfono: +34 900 123 456.
Email: hola@velora-home.es.
Sede: Barcelona, España.
6. Lineamientos de Diseño UI/UX
Estilo visual: tienda de mobiliario cuidada, cálida y minimalista, con fotografías amplias de producto y una presentación premium.
Colores: fondo marfil #F7F4EF; texto principal carbón #24231F; botones principales verde oscuro #34433B; hover verde profundo #26332D; acentos arena #B78D63; tarjetas blancas #FFFFFF.
Tipografía: DM Serif Display para títulos e Inter para textos y controles.
Componentes y layout: menú hamburguesa de tres barras en la esquina superior derecha; selector de idioma visible; hero con carrusel de sillas y flechas laterales; bloques de producto; filtros en el catálogo; páginas de detalle; sección «Quiénes somos»; formulario y pie de página. Los títulos deben ser grandes y legibles. Mantener las llamadas a la acción visibles en Inicio y en los productos.
Responsividad: diseño Mobile-First, con controles utilizables en móvil y escritorio. Mantener las flechas del carrusel visibles y adaptadas a pantallas pequeñas.
Referencias visuales: usar la imagen adjunta como referencia de composición, tonos cálidos, presentación del catálogo, productos y pie de página. Las imágenes y productos del sitio deben mostrar exclusivamente sillas de oficina. Crear una imagen de silla para la portada del carrusel y una imagen para cada modelo.
7. Alcance del Proyecto (Scope)
Incluido (MVP):

Página de inicio con carrusel de sillas, eslogan, CTAs y cuatro modelos destacados.
Catálogo de diez modelos con categorías y filtros por precio, color y soporte lumbar.
Página de detalle para cada silla.
Menú hamburguesa y cambio entre español e inglés.
Página «Quiénes somos» con historia ficticia.
Formulario de contacto con confirmación visual simulada.
Datos ficticios de contacto y de sede.
Información de envío a toda Europa: 3 € y entrega en 3 días.
Excluido:

Pagos, carrito y proceso de compra.
Inicio de sesión y cuentas de usuario.
Páginas de privacidad y términos y condiciones.
Cualquier otro elemento no especificado en los requisitos.
Nota final
Utiliza toda la información anterior al generar el sitio.

Sigue al pie de la letra los lineamientos y no asumas requisitos adicionales fuera de esta especificación.

Si algo es ambiguo, prioriza la interpretación que mantenga la lógica del producto según la visión descrita.

Antes de generar código, confirma tu entendimiento en modo conversación (Chat Mode).

Construiremos la base según este PRD y después iteraremos.
