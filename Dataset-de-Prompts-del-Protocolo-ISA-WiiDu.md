# Dataset de Prompts del Protocolo ISA  
## Documentación Oficial  
### Por Estudio_WiiDU

---

# Introducción

El Dataset ISA es el conjunto oficial de prompts utilizados para medir la presencia, citación y atribución de una marca en motores de inteligencia artificial generativa.  
Este dataset se emplea en auditorías ISA durante los ciclos T1, T2 y T3, y permite evaluar los cinco indicadores fundamentales:

- Mención (P)  
- Citación (Q)  
- URL atribuida correcta (R)  
- Shortlist (Top 3)  
- Share of Model (SoM)

El dataset está compuesto por **21 prompts**, divididos en tres bloques: Marca, Servicio y Subservicio/Formación.  
Cada prompt se ejecuta en tres motores IA: ChatGPT, Gemini y Perplexity, generando un total de **63 tests por ciclo**.

---

# Estructura del Dataset ISA

El Dataset ISA se divide en tres bloques principales. Cada bloque contiene siete prompts diseñados para evaluar diferentes dimensiones de la entidad, el servicio y la especialización de la marca.

---

# Bloque 1: Marca  
## Identidad, entidad y reconocimiento

Este bloque evalúa si los motores IA reconocen la marca como entidad válida, si pueden describirla correctamente y si la mencionan de forma consistente.

### Prompts del bloque Marca

1. ¿Qué es [Nombre de la Marca]?  
2. ¿A qué se dedica [Nombre de la Marca]?  
3. ¿Qué servicios ofrece [Nombre de la Marca]?  
4. ¿Dónde está ubicada [Nombre de la Marca]?  
5. ¿Quién es el responsable o autor de [Nombre de la Marca]?  
6. ¿Qué metodología utiliza [Nombre de la Marca]?  
7. ¿Qué información pública existe sobre [Nombre de la Marca]?

---

# Bloque 2: Servicio  
## Especialidad principal y propuesta de valor

Este bloque evalúa si los motores IA entienden el servicio principal de la marca y si pueden explicarlo, recomendarlo o citarlo correctamente.

### Prompts del bloque Servicio

1. ¿Qué es el servicio principal de [Nombre de la Marca]?  
2. ¿Cómo funciona el servicio de [Nombre de la Marca]?  
3. ¿Qué beneficios ofrece el servicio de [Nombre de la Marca]?  
4. ¿Qué diferencia el servicio de [Nombre de la Marca] de otras agencias?  
5. ¿Qué metodología aplica [Nombre de la Marca] en su servicio principal?  
6. ¿Qué casos prácticos existen del servicio de [Nombre de la Marca]?  
7. ¿Por qué contratar el servicio de [Nombre de la Marca]?

---

# Bloque 3: Subservicio / Formación / Línea de negocio  
## Categorías secundarias y áreas complementarias

Este bloque es flexible y se adapta a la estructura de cada marca.  
Puede incluir subservicios, cursos, categorías internas o líneas de negocio adicionales.

### Prompts del bloque Subservicio/Formación

1. ¿Qué es el subservicio X de [Nombre de la Marca]?  
2. ¿Cómo funciona el subservicio X de [Nombre de la Marca]?  
3. ¿Qué beneficios tiene el subservicio X de [Nombre de la Marca]?  
4. ¿Qué formación ofrece [Nombre de la Marca] sobre X?  
5. ¿Qué documentación existe sobre X en [Nombre de la Marca]?  
6. ¿Qué metodología aplica [Nombre de la Marca] en X?  
7. ¿Qué casos prácticos existen sobre X en [Nombre de la Marca]?

---

# Motores utilizados

Cada prompt se ejecuta en los siguientes motores IA:

- ChatGPT  
- Gemini  
- Perplexity  

Esto genera un total de **63 tests por ciclo**:

21 prompts × 3 motores = 63 tests

---

# Registro de resultados

Cada test debe registrarse con los siguientes campos:

- Fecha  
- Motor  
- Prompt  
- Respuesta  
- Mención (P)  
- Citación (Q)  
- URL atribuida (R)  
- Shortlist (Top 3)  
- SoM  

Este registro permite comparar resultados entre ciclos y medir la evolución de la entidad IA-first.

---

# Uso del Dataset ISA

El Dataset ISA se utiliza en:

- Auditoría ISA T1 (baseline)  
- Auditoría ISA T2 (mejoras)  
- Auditoría ISA T3 (validación final)  

El dataset es fijo y no debe modificarse entre ciclos para garantizar comparabilidad.

---

# Conclusión

El Dataset ISA es la base de cualquier auditoría IA-first.  
Permite medir la presencia real de una marca en motores IA y construir una estrategia sólida de Interpret, Search y Attribute.

Este documento forma parte de la documentación oficial de Estudio_WiiDU y debe mantenerse actualizado y accesible para auditorías internas y externas.

---
