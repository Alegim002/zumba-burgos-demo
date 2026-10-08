# Zumba Burgos · Demo independiente

Propuesta independiente de Agallart Digital. Modalidades y nombres de sedes basados en la web pública de Zumba Burgos, revisada el 8 de octubre de 2026. Alumnos, consultas, sesiones, asignaciones de sedes, horarios, aforos y asistencias ficticios, sin datos de clientes ni precios vigentes supuestos.

Incluye cuatro apartados:

- Consultas: modalidad de interés, tipo de solicitud, filtros, creación de ejemplos, edición, cambios de estado y notas. Las recuperaciones se vinculan a clases regulares.
- Alumnos: búsqueda y filtro de modalidad, ficha con historial, asistencias y próximas clases. Cada participación distingue inscripción regular, clase suelta, recuperación o reserva especial.
- Calendario: vista mensual navegable y filtrada por modalidad, sesiones por día, sede y aforo de ejemplo, con participantes de cada sesión. Desde cada clase se puede abrir la ficha del alumno y desde su historial, la clase correspondiente.
- Servicios: clases regulares, clase suelta/primera visita y clases especiales; enlaces a las fuentes y acceso al calendario de cada modalidad. Recuperación como condición de las clases regulares, sedes publicadas y aviso de tarifas pendientes de confirmar.

El calendario abre en octubre de 2026 para mostrar sesiones ficticias. Las sedes reales se usan como nombres de referencia; su asignación a cada sesión es inventada. Los datos solo viven en memoria y los cambios se reinician al recargar. No envía mensajes, reserva clases, modifica formularios del negocio ni procesa pagos. No introducir datos personales reales.

El panel (`index.html`) es un HTML autónomo. La nueva web (`web.html`) usa una imagen ilustrativa optimizada (`hero.svg`). Se sirven con GitHub Pages desde la raíz de main.

## Nueva web de ejemplo

- Portada, modalidades, calendario mensual con filtros, sedes y preguntas frecuentes. Diseño adaptable a móvil, basado en la propuesta visual adjunta y en la estructura de servicios de la web oficial. La web original devolvía un error 502 al intentar revisar su apariencia el 8 de octubre de 2026; no se afirma que los colores o el logotipo provisional reproduzcan exactamente su identidad.
- El formulario utiliza únicamente personas y correos ficticios predefinidos. Permite inscripciones, reservas y recuperaciones compatibles con las condiciones de ejemplo; rechaza duplicados y personas ya presentes en una clase.
- La solicitud muestra un enlace al CRM con identificadores ficticios en el fragmento de la URL. Al abrirlo, el panel crea una consulta por responder y la vincula al alumno y a la sesión como solicitud pendiente de revisión. No hay backend, correos ni pagos. El fragmento se retira de la barra de direcciones y recargar restablece los ejemplos.
- La imagen de portada es una ilustración fotográfica generada con personas ficticias; no representa a Mariángeles ni a sus clientes. El sitio es una propuesta independiente, no una web oficial.
- La integración real requeriría autenticación, almacenamiento, disponibilidad real, consentimiento y reglas de confirmación acordadas con el negocio.

Validación: pruebas de solicitudes, duplicados, condiciones de recuperación, vínculo web → CRM, alumno, sesión, historial y restablecimiento; revisión posterior de la web publicada.

Fuentes oficiales revisadas:

- https://zumbaburgos.com/ — actividad y sedes.
- https://zumbaburgos.com/normativa-general/ — inscripciones, aforo, prorrateo, recuperaciones de lunes a jueves entre octubre y junio, y clases especiales con reserva y tarifa independiente.
- https://zumbaburgos.com/preguntas-frecuentes/ — clase suelta para probar antes de inscribirse.
- https://zumbaburgos.com/reservas/ — reservas de sesiones especiales de fin de semana.
- https://zumbaburgos.com/ubicacion/ — Social Dance y Polideportivo María Mediadora.
- https://zumbaburgos.com/tarifas-2/ — la página y los documentos recuperados incluían temporadas 2025/26 y 2024/25. No se trasladan esos importes como tarifas vigentes de 2026/27; precios, cuotas y aforos reales pendientes de validación con Mariángeles.

Los servicios publicados se han convertido en campos y vistas de una propuesta de CRM. No se afirma que el negocio utilice este sistema ni existe conexión con su web o formularios actuales. El enlace desde la web nueva es una simulación local con datos ficticios.
