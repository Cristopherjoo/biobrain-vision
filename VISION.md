# Vision — BioBrain Poliglota

## Introducción

BioBrain es una herramienta de análisis estructural y semántico diseñada para transformar bases de código complejas en representaciones organizadas, navegables y procesables.

El objetivo del sistema no es generar código ni reemplazar desarrolladores, sino facilitar la comprensión de arquitecturas de software mediante extracción estructural, indexación contextual y análisis semántico offline.

BioBrain reduce la fricción entre:
- el código fuente,
- la comprensión humana,
- y los sistemas externos que requieren interpretar estructuras de software de manera eficiente.

---

## Imagen 1 (Vista general del sistema)

![Interfaz de Sincronización en Tiempo Real](assets/panel01.png)


---

## Problema

A medida que los sistemas crecen, aumenta la dificultad para:

- comprender la estructura global del sistema,
- visualizar relaciones entre módulos,
- mantener documentación actualizada,
- integrar IA sobre bases de código reales,
- navegar arquitecturas grandes sin perder contexto.

Las herramientas existentes suelen:
- depender de servicios cloud,
- mezclar análisis con generación de código,
- priorizar automatización sobre interpretabilidad.

BioBrain propone un enfoque distinto:
- análisis estructural primero,
- representaciones interpretables,
- IA local,
- persistencia estructural del conocimiento del sistema.

---

## Objetivo del proyecto

BioBrain busca funcionar como una capa intermedia entre:

- proyectos de software,
- motores de análisis,
- sistemas de visualización,
- herramientas de IA local.

Su propósito es convertir código fuente en una representación estructurada reutilizable que pueda alimentar:

- documentación técnica,
- análisis semántico,
- clustering lógico,
- motores externos,
- sistemas de visualización,
- o capas de inteligencia contextual.

---

## Imagen 2 (Ejemplo de salida)

![Interfaz de Sincronización en Tiempo Real](assets/panel02.png)


---

## Estado actual del proyecto — v3.0.0

BioBrain actualmente incluye:

### Capacidades implementadas

- Extracción AST para Python
- Parsing Java mediante Tree-sitter
- Detección automática de lenguaje
- Clustering jerárquico por archivo
- Indexación estructurada (`index.json`)
- Persistencia separada por lenguaje
- Análisis semántico local mediante Ollama
- Interfaz visual PyQt6
- Integración experimental con Synapsekai
- Streaming SSE para monitoreo externo
- Mapeo básico de dependencias cruzadas

---

## Lenguajes soportados

| Lenguaje | Estado |
|----------|--------|
| Python | Estable |
| Java | Experimental estable |
| Cobol | Exploración futura |

---

## Estado general del sistema

| Área | Estado |
|------|--------|
| Núcleo AST Python | Estable |
| Parser Java | Activo |
| UI PyQt6 | Funcional |
| IA semántica local | Funcional |
| Integración Synapsekai | Experimental |
| Reportes avanzados | En desarrollo |
| Sistema multilenguaje | En evolución |

---

## Filosofía del proyecto

### Offline-first
El análisis se ejecuta localmente sin depender de infraestructura cloud.

### Transparencia estructural
Las representaciones generadas deben ser interpretables y auditables.

### No invasivo
El sistema no modifica el código fuente analizado.

### Modularidad
Cada componente evoluciona de forma independiente.

### Persistencia reutilizable
Los datos generados pueden reutilizarse en otros sistemas, IA o pipelines.

---

## Relación con Synapsekai

BioBrain y Synapsekai son sistemas independientes y desacoplados que operan bajo un modelo cliente-servidor local.

BioBrain actúa como:
- el cliente principal y extractor estructural,
- el indexador de código y organizador de arquitectura,
- el proveedor de contexto (Blueprint JSON) y la interfaz de usuario (PyQt6).

Synapsekai actúa como:
- el motor biológico backend y servidor de simulación,
- el entorno de procesamiento físico y neuronal en un volumen 3D discreto,
- el sistema de monitoreo homeostático que calcula la fatiga y los signos vitales del código.

La integración ocurre localmente mediante:
- APIs HTTP (incluyendo el Wake-Up Service de latencia),
- blueprints estructurales en formato JSON,
- streaming de datos mediante Server-Sent Events (SSE).


---

## Alcance del sistema

BioBrain no está diseñado para ser:

- un IDE,
- un agente autónomo,
- un generador de código,
- un compilador,
- ni un reemplazo de herramientas tradicionales.

Su enfoque principal es:
- interpretación estructural,
- organización contextual,
- representación navegable de arquitecturas de software.

---

## Dirección futura

Las siguientes etapas incluyen:

- soporte para Go y TypeScript,
- escaneo incremental,
- reportes HTML/PDF,
- métricas comparativas por lenguaje,
- mejoras en análisis semántico,
- visualización avanzada de arquitectura,
- optimización para monorepos grandes.

---

## Estado del repositorio

Este repositorio documenta:
- la evolución conceptual del sistema,
- la arquitectura general,
- la visión del proyecto,
- y las capacidades actuales.

La implementación interna puede cambiar con rapidez mientras el proyecto sigue en desarrollo activo.

---

## Autor

Cristopher Joo  
Desarrollador independiente — Chile

> BioBrain explora formas de transformar arquitecturas de software en estructuras comprensibles, navegables y reutilizables.