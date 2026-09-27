# Plan para localizar clientes y vender Port Lookup API

## Corrección importante
Esta API consulta **puertos de red** (por ejemplo, 22/SSH, 443/HTTPS y 3389/RDP), no puertos marítimos. La propuesta comercial debe dirigirse a equipos de desarrollo, soporte, DevOps, ciberseguridad, MSP y educación técnica.

## Cliente ideal

1. **MSP y empresas de soporte TI**: necesitan explicar servicios y riesgos a sus clientes.
2. **Consultoras de ciberseguridad**: pueden incorporar la consulta en reportes y herramientas internas.
3. **Equipos DevOps/SRE**: validan configuraciones durante despliegues y troubleshooting.
4. **Software houses y SaaS**: integran la consulta en paneles, guías o productos de infraestructura.
5. **Academias y bootcamps**: usan información de puertos en laboratorios y material didáctico.
6. **Administradores de redes**: requieren una consulta rápida dentro de sus flujos internos.

## Propuesta de valor honesta

> Una API REST sencilla para consultar el servicio, protocolo, nivel de riesgo y descripción de puertos de red comunes. Ideal para integrarla en herramientas internas, paneles de soporte, laboratorios y flujos de diagnóstico.

No prometer detección en tiempo real, escaneo de hosts, base de datos completa ni disponibilidad de 99.9% hasta que esas funciones estén implementadas y medidas.

## Oferta inicial recomendada

- **Developer**: gratis o prueba de 14 días; 100 consultas/día.
- **Team**: $19/mes; límites mayores y soporte por email.
- **Business**: $79/mes; límites personalizados, soporte prioritario y despliegue privado.
- **Código fuente**: cotización; licencia para una empresa, instalación y soporte opcional.

Estos precios son hipótesis de lanzamiento. Validarlos con 10 entrevistas antes de fijarlos definitivamente.

## Embudo de ventas de 30 días

### Días 1–3: preparación
- Publicar documentación real de `/docs`.
- Añadir API key, rate limiting, logs y política de privacidad antes de cobrar.
- Crear una demo con ejemplos de `/api/v1/port/{port_number}`.
- Sustituir los placeholders de email, dominio y URL de API.

### Días 4–10: prospectos
- Crear una lista de 50 empresas usando sitios públicos y búsquedas de LinkedIn.
- Registrar empresa, web, rol, URL pública, problema probable y estado.
- Priorizar MSP, consultoras de seguridad y software houses.

### Días 11–20: contacto
- Enviar 10 mensajes personalizados por día.
- No comprar ni enviar mensajes masivos a listas sin consentimiento.
- Ofrecer una demo de 10 minutos y acceso de prueba.

### Días 21–30: validación y cierre
- Hacer demos con datos reales y documentar objeciones.
- Preguntar qué endpoint, límite y modalidad de despliegue necesitan.
- Cerrar primero un piloto pagado, no una licencia Enterprise sin validar el producto.

## Métricas

- 50 cuentas investigadas.
- 30 contactos relevantes.
- 10 respuestas.
- 5 demos.
- 2 pilotos.
- 1 cliente pagado.

## Dónde buscar

- LinkedIn: `MSP`, `network support`, `DevOps`, `SOC`, `cybersecurity consultant`.
- Google Maps: `soporte TI`, `consultoría ciberseguridad`, `servicios administrados` + ciudad.
- Directorios empresariales y cámaras de comercio.
- Comunidades técnicas, respetando sus reglas.
- GitHub y Product Hunt para alianzas, no para spam.

## Checklist legal y operativo

- Confirmar que los datos de la base pueden redistribuirse comercialmente.
- Publicar términos de servicio, privacidad y política de uso aceptable.
- No presentar `risk` como una evaluación de seguridad universal.
- Explicar que la API describe puertos conocidos; no sustituye una auditoría.
- Configurar pagos, facturas, soporte y procedimiento de reembolso.
