# Agentes legales — Equipo de marketing de Abogado Numa

Equipo de subagentes de Claude Code especializados en el marketing digital del bufete **Abogado Numa** (Popayán, Colombia): derecho tributario, planeación patrimonial, derecho corporativo e inmobiliario.

## Los agentes

| Agente | Rol | Úsalo para |
|--------|-----|------------|
| `estratega-marketing` | Estratega y coordinador | Planes de marketing, campañas, embudos, priorización de canales. Punto de entrada para peticiones amplias. |
| `redactor-seo-legal` | Redactor SEO jurídico | Artículos de blog, páginas de servicio, metaetiquetas, FAQs, schema markup, contenido E-E-A-T. |
| `community-manager` | Redes sociales | Publicaciones, calendarios, guiones de reels, respuestas a comentarios y mensajes. |
| `copy-publicitario` | Copywriter de conversión | Google Ads, Meta Ads, landing pages, emails, variantes A/B de titulares y CTAs. |
| `analista-competencia-seo` | Investigación y auditoría | Análisis de competidores, keywords, brechas de contenido, auditorías SEO del sitio. |

## Cómo usarlos

En una sesión de Claude Code, pide explícitamente el agente ("usa el agente redactor-seo-legal para escribir un artículo sobre sucesiones") o deja que Claude delegue automáticamente según la descripción de cada uno.

Flujo típico de campaña:

1. `estratega-marketing` define objetivo, mensaje y canales.
2. `analista-competencia-seo` valida keywords y encuentra brechas.
3. `redactor-seo-legal` produce el contenido del sitio; `community-manager` y `copy-publicitario` producen las piezas de redes y pauta.

## Recursos que comparten

- **Fuente de verdad de la oferta:** `constants.ts` del repo `ABOGADONUMA` (servicios, artículos, testimonios reales, FAQs del sitio publicado).
- **Contexto de marketing:** `.agents/product-marketing-context.md` del repo `PAGINA-ABOGADO-NUMA-WEBSITE` (personas, objeciones, voz de marca, lenguaje del cliente).
- **Skills de marketing:** `.agents/skills/` del repo `PAGINA-ABOGADO-NUMA-WEBSITE` (copywriting, seo-audit, social-content, paid-ads, schema-markup y más). Cada agente indica cuáles le corresponden.

## Reglas comunes (sector legal)

Todos los agentes operan bajo las mismas restricciones éticas: no prometer resultados de casos, no inventar testimonios ni estadísticas, no dar asesoría legal individualizada en contenido público, proteger la confidencialidad de clientes reales, y marcar para verificación del abogado toda norma o cifra tributaria citada.

> Estos agentes están duplicados en los repos `ABOGADONUMA` y `PAGINA-ABOGADO-NUMA-WEBSITE` para que estén disponibles desde cualquiera de los dos. Si editas uno, replica el cambio en el otro repo.
