# 🍷 WineAdvisor Agent: Integración de ML, RAG y Agentes Autónomos
### El futuro del análisis enológico: Inteligencia Artificial Agéntica y Gobernada

Este proyecto representa la convergencia entre el Machine Learning tradicional y la IA Generativa de vanguardia. Se trata de un **Agente Autónomo** capaz de razonar sobre la calidad del vino, utilizando un modelo predictivo propio y una base de conocimientos técnica vía RAG para justificar sus decisiones y recomendar mejoras productivas.

---

## 🛡️ Visión de Gobierno de Datos y Ética en la IA (AI Governance)
En un sistema agéntico, la gobernanza es más crítica que nunca. Este proyecto implementa controles de **Data & AI Governance** avanzados:

1. **Gobernanza de la Salida (Structured Output):** El agente no solo genera texto, sino que devuelve una **salida estructurada (JSON)** validada. Esto asegura que la información sea procesable por otros sistemas, manteniendo la integridad semántica de la respuesta.
2. **Validación Documental (RAG Integrity):** Mediante la técnica de *Retrieval-Augmented Generation*, el agente mitiga las alucinaciones del LLM, asegurando que sus justificaciones se basen exclusivamente en literatura técnica validada (ej. Cortez et al.).
3. **Transparencia y Explicabilidad:** El sistema rompe la "caja negra" del ML al cruzar la predicción numérica con una explicación técnica detallada, permitiendo que el experto humano audite el razonamiento de la IA.
4. **Estado de Validación:** Cada respuesta incluye un campo de metadatos de calidad (`estado_validacion: VALIDADO`), cumpliendo con protocolos de confianza para entornos corporativos.

---

## 🎯 Capacidades del Agente "WineAdvisor"
- **Predicción Inteligente:** Ejecuta un modelo de ML (Random Forest/XGBoost) para estimar la calidad del vino a partir de `vinos.csv`.
- **Motor de RAG:** Consulta una base técnica vectorizada para explicar el impacto químico (cloruros, acidez, etc.) en la calidad.
- **Tools & Tools Calling:** Capacidad para invocar herramientas externas de análisis y cálculo.
- **Recomendación Estratégica:** No solo diagnostica, sino que propone ajustes fisicoquímicos para elevar la puntuación del producto.

---

## 🛠️ Stack Tecnológico
- **Orquestación de Agentes:** Frameworks de LLM (LangChain/Agentes autónomos).
- **Modelos de Lenguaje:** Integración con LLMs de última generación (GPT-4o / Claude / Groq).
- **Vector Database:** Para la implementación de RAG.
- **Machine Learning:** `Scikit-learn`, `Pandas`.
- **Validación de Datos:** Salida estructurada mediante esquemas de validación.

---

## 📊 Datos y Conocimiento
- **Dataset de entrada:** `vinos.csv` (Atributos fisicoquímicos).
- **Base de Conocimiento:** Literatura técnica sobre enología y calidad química del vino.

---

## 🚀 Cómo utilizar este proyecto
1. Clona el repositorio.
2. Asegúrate de tener el archivo `vinos.csv` en la raíz.
3. Configura tus variables de entorno (API Keys de LLM).
4. Ejecuta el notebook `wineadvisor_agent_system.ipynb` para interactuar con el agente.

---
**Sobre la autora:** Especialista en **Data Governance**. Mi misión es liderar la transición hacia una IA corporativa donde la potencia de los LLMs se combine con el rigor del Gobierno del Dato y la precisión del Machine Learning.
