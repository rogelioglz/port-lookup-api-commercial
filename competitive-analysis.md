# Análisis competitivo inicial

## Posicionamiento correcto

Port Lookup API, según el código actual, es una API de referencia para **puertos de red**. Su ventaja inicial no es competir con plataformas de inteligencia marítima, tracking de contenedores o escaneo de seguridad, sino ofrecer una integración pequeña y fácil para consultas de servicios y protocolos.

## Alternativas del cliente

| Alternativa | Fortalezas | Cómo diferenciarse |
|---|---|---|
| Tabla local o documentación interna | Gratis y control total | Endpoint listo, respuesta JSON y mantenimiento documentado |
| Bibliotecas o archivos públicos | Flexibles | API alojada y contrato de respuesta estable |
| Herramientas de escaneo | Detectan exposición real | Dejar claro que esta API no escanea; complementar, no sustituir |
| APIs de marketplace | Distribución y variedad | Soporte directo, despliegue privado y enfoque sencillo |
| Plataformas marítimas como SeaRates | Datos de puertos marítimos y tracking | No competir en ese segmento; diferenciarse como network-port lookup |

## Competidores de referencia marítimos

SeaRates ofrece APIs relacionadas con tracking y puertos marítimos; esas soluciones no son equivalentes al producto actual. Si se decide entrar al segmento marítimo, habrá que crear otra propuesta, datos y términos de uso.

## Comparativa de mensajes

### Mensaje débil
“API completa de seguridad de puertos con datos en tiempo real.”

### Mensaje verificable
“Consulta REST de puertos de red comunes con servicio, protocolo, riesgo orientativo y descripción.”

## Funciones que aumentarían el valor

1. API keys y cuotas por cliente.
2. Endpoint de búsqueda por servicio o protocolo.
3. Versionado y OpenAPI documentado.
4. Dataset ampliado con fuente y fecha de actualización.
5. Respuestas en inglés y español.
6. Exportación CSV/JSON.
7. Historial de cambios del dataset.
8. Métricas, logs y límites de uso.
9. Despliegue privado y guía de seguridad.
10. Tests automatizados y monitorización.

## Validación antes de subir precios

Entrevistar a cinco clientes de cada segmento y preguntar:

- ¿Qué herramienta usan hoy?
- ¿Qué costo tiene mantener sus datos?
- ¿Necesitan API alojada o self-hosted?
- ¿Qué volumen de consultas esperan?
- ¿Qué requisito de seguridad o cumplimiento es obligatorio?
- ¿Pagarían por un piloto? ¿Cuánto?

No afirmar cobertura, SLA, tiempo real o precisión hasta medirlo y documentarlo.
