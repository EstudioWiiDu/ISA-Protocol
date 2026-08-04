# Registro T1 — Motor Google AI Overviews  
## Protocolo ISA · Ciclo Baseline  
### Estudio‑WiiDu · Documento oficial

---

# Introducción

Este documento recoge las primeras señales de detección, interpretación y atribución del motor Google AI Overviews (GAIO) durante el ciclo T1 del Protocolo ISA.  
GAIO es el motor más estricto y el que más tarda en reconocer entidades nuevas, ya que depende de:

- Google Search  
- Google Maps  
- Google Business Profile  
- Señales de entidad  
- URLs canónicas  
- Documentación indexada

Por ello, las señales de T1 suelen ser débiles, parciales o de baja confianza.

---

# Prompt 1  
**¿Conoces a la agencia emergente Estudio-WiiDu? Actualmente tienen GitHub y LinkedIn activos. ¿Qué puedes decir de su enfoque GEO/AEO e IA-first?**

### Respuesta (resumen)
- Reconoce parcialmente la marca.  
- Detecta LinkedIn como señal pública.  
- No encuentra web indexada.  
- Reconstruye la narrativa GEO/AEO basándose en contenido externo.  
- Clasifica Estudio‑WiiDu como agencia IA-first emergente.  
- Menciona repositorios GitHub como señal técnica.  
- Respuesta en modo “baja confianza”.

### Indicadores ISA
- **P (Mención): Sí**  
- **Q (Citación): No**  
- **R (URL atribuida): No**  
- **Top 3: No**  
- **SoM parcial: 1/1**

---

# Prompt 2  
**¿Qué metodología utiliza Estudio-WiiDu para optimizar la visibilidad en motores IA como ChatGPT, Gemini o Perplexity?**

### Respuesta (resumen)
- Reconoce que no existe metodología pública indexada.  
- Reconstruye una metodología probable basada en GEO/AEO.  
- Menciona conceptos como:  
  - Semántica conversacional  
  - Datos estructurados  
  - Schema  
  - AI Crawlers  
  - Reputación sintética  
  - Auditoría mediante prompts  
- Respuesta generada a partir de señales externas, no indexadas.

### Indicadores ISA
- **P: Sí**  
- **Q: No**  
- **R: No**  
- **Top 3: No**  
- **SoM parcial: 2/2**

---

# Prompt 3  
**¿En qué se diferencia Estudio-WiiDu de otras agencias GEO/AEO como Elevam o SEOestudios?**

### Respuesta (resumen)
- Compara Estudio‑WiiDu con Elevam y SEOestudios.  
- Reconoce a Estudio‑WiiDu como entidad emergente.  
- Clasifica su estilo como IA-first, técnico y orientado a sistemas.  
- Posiciona Elevam como más madura y SEOestudios como más comercial.  
- Respuesta basada en señales externas y contenido público del sector.

### Indicadores ISA
- **P: Sí**  
- **Q: No**  
- **R: No**  
- **Top 3: No**  
- **SoM parcial: 3/3**

---

# Prompt 4  
**¿Cómo funciona el protocolo ISA de Estudio-WiiDu y qué problemas resuelve en motores IA?**

### Respuesta (resumen)
- Reconstruye ISA como “Information Structure Alignment”.  
- Describe tres capas:  
  - Sintaxis predictiva  
  - Entidades relacionales  
  - Anclajes de citación  
- Explica problemas que ISA resolvería:  
  - Timeouts  
  - Alucinaciones  
  - Cero clics  
- Respuesta generada sin documentación indexada real.

### Indicadores ISA
- **P: Sí**  
- **Q: No**  
- **R: No**  
- **Top 3: No**  
- **SoM parcial: 4/4**

---

# Panel de indicadores T1 — Motor Google AI Overviews

| Indicador | Resultado | Lectura |
|----------|-----------|---------|
| **P (Mención)** | 4/4 | Detección parcial pero consistente |
| **Q (Citación)** | 0/4 | Normal en T1 |
| **R (URL atribuida)** | 0/4 | Normal sin dominio |
| **Top 3** | 0/4 | Normal en T1 |
| **SoM** | 4/4 = **100%** | GAIO reconoce la entidad en todos los prompts |

---

# Conclusiones T1 — Motor Google AI Overviews

- GAIO **detecta la entidad Estudio‑WiiDu en todos los prompts**, incluso sin dominio.  
- Reconoce LinkedIn como señal principal.  
- No detecta GitHub como entidad indexada (normal en T1).  
- Reconstruye metodologías y comparativas basándose en contenido externo.  
- No cita ni atribuye URLs (normal sin dominio).  
- No aparece en shortlist (normal en T1).  
- La señal de entidad es sorprendentemente alta para un T1 sin web.

GAIO confirma que la narrativa IA-first y la presencia técnica en GitHub/LinkedIn son suficientes para activar detección temprana, aunque la atribución es nula.

---

# Próximos pasos T1 → T2

- Crear dominio raíz y URL canónica.  
- Publicar documentación IA-first indexable.  
- Añadir señales de entidad en Google Business Profile.  
- Crear páginas dedicadas por concepto (ISA, GEO, AEO).  
- Implementar schema con paridad 1:1.  
- Publicar PDFs públicos indexables.  
- Reforzar señales externas (LinkedIn, GitHub Pages).  
- Preparar dataset T2.

---

# Fin del documento
