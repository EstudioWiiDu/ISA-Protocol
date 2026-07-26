# Lanzamiento T1  
## Ejecución del dataset ISA  
### Por Estudio_WiiDu

---

# Introducción

El Lanzamiento T1 es la fase en la que se ejecutan los 21 prompts del Dataset ISA en los tres motores IA seleccionados.  
Esta fase genera los datos crudos del baseline, sin interpretaciones ni correcciones.

El objetivo es obtener una visión real de cómo la IA percibe la marca en su estado inicial.

---

# Motores utilizados

Los prompts deben ejecutarse en los siguientes motores IA:

- ChatGPT  
- Gemini  
- Perplexity  

Cada motor valida una parte distinta del Protocolo ISA:

- Perplexity → Interpret / AEO (detección temprana)  
- ChatGPT → Interpret / AEO (citación y reutilización)  
- Gemini → Search / Attribute (entidad y URL correcta)

---

# Dataset ISA

El dataset está compuesto por:

- 7 prompts de Marca  
- 7 prompts de Servicio  
- 7 prompts de Subservicio/Formación  

Total por ciclo:

21 prompts × 3 motores = **63 tests T1**

El dataset es fijo y no debe modificarse entre ciclos.

---

# Reglas de ejecución

## 1. No modificar los prompts
Los 21 prompts deben ejecutarse exactamente como están definidos.

## 2. No repetir prompts
Cada prompt se lanza una sola vez por motor.

## 3. No corregir respuestas
Las respuestas deben registrarse tal cual aparecen.

## 4. No intervenir en la IA
No se debe guiar, corregir o influir en la respuesta del motor.

## 5. Registrar todo
Cada test debe guardarse con su respuesta completa.

---

# Objetivo del Lanzamiento T1

El objetivo es obtener:

- respuestas crudas  
- señales reales  
- detección inicial  
- citación inicial  
- atribución inicial  
- shortlist inicial  
- SoM inicial  

Estos datos serán la base para comparar T2 y T3.

---

# Resultado esperado

En T1 es normal que:

- no haya citación  
- no haya URL atribuida  
- no haya shortlist  
- SoM sea bajo (0–5%)  
- Gemini no reconozca la entidad  
- ChatGPT no reutilice definiciones  
- Perplexity solo detecte parcialmente la marca  

Esto es baseline.  
Esto es T1.

---
