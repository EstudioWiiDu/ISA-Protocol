# Registro T1  
## Panel de datos del ciclo baseline  
### Por Estudio_WiiDu

---

# Introducción

El Registro T1 es la fase en la que se documentan todos los resultados obtenidos durante la ejecución del dataset ISA.  
Aquí se guardan las respuestas crudas de los motores IA y se clasifican según los indicadores oficiales del Protocolo ISA.

El objetivo es construir un panel de datos completo, ordenado y replicable.

---

# Estructura del registro

Cada uno de los 42-63 tests del ciclo T1 deben registrarse con los siguientes campos:

## Datos del test
- Fecha  
- Motor (ChatGPT, Gemini, Perplexity)  
- Prompt ejecutado  
- Respuesta completa  

## Indicadores ISA
- Mención (P)  
- Citación (Q)  
- URL atribuida correcta (R)  
- Shortlist (Top 3)  
- Share of Model (SoM)  

---

# Indicadores ISA en detalle

## Mención (P)
Indica si el motor IA nombra la marca de forma explícita.

## Citación (Q)
Indica si el motor IA muestra fuentes o enlaces.

## URL atribuida correcta (R)
Indica si el motor IA cita la URL canónica correcta de la marca.

## Shortlist (Top 3)
Indica si la marca aparece entre las primeras recomendaciones del motor IA.

## Share of Model (SoM)
Porcentaje de prompts donde la marca aparece mencionada.

---

# Formato recomendado del registro

Cada test debe guardarse en formato tabla o JSON estructurado.  
Ejemplo en tabla:

| Fecha | Motor | Prompt | P | Q | R | Top 3 | SoM | Respuesta |
|-------|--------|--------|----|----|----|--------|--------|-----------|
| 2026-07-26 | ChatGPT | ¿Qué es Estudio_WiiDu? | Sí | No | No | No | 1/21 | (respuesta completa) |

---

# Reglas del registro T1

## 1. Registrar todo sin modificar
Las respuestas deben guardarse tal cual aparecen.

## 2. No corregir errores de la IA
Si la IA se equivoca, se registra el error.

## 3. No completar información faltante
El registro debe reflejar la realidad del motor IA.

## 4. No omitir respuestas
Incluso respuestas vacías o irrelevantes deben registrarse.

## 5. Mantener consistencia
El formato debe ser idéntico en todos los tests.

---

# Objetivo del Registro T1

El objetivo es construir un panel de datos que permita:

- comparar T1 con T2 y T3  
- detectar mejoras reales  
- identificar bloqueos  
- medir señales de entidad  
- evaluar citación y atribución  
- calcular SoM con precisión  

El Registro T1 es la base de toda la medición ISA.

---
