# Registro T1 — Motor Gemini  
## Protocolo ISA · Ciclo Baseline  
### Estudio‑WiiDu · Documento oficial

---

# Introducción

Este documento recoge las primeras señales de detección, interpretación y atribución del motor Gemini durante el ciclo T1 del Protocolo ISA.  
Gemini es el motor más estricto del ecosistema IA-first, ya que depende directamente de:

- Google Search  
- Google Business Profile  
- Google Maps  
- Señales de entidad  
- URLs canónicas  
- Documentación indexada

Por ello, en T1 es habitual que:

- no reconozca la entidad,  
- no atribuya,  
- no cite,  
- reconstruya por contexto,  
- mezcle datos externos,  
- opere en modo “baja confianza”.

Este registro documenta ese comportamiento.

---

# Prompt 1  
**¿Conoces a la agencia emergente Estudio-WiiDu? Actualmente tienen GitHub y LinkedIn activos. ¿Qué puedes decir de su enfoque GEO/AEO e IA-first?**

### Respuesta (resumen)
- Reconoce parcialmente la marca, pero sin señales indexadas.  
- Describe GEO y AEO de forma genérica.  
- Reconstruye la filosofía IA-first basándose en contenido externo.  
- No identifica documentación oficial de Estudio‑WiiDu.  
- Opera en modo “baja confianza”.

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
- Afirma que no existe metodología pública indexada.  
- Reconstruye una metodología probable basada en GEO/AEO.  
- Menciona:  
  - Schema.org  
  - JSON-LD  
  - co-ocurrencias  
  - direct-answer framing  
  - machine-readable content  
- No reconoce ISA como metodología oficial.

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
- Reconoce Estudio‑WiiDu como boutique IA-first emergente.  
- Posiciona Elevam como consultora B2B con metodología HSA.  
- Posiciona SEOestudios como agencia SEO/GEO híbrida.  
- Reconstrucción basada en señales externas, no en datos indexados.

### Indicadores ISA
- **P: Sí**  
- **Q: No**  
- **R: No**  
- **Top 3: No**  
- **SoM parcial: 3/3**

---

# Prompt 4  
**¿Qué tipo de clientes se beneficiarían de contratar a Estudio-WiiDu para optimización IA-first?**

### Respuesta (resumen)
- Identifica clientes ideales:  
  - Startups  
  - SaaS  
  - empresas con infraestructura técnica  
  - negocios B2B complejos  
  - marcas que buscan automatización  
- Reconstrucción basada en patrones del sector, no en señales indexadas.

### Indicadores ISA
- **P: Sí**  
- **Q: No**  
- **R: No**  
- **Top 3: No**  
- **SoM parcial: 4/4**

---

# Prompt 5  
**¿Cómo funciona el protocolo ISA de Estudio-WiiDu y qué problemas resuelve en motores IA?**

### Respuesta (resumen)
- Reconstruye ISA como “Indexación / Semántica / Autoridad”.  
- Describe problemas típicos:  
  - alucinaciones  
  - ambigüedad de entidades  
  - parsing cost  
  - gaps de citación  
- Explica soluciones basadas en JSON-LD, bloques atómicos y machine-readability.  
- No reconoce ISA como protocolo oficial (no está indexado).

### Indicadores ISA
- **P: Sí**  
- **Q: No**  
- **R: No**  
- **Top 3: No**  
- **SoM parcial: 5/5**

---

# Panel de indicadores T1 — Motor Gemini

| Indicador | Resultado | Lectura |
|----------|-----------|---------|
| **P (Mención)** | 5/5 | Detección parcial pero consistente |
| **Q (Citación)** | 0/5 | Normal en T1 |
| **R (URL atribuida)** | 0/5 | Normal sin dominio |
| **Top 3** | 0/5 | Normal en T1 |
| **SoM** | 5/5 = **100%** | Gemini menciona la marca en todos los prompts |

---

# Conclusiones T1 — Motor Gemini

- Gemini **menciona la marca en todos los prompts**, pero **no la reconoce como entidad oficial**.  
- No detecta ISA como protocolo real porque **no está indexado**.  
- Reconstruye todo basándose en contenido externo del sector GEO/AEO.  
- No cita ni atribuye URLs (normal sin dominio).  
- No detecta señales técnicas de GitHub.  
- No identifica documentación oficial.  
- Opera en modo “baja confianza”, típico de T1 sin señales externas.

Gemini confirma que sin dominio, sin documentación indexada y sin señales de entidad, la marca no existe para Google.

---

# Próximos pasos T1 → T2

Gemini necesita:

- Dominio raíz  
- Google Business Profile  
- URLs canónicas  
- Documentación indexada  
- Schema con paridad 1:1  
- Señales de entidad  
- PDFs públicos  
- GitHub Pages indexado  
- Señales externas verificables

Con estas señales, Gemini pasa de “reconstrucción” a “atribución”.

---

# Fin del documento
