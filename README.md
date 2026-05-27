# 🧠 BioBrain Poliglota

BioBrain es un sistema de análisis estático que transforma código fuente en una representación estructural jerárquica del software.

Su objetivo es facilitar la comprensión de arquitecturas complejas mediante la extracción de componentes como clases, funciones, métodos y dependencias, generando un mapa navegable del sistema.

---

## 🌍 Qué hace

BioBrain convierte un proyecto de software en una estructura organizada que representa su arquitectura interna sin modificar el código original.

Esta representación puede ser utilizada para:

- documentación técnica  
- análisis arquitectónico  
- exploración de bases de código  
- integración con herramientas de IA  
- visualización de estructuras de software  

---

## 🖥️ Interfaz del sistema

### 📂 Panel de escaneo

![Panel de escaneo del sistema](assets/panel01.png)

Este panel permite seleccionar un proyecto y ejecutar el análisis estructural del código fuente.

Muestra en tiempo real la detección del lenguaje, extracción de componentes y generación del índice estructural.

---

### 🧠 Panel de respuesta de IA local

![Respuesta de IA local](assets/panel02.png)

Este panel muestra el resultado del análisis semántico realizado por la IA local.

Cada componente del sistema es enriquecido con contexto, resumen técnico y clasificación estructural.

---

## ⚙️ Cómo funciona

El sistema analiza el código fuente y construye un modelo estructural basado en:

- análisis AST (Python)  
- análisis con Tree-sitter (Java)  
- detección automática de lenguaje  
- indexación jerárquica del sistema  
- agrupación de componentes relacionados  

El resultado es un conjunto de archivos estructurados en JSON que representan el sistema.

---

## 🧬 Características principales

- detección automática de lenguaje (Python / Java)  
- extracción estructural del código fuente  
- representación jerárquica de componentes  
- análisis semántico local con IA  
- interfaz visual para exploración del sistema  
- exportación de estructura en formato JSON  

---

## 🔌 Integración con otros sistemas

BioBrain puede exportar la estructura generada a herramientas externas mediante un flujo de datos basado en JSON.

Esta integración es opcional y permite utilizar el modelo estructural en otros sistemas de análisis o visualización.

---

## 🧭 Filosofía del sistema

- análisis local (offline-first)  
- no invasivo (no modifica el código)  
- enfoque estructural antes que semántico  
- salida reutilizable para otros sistemas  
- modularidad y separación de componentes  

---

## 🧱 Qué no es BioBrain

BioBrain no es:

- un IDE  
- un compilador  
- un generador de código  
- un agente autónomo  

Es una herramienta de interpretación estructural del software.

---

## 📦 Lenguajes soportados

- Python (estable)  
- Java (soporte mediante Tree-sitter)  

---

## 👤 Autor

Cristopher Joo — Chile
