# 👋 Emanuel Simón Zepeda

### 🧠 Desarrollador Analista | Data Engineer | Automatización & Arquitectura de Sistemas

🚀 Especialista en diseño e implementación de soluciones de **integración de datos, automatización de procesos y control operativo**, enfocado en ambientes productivos empresariales.

---

## 🎯 Enfoque Profesional

* 🔄 Integración de datos: **SQL Server ↔ MySQL**
* ⚙️ Automatización de procesos críticos con Python
* 🧱 Arquitectura de sincronización controlada
* 📊 Conciliación de información (Facturación vs Contabilidad)
* 🤖 OCR + IA para extracción inteligente de datos

---

## 🏗️ Arquitectura de Trabajo

```
SQL Server (Source of Truth)
        ↓
   TallerZam.py
        ↓
 ControlLavado.py
        ↓
 ControlLlantas.py
        ↓
    MySQL (Target)
```

### 🔄 Orquestación

```
MasterSync.py
 ├── Ejecuta TallerZam
 ├── Espera finalización
 ├── Ejecuta ControlLavado
 ├── Espera finalización
 ├── Ejecuta ControlLlantas
```

✔ Sin ejecución simultánea
✔ Control de concurrencia
✔ Procesos auditables
✔ Integridad de datos garantizada

---

## 🧠 Principios de Ingeniería

* **Single Source of Truth**
* **Fail-Fast Strategy**
* **Observabilidad completa**
* **Ejecución secuencial controlada**
* **Trazabilidad operativa**

---

## 🛠️ Stack Tecnológico

![Python](https://img.shields.io/badge/Python-3.10-blue)
![SQL Server](https://img.shields.io/badge/SQL%20Server-Enterprise-red)
![MySQL](https://img.shields.io/badge/MySQL-Data-blue)
![Linux](https://img.shields.io/badge/Linux-Server-black)
![n8n](https://img.shields.io/badge/n8n-Automation-orange)

* Python (ETL, automatización)
* SQL Server / MySQL
* PowerShell / Bash
* OCR (Tesseract + OpenCV)
* n8n (automatización)
* Metabase (visualización)

---

## 📊 Impacto en Negocio

* 🔻 Eliminación de duplicidad de registros
* ⚡ Reducción de tiempos de procesamiento
* 🔐 Control total de ejecución de procesos
* 📈 Mejora en confiabilidad de datos
* 🧾 Trazabilidad completa de operaciones

---

## 📂 Proyectos Destacados

### 🔹 Sincronización Operativa

Sistema de integración controlada entre SQL Server y MySQL.

### 🔹 OCR Inteligente

Extracción automática de información desde documentos PDF.

### 🔹 Conciliación Facturación vs Contabilidad

Validación y análisis de discrepancias financieras.

---

## 📫 Contacto

* 📧 [emanuelsimon@hotmail.com](mailto:emanuelsimon@hotmail.com)
* 💼 LinkedIn: (agregar)

---

## 🧠 Filosofía

> “Un sistema sin control es un problema futuro.
> Un sistema con trazabilidad es una solución empresarial.”

---
