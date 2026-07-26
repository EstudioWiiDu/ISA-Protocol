# Interpretación T1  
## Análisis del ciclo baseline  
### Por Estudio_WiiDu

---

# Introducción

La Interpretación T1 es la fase en la que se analizan los datos registrados durante el ciclo baseline.  
Aquí se evalúa cómo los motores IA perciben la marca, qué señales detectan y qué indicadores presentan debilidad o ausencia.

El objetivo es transformar los datos en conclusiones técnicas.

---

# Análisis por indicadores

## Mención (P)
Evalúa si los motores IA reconocen la marca como entidad.  
En T1 es habitual que:

- Perplexity mencione parcialmente  
- ChatGPT mencione ocasionalmente  
- Gemini no mencione la marca  

## Citación (Q)
Evalúa si los motores IA muestran fuentes o enlaces.  
En T1 es normal que no exista citación.

## URL atribuida correcta (R)
Evalúa si la IA cita la URL canónica correcta.  
En T1 es habitual que:

- no exista URL atribuida  
- la IA invente URLs  
- la IA cite dominios incorrectos  

## Shortlist (Top 3)
Evalúa si la marca aparece entre las primeras recomendaciones.  
En T1 es normal que no aparezca.

## Share of Model (SoM)
Porcentaje de prompts donde la marca aparece mencionada.  
En T1 suele estar entre 0% y 5%.

---

# Análisis por motor IA

## Perplexity
- Detecta entidades nuevas rápidamente  
- Suele mencionar antes que otros motores  
- No suele atribuir URL  
- No suele citar  
- Es útil para medir Interpret y AEO

## ChatGPT
- Reutiliza definiciones si están bien escritas  
- Puede mencionar la marca si la documentación es clara  
- No suele atribuir URL en T1  
- Es útil para medir claridad y citación

## Gemini
- Depende de Google Search  
- No suele reconocer entidades nuevas  
- No atribuye URL en T1  
- Es útil para medir Search y Attribute

---

# Patrones habituales en T1

- Falta de mención en Gemini  
- Falta de citación en todos los motores  
- Falta de URL atribuida correcta  
- SoM muy bajo  
- Respuestas genéricas  
- Confusión sobre la especialidad de la marca  
- Ausencia de señales de entidad  
- Invento de URLs  
- Falta de shortlist

Estos patrones son normales y forman parte del baseline.

---

# Objetivo de la Interpretación T1

El objetivo es identificar:

- qué señales faltan  
- qué documentación debe ampliarse  
- qué URLs deben crearse  
- qué arquitectura debe corregirse  
- qué señales externas deben activarse  
- qué motores presentan mayor debilidad  
- qué indicadores deben mejorar en T2  

La Interpretación T1 es la base para construir la hoja de mejoras T1 → T2.

---
