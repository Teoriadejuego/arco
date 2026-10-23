# ARCO

**SALMER recoge · DOVELA prepara · CLAVE permite consultar.**

Demostración de herramientas para centros educativos, con datos simulados.

- [Abrir la web](https://teoriadejuego.github.io/arco/).
- [Recorrido acompañado SALMER → DOVELA → CLAVE](https://teoriadejuego.github.io/arco/DEMO.html).
- [Probar SALMER](https://teoriadejuego.github.io/arco/SALMER.html).
- [Preparar un informe en DOVELA](https://teoriadejuego.github.io/arco/DOVELA.html).
- [Consultar en CLAVE](https://teoriadejuego.github.io/arco/CLAVE.html).
- [Caso SALMER: tipos de situaciones](https://teoriadejuego.github.io/arco/CLAVE-SALMER.html).

La demo acompañada permite responder, elegir entre informe breve o completo y abrir CLAVE sin descargar archivos ni recordar contraseñas. Su guía es opcional y los datos solo permanecen en memoria hasta cerrar o recargar. El recorrido integrado necesita HTTP(S).

DOVELA permite autorizar la exportación de PDF por perfil. CLAVE descarga la vista con marca de agua y contraseña de apertura igual al nombre de usuario; la clave del .arco sigue siendo independiente. Los informes antiguos deben regenerarse en DOVELA para habilitar este permiso. En la demo acompañada el usuario es orientacion.

Las redes incluyen «Otra visualización», que agrupa los estudiantes por comunidades exploratorias y mantiene las flechas y sus tipos de relación.

La portada ofrece cuatro informes simulados y un caso completo de SALMER, con Excel, plantillas y paquetes de ejemplo. Las contraseñas de demostración son públicas deliberadamente.

Cada herramienta incluye sus recursos en su HTML y puede guardarse para uso local. No requiere instalar R ni Node. La lectura de archivos y los cálculos se realizan en el navegador; no se envían respuestas ni archivos a un servidor. GitHub sirve las páginas y recibe las solicitudes habituales de navegación.

SALMER es una encuesta de demostración: no hay recogida real ni conexión con LimeSurvey. Las consultas no se guardan de forma persistente; conserva los archivos descargados si los necesitas. Las claves sencillas y los ejemplos sirven para evaluar la herramienta, no constituyen una certificación de seguridad para datos sensibles reales.

Este repositorio contiene exclusivamente la distribución pública generada. No incluye datos reales, informes privados, directorios de trabajo ni credenciales de usuarios reales. Los métodos de cálculo se mantienen respecto a la revisión local.

La entrega se comprueba mediante pruebas de modelos, contratos, flujos simulados y verificación de scripts/enlaces. La revisión completa en dispositivos destinatarios sigue pendiente. El lector Excel SheetJS se distribuye con su licencia en LICENCIA-SheetJS.txt. PDFKit, SVG-to-PDFKit y DejaVu se distribuyen con sus licencias en LICENCIAS-PDF.txt.

Publicación: rama main, carpeta raíz, con GitHub Pages. La carpeta se prepara desde las fuentes locales mediante herramientas/build-all.mjs y herramientas/preparar-github.mjs; no se debe subir el árbol privado de trabajo.
