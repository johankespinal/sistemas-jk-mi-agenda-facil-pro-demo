# Agenda Fácil PRO · Sistemas JK

**Demostración interactiva** de un sistema web para gestionar citas, clientes y servicios de negocios pequeños. Proyecto de portafolio, no un sistema comercial conectado a servidores.

## ¿Qué se puede probar?

- Dashboard con próximas citas, citas del día, pendientes, completadas y cantidad de clientes.
- Crear, editar, completar, cancelar y eliminar citas con fecha, hora, cliente, servicio y nota.
- Crear y editar fichas de clientes; directorio con búsqueda.
- Crear y editar servicios, precios y duración.
- Reportes actualizados a partir de las citas guardadas, y exportación CSV.
- Búsqueda y filtros por fecha/estado; tarjetas adaptables a móvil.
- Datos de demostración de ejemplo y botón para restablecerlos.
- Persistencia de pruebas en `localStorage` de cada navegador.

## Abrir sin instalar nada

Abre `index.html` con Chrome, Edge o Firefox. `styles.css` y `app.js` deben permanecer junto a `index.html`.

## Publicar en GitHub Pages

1. Crea un repositorio público independiente, por ejemplo `sistemas-jk-agenda-facil-pro-demo`.
2. Sube `index.html`, `styles.css`, `app.js` y `README.md` a la raíz del repositorio.
3. En `Settings → Pages`, selecciona `Deploy from a branch`, rama `main`, carpeta `/ (root)` y guarda.
4. Espera a que GitHub confirme que el sitio está publicado; comparte su enlace.

## Limitaciones importantes

- No tiene backend, inicio de sesión, sincronización entre dispositivos, notificaciones reales, integración con calendarios externos ni copias de seguridad remotas.
- Los datos viven únicamente en el navegador que los creó, pueden perderse si se limpia el almacenamiento, y **no deben utilizarse para clientes reales ni información sensible**.
- Los reportes muestran importes de servicios de citas completadas a modo ilustrativo, **no pagos reales ni facturación**.
- La versión comercial requeriría backend, autenticación, autorización de usuarios, auditoría, protección de datos personales, validaciones de citas y copias de seguridad.
- Las fuentes web de Google son opcionales; la interfaz tiene tipografías alternativas.

**Sistemas JK** · Proyecto de demostración para portafolio.
