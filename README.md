# Horario Escolar — Colegio del Pilar · V1.0.4 DE PRUEBA

Base: Colegio del Pilar V1.0.3 estable. Referencia visual: St. Matthew’s V1.0.1 y North Hills V1.0.3.

## Cambios exclusivos de esta versión

- Encabezado bajo el banner: «Horario Escolar» a la izquierda y 2027 a la derecha, sin cápsula «Ciclo».
- Selector conserva curso y división; franja inferior indica «Turno mañana / Turno tarde» y «MODO DEMO», sin repetir el curso.
- Las tarjetas muestran «· Hoy» junto al nombre del día, sin reemplazar la cantidad de clases. El estado cambia según fecha local, al volver a primer plano y mediante actualización periódica. En fines de semana no se marca ningún día.
- Actualización de versión visible en Ayuda y version.json; cambio de clave de caché del service worker.

No se modificaron las materias, los horarios ficticios de los 12 cursos, el ciclo lectivo de ejemplo 2027, los íconos de instalación, el banner, el escudo, las claves de preferencias ni la navegación. DEMO NO OFICIAL; no está asociada oficialmente al colegio.

## Instalación en GitHub Pages (solo después de aprobar)

Subir el contenido del ZIP a la raíz del repositorio del Colegio del Pilar. Mantener `index.html`, `service-worker.js`, `version.json`, `manifest.webmanifest` e íconos en la misma carpeta. GitHub Pages requiere HTTPS para instalar PWA.

**Estado: V1.0.4 DE PRUEBA. No publicar ni declarar estable hasta aprobación del usuario.**
