# VeloSpan — Landing Page Web

[![Web Status](https://img.shields.io/website?url=https%3A%2F%2Fvelospan.app)](https://velospan.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-magenta.svg)](https://opensource.org/licenses/MIT)
[![Stack](https://img.shields.io/badge/Stack-HTML5%20%7C%20TailwindCSS%20%7C%20JS-00B7EE.svg)]()

Este repositorio contiene el código fuente de la **landing page oficial** de **VeloSpan**. Este sitio web ha sido diseñado con un enfoque comercial y de producto para la captación de usuarios, actuando además como la plataforma pública requerida para la auditoría y validación del flujo de producción ante la API de Strava.

---

## 🚀 El Proyecto Global: ¿Qué es VeloSpan?

**VeloSpan** (del latín *Velo*, ciclismo; y del anglosajón *Span*, ciclo de vida) es un ecosistema integral de mantenimiento preventivo digital para ciclistas.

El sistema resuelve un problema crítico detectado mediante ingeniería de requisitos en una muestra real de ciclistas ($N=29$), donde el **82.8%** admitió desconocer el kilometraje exacto de su material y un **79.3%** dependía únicamente de evaluaciones visuales subjetivas. 

VeloSpan automatiza este proceso transformando los kilómetros digitales de las actividades deportivas en alertas proactivas sobre la salud del equipamiento.

### 💻 Repositorio del Proyecto Principal
La lógica de negocio pesada, la automatización y las aplicaciones nativas no se encuentran en este repositorio. Puedes auditar la arquitectura de software del sistema completo aquí:
🔗 **[Ir al repositorio de la Aplicación y Backend de VeloSpan](https://github.com/fercartri/velospanLatex)**

El núcleo global del sistema está compuesto por:
* **Backend:** API asíncrona construida con **FastAPI**, **Redis** y colas de tareas con **Celery**.
* **Frontend:** Aplicación móvil multiplataforma desarrollada en **Flutter** utilizando el patrón de diseño BLoC para la gestión de estados.
* **Persistencia:** Base de datos relacional sobre **PostgreSQL** administrada mediante el ORM SQLAlchemy.

---

## 🌐 Este Repositorio: Módulo Web de Captación

Este proyecto web estático implementa la capa de presentación pública del producto. Se centra en la conversión de clientes a través de un diseño de interfaz de alta fidelidad alineado con el manual de identidad corporativa de la marca.

---

## 🛠️ Instalación y Uso Local

Al tratarse de un desarrollo web estático, no requiere de compilación ni de un servidor de aplicaciones pesado:

1. Clona este repositorio:
   ```bash
   git clone [https://github.com/fercartri/velospanweb.git](https://github.com/fercartri/velospanweb.git)