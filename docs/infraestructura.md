# Infraestructura técnica

## Arquitectura propuesta
- Cliente web: HTML, CSS y JavaScript.
- Backend: Node.js.
- Base de datos: PostgreSQL.
- Comunicación en vivo: WebSockets.
- Hosting: proveedor administrado a seleccionar tras comparar costos, límites, ubicación y privacidad.

## Autoridad del servidor
El servidor es la fuente de verdad para producción, salarios, inventarios, mercado, elecciones, permisos, noticias e historial. El navegador envía acciones y muestra resultados; no decide unilateralmente el estado del mundo.

## Mundo persistente
Un único mundo compartido y activo continuamente. Los procesos programados deben ser idempotentes para evitar duplicar producción o pagos tras reinicios.

## Separación conceptual de datos
Cuentas/autenticación; perfiles públicos; datos nacionales; empresas/mercado; elecciones/instituciones; prensa e historial.

## Escalabilidad
Comenzar con despliegue pequeño y base de datos administrada. Medir y optimizar antes de separar servicios o agregar instancias. Preparar copias de seguridad, monitoreo, registros y recuperación.

## Seguridad
Hash seguro de contraseñas mediante biblioteca especializada; permisos validados en servidor; protección contra manipulación de solicitudes; límites de frecuencia; backups y retención; secretos y datos privados nunca expuestos al cliente.

## Decisión pendiente
No se eligió hosting. Se decidirá con un prototipo y estimaciones de usuarios concurrentes, carga, tráfico y presupuesto.
