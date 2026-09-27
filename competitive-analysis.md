# Análisis competitivo - Port Lookup API (Network Ports)

## Posicionamiento correcto

Port Lookup API, según el código actual, es una API de referencia para **puertos de red**. Su ventaja inicial no es competir con plataformas de inteligencia marítima, tracking de contenedores o escaneo de seguridad, sino ofrecer una integración pequeña y fácil para consultas de servicios y protocolos.

## Alternativas del cliente

| Alternativa | Fortalezas | Debilidades | Cómo diferenciarse |
|---|---|---|---|
| Tabla local o documentación interna | Gratis y control total | Mantenimiento manual, dispersión | Endpoint listo, respuesta JSON y mantenimiento documentado |
| Bibliotecas o archivos públicos | Flexibles | Desactualización, no integrado | API alojada y contrato de respuesta estable |
| Herramientas de escaneo (Nmap, etc.) | Detectan exposición real | Complejas, requieren infra | Dejar claro que esta API no escanea; complementar |
| APIs de marketplace | Distribución y variedad | Costo alto, SLA variable | Soporte directo, despliegue privado y sencillez |
| Documentación de IANA (wiki.iana.org) | Fuente oficial | No es API, requiere parsing | Formato estructurado, actualización garantizada |

## No competir con APIs marítimas

SeaRates, Datamar y plataformas similares ofrecen APIs para tracking de contenedores, eficiencia portuaria e inteligencia de shipping. Eso es un mercado diferente y requiere datos, infraestructura y licencias distintas.

**Tu producto actual:** consulta de puertos de red.  
**Tu mercado actual:** soporte TI, DevOps, consultoras, MSP, académica.  
**Tu competencia directa:** tablas internas, documentación, herramientas caseras.

## Comparativa de mensajes

### Mensaje débil ❌
"API completa de seguridad de puertos con datos en tiempo real y cobertura global."

### Mensaje verificable ✅
"Consulta REST de puertos de red comunes (SSH, HTTP, RDP, MySQL, etc.) con servicio, protocolo, riesgo orientativo y descripción."

## Benchmarking de competidores indirectos

| Solución | Precio | Ventaja | Debilidad |
|---|---|---|---|
| Tabla Excel/interna | Gratis | Control total | Mantenimiento, no integrado |
| Nmap/nessus | $0–$5k/año | Escaneo real | Pesado, requiere infra |
| IANA Registry público | Gratis | Oficial | No es API, difícil de parsear |
| Plataformas marítimas | $500–$10k/mes | Datos especializados | Para otro mercado |
| **Port Lookup API** | **$19–$79/mes** | **Integración rápida, soporte** | **Datos de referencia, no escanea** |

## Funciones que aumentarían competitividad

1. **Inmediato (primer mes)**
   - API keys y cuotas por cliente.
   - Rate limiting y logs.
   - Documentación OpenAPI/Swagger.
   - Política de privacidad y TOS.

2. **Corto plazo (1–3 meses)**
   - Búsqueda por servicio o protocolo.
   - Exportación CSV/JSON.
   - Versión self-hosted.
   - Respuestas en inglés y español.
   - Dashboard de uso.

3. **Mediano plazo (3–6 meses)**
   - Dataset ampliado con fuente y fecha.
   - Historial de cambios (changelog).
   - Monitorización y uptime SLA.
   - Guía de integración por lenguaje.
   - Tests automatizados.

## Validación antes de fijar precios

Entrevistar a **mínimo 5 clientes** de cada segmento:

1. MSP
2. Consultora de ciberseguridad
3. Equipo DevOps
4. Academia/bootcamp
5. Software house

**Preguntas clave:**

- ¿Qué herramienta usan hoy para consultar puertos?
- ¿Qué costo tiene mantenerla?
- ¿Necesitan API alojada o self-hosted?
- ¿Qué volumen de consultas esperan?
- ¿Qué requisito de seguridad es obligatorio?
- ¿Pagarían por un piloto? ¿Cuánto?

## Recomendaciones

✅ **SÍ hacer:**
- Posicionar como "integración sencilla de referencia."
- Enfocarse en MSP, DevOps y consultoras.
- Validar con clientes reales antes de subir precios.
- Ser honesto sobre lo que hace y lo que no.
- Ofrecer piloto de 14 días con acceso real.

❌ **NO hacer:**
- Afirmar cobertura global sin datos verificados.
- Competir con plataformas marítimas.
- Prometeer SLA de 99.9% sin infraestructura.
- Enviar spam o campañas masivas.
- Posicionar como "herramienta de hacking."
