# Scripts comerciales y templates de outreach

## Pitch de 20 segundos

> Hola, [nombre]. Vi que [empresa] ofrece [soporte TI/DevOps/ciberseguridad]. Tenemos una API REST que devuelve información de puertos de red comunes —servicio, protocolo, riesgo orientativo y descripción— para integrarla en paneles, reportes y flujos internos. ¿Te enseño una demo de 10 minutos?

## Mensaje de LinkedIn

Hola, [nombre]. Vi que trabajas en [empresa/área]. Estamos validando una API sencilla para consultar información de puertos de red y mostrarla dentro de herramientas de soporte y seguridad. No es un escáner: es una capa de consulta integrable por REST. ¿Te interesaría probarla con un caso real?

## Primer email

**Asunto:** Consulta de puertos de red dentro de tu herramienta

Hola, [nombre]:

[Empresa] trabaja con [soporte/infraestructura/ciberseguridad]. Port Lookup API permite consultar por REST datos de puertos comunes como servicio, protocolo, nivel de riesgo orientativo y descripción.

Puede servir para paneles internos, reportes, documentación técnica y laboratorios. La integración de ejemplo es:

`GET /api/v1/port/{port_number}`

¿Tienes algún flujo donde hoy mantengan esta información manualmente? Si te parece útil, te muestro una demo breve y te doy acceso de prueba.

Saludos,
[Tu nombre]
[Empresa]
[URL real]

## Seguimiento 1 (3 días después)

Hola, [nombre]. Solo retomo mi mensaje. La propuesta es pequeña: consultar datos de puertos desde tu aplicación sin mantener una tabla local. Si no es una prioridad, dime y no vuelvo a contactarte.

## Seguimiento 2 (7 días después)

Hola, [nombre]. Cierro el hilo por ahora. Si en el futuro necesitas integrar información de puertos en un dashboard, reporte o herramienta de soporte, aquí está la demo: [URL].

## Guion de demo (10 minutos)

**Minutos 0-1:** Presentación
- "Soy [nombre], trabajo en Port Lookup API."
- "¿Tienes 10 minutos para ver cómo funciona?"

**Minutos 1-3:** Problema
- "¿Dónde guardan hoy información de puertos de red?"
- "¿Cuánto tiempo les toma mantenerla actualizada?"
- "¿Es algo que repeten en diferentes proyectos o clientes?"

**Minutos 3-7:** Solución
- Mostrar `/docs` de la API.
- Ejecutar ejemplo: `GET /api/v1/port/22` → devuelve SSH con riesgo Bajo.
- Ejecutar ejemplo: `GET /api/v1/port/3389` → devuelve RDP con riesgo Alto.
- Explicar respuesta JSON.
- "Lo integran en 10 minutos con cualquier lenguaje."

**Minutos 7-9:** Validación
- "¿Esto tiene sentido para ustedes?"
- "¿Qué volumen de consultas esperarían?"
- "¿Prefieren alojar la API o tener acceso privado?"

**Minuto 9-10:** Cierre
- "Te mando un acceso de prueba por 14 días. ¿Cuál es tu correo?"
- "Usalo en tu herramienta favorita y me llamas si algo no funciona."

## Respuestas a objeciones

**"Podemos guardar la tabla nosotros."**
> Correcto. El valor depende de si prefieren una consulta centralizada, una integración rápida y mantenimiento externo. Podemos comparar el costo del piloto.

**"¿También escanea equipos?"**
> No. La versión actual consulta información conocida de puertos; no escanea hosts ni confirma exposición.

**"¿Los datos son siempre correctos?"**
> Son datos de referencia. Documentamos su alcance y proceso de actualización; no debe usarse como sustituto de una auditoría.

**"¿Puedo alojarlo yo?"**
> Sí, podemos cotizar una licencia self-hosted, instalación y soporte.

**"¿Qué pasa si me cierran la cuenta o cambian los precios?"**
> Es justo. Si compras el código fuente, tienes independencia total. Si usas la API alojada, respetamos seis meses de preaviso para cualquier cambio importante.

**"¿Necesito cambiar mucho en mi sistema?"**
> No. Es un endpoint REST. Si tu stack es Python, Node, Go, .NET o Java, integras en 15 minutos.

## Regla de contacto responsable

- Personalizar cada contacto. No enviar templados sin nombre.
- Usar canales permitidos: LinkedIn, email público, web de contacto.
- Respetar bajas inmediatas. Si dicen "no contactarme más", responder "OK" y no volver.
- No enviar campañas masivas sin consentimiento explícito.
- Mantener una lista de exclusión.
- No usar datos de terceros sin verificar legalidad.
