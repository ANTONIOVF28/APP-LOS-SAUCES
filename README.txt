LOS SAUCES — prototipo inicial para iPhone/iPad

INCLUYE
- Registro, edición y eliminación de eventos.
- Cliente, teléfono, tipo, fecha, horario, invitados y notas.
- Precio de renta, anticipo, pagos adicionales y saldo automático.
- Resumen de eventos e ingresos, filtros y calendario mensual.
- Exportación/importación de respaldo JSON.
- Interfaz adaptable a iPhone y opción PWA para añadir a pantalla de inicio.

LIMITACIONES IMPORTANTES DE ESTA VERSIÓN
- Los datos se guardan en el almacenamiento local del navegador. No se sincronizan entre dispositivos y podrían perderse si se borra el historial/datos del sitio.
- La conexión real con Google Calendar aún no está configurada.
- No usar todavía como única fuente de datos de un negocio en producción.

CÓMO ABRIR DESDE IPHONE/IPAD
1. Sube los archivos de esta carpeta a un servicio de hosting HTTPS (por ejemplo, un repositorio GitHub y un servicio de publicación estática).
2. Abre la URL HTTPS publicada en Safari.
3. Pulsa Compartir > Añadir a pantalla de inicio > Añadir.
4. Para probar el prototipo sin publicar, abre index.html en un entorno que permita servir archivos web; abrirlo directamente como archivo puede impedir algunas funciones PWA.

SIGUIENTE PASO PARA PRODUCCIÓN
Configurar autenticación y base de datos en la nube, reglas de acceso privadas para un solo usuario, y Google OAuth/Calendar API. Se necesitan cuentas del usuario y configuración de credenciales; nunca pegues contraseñas ni claves privadas en el chat.
