# Portfolio de Agentes de IA y Automatizaciones — Alura Latam

Este repositorio reúne los proyectos prácticos desarrollados durante la formación de **Agentes de IA para Negocios** en Alura Latam. Cada proyecto aborda la resolución de problemas operativos reales mediante soluciones No-Code / Low-Code conectadas a modelos de lenguaje (LLMs).

---

## 1. ARI News — Dashboard de Inteligencia Estratégica

**Herramientas:** Google Opal | Gemini API  
**Concepto:** Pipelines de Agentes de IA  
**🌐 Demo en vivo:** [Ver Dashboard de ARI News en Google Opal](https://opal.google/app/12W-lH8TSiqixzt7ntMh-RrgSVz7j0sZC)

### 📌 Descripción del Proyecto
ARI News es un sistema automatizado que busca noticias reales en internet, filtra y valida los resultados, y entrega una página profesional estructurada y lista para usar como dashboard de inteligencia estratégica, de forma totalmente visual y autónoma.

### 🛠️ Funcionalidades Clave
* **Búsqueda autónoma:** Recopilación de noticias reales en tiempo real desde internet.
* **Validación e Inteligencia:** Filtrado, sintesis y verificación mediante agentes de IA.
* **Interfaz Profesional:** Publicación y generación automática de un sitio interactivo.

### 🖼️ Captura del Proyecto
![ARI News Dashboard](assets/ari-news-dashboard.png)

---

## 2. ARI Flow — Automatización de Atención por Email (24/7)

**Herramientas:** Make.com | Gmail | Google Drive | Google Gemini API  
**Concepto:** Human-in-the-Loop Removal (Sistemas Autónomos 24/7)

### 📌 Descripción del Proyecto
ARI Flow es un sistema de trabajo autónomo diseñado para sacar al humano del loop operacional. Monitorea de forma continua la casilla de correo entrante, clasifica automáticamente las consultas sobre Oracle o servicios de la empresa, responde basándose en la documentación interna almacenada en Google Drive y deriva únicamente los casos no estandarizados a atención humana.

### 🛠️ Arquitectura del Flujo
1. **Trigger:** Monitoreo continuo de correo entrante en Gmail.
2. **Clasificación con IA:** Un agente impulsado por Google Gemini analiza la intención del mensaje.
3. **Consulta de Conocimiento:** Extracción y verificación de la documentación interna en Google Drive.
4. **Respuesta o Enrutamiento:**
   * **Automatizado:** Redacción y envío automático de la respuesta.
   * **Derivación:** Enrutamiento a un operador humano en caso de requerir supervisión.

### 🖼️ Captura del Escenario en Make
![ARI Flow Scenario](assets/ari-flow-make.png)

---

## 💡 Habilidades y Conceptos Clave Demostrados
* **Pipelines de Agentes:** Diseño e integración de agentes de IA para tareas complejas.
* **Integración de RAG/Documentación:** Uso de bases de conocimiento (Google Drive) para respaldar las respuestas de los modelos.
* **Automatización No-Code / Low-Code:** Construcción de flujos end-to-end con Make.com y Google Opal.
* **Operación Autónoma 24/7:** Configuración de sistemas que funcionan de forma continua sin supervisión directa.
