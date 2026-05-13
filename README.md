# VeloSpan | Component Lifecycle Manager

> **Kilómetros digitales, mantenimiento real**

VeloSpan es un sistema integral de gestión de activos ciclistas diseñado para automatizar el seguimiento del ciclo de vida de los componentes mecánicos mediante la telemetría de tus entrenamientos.

🔗 **Accede a la web del proyecto:** [velospan.app](https://velospan.vercel.app/)

---

## 📋 Contexto y Motivación

En la última década, el ciclismo deportivo ha vivido una transformación digital profunda. Hoy en día, impera la "cultura del dato": todo entrenamiento que no se graba y se sube a la nube, no existe. Sin embargo, a pesar de monitorizar vatios y pulsaciones con precisión milimétrica, el mantenimiento mecánico sigue siendo subjetivo.

### El Problema
Según el estudio realizado durante este proyecto a 29 ciclistas reales:
* **82.8%** reconoce desconocer el kilometraje exacto de sus componentes.
* **79.3%** depende exclusivamente de la inspección visual subjetiva o de la aparición de ruidos extraños.
* Esta falta de control proactivo compromete la eficiencia mecánica y la **seguridad vial** del ciclista.

### La Propuesta: VeloSpan
VeloSpan nace como el puente necesario entre los datos de rendimiento deportivo y el mantenimiento preventivo. El nombre deriva de *Velo* (ciclismo) y *Span* (ciclo de vida), simbolizando el dominio total sobre la durabilidad del material.

---

## ✨ Funcionalidades Principales

* **Sincronización Automatizada:** Conexión transparente con la **API de Strava** mediante Webhooks para capturar cada kilómetro real sin intervención manual.
* **Modelado Granular de Activos:** Permite configurar un "Garaje Digital" con múltiples bicicletas y desglosar cada una en componentes individuales como cadena, cubiertas o líquido tubeless.
* **Semáforo de Desgaste:** Sistema visual basado en códigos de colores universales (Verde, Naranja, Rojo) para identificar estados críticos en menos de 3 segundos.
* **Alertas Predictivas:** Notificaciones proactivas cuando un activo alcanza el umbral de seguridad definido por el usuario.

---

## 🛠️ Stack Tecnológico

El sistema utiliza una arquitectura **Clean Architecture** cliente-servidor desacoplada para garantizar modularidad y alta disponibilidad.

* **Frontend:** [Flutter](https://flutter.dev/) para una experiencia nativa fluida en iOS y Android.
* **Backend:** [FastAPI](https://fastapi.tiangolo.com/) (Python) de alto rendimiento para la lógica de negocio.
* **Procesamiento Asíncrono:** Uso de [Redis](https://redis.io/) y [Celery](https://docs.celeryq.dev/) para gestionar la ingesta masiva de datos sin bloquear el sistema.
* **Persistencia:** [PostgreSQL](https://www.postgresql.org/) con SQLAlchemy para garantizar la integridad referencial.
* **Infraestructura:** Contenerización con [Docker](https://www.docker.com/) y despliegue automatizado en [Railway](https://railway.app/).

---

## 👤 Autor

**Fernando Carmona Palacio**
* Trabajo de Fin de Grado - 2026.
* Escuela de Ingeniería Informática - Universidad de Valladolid.
* Tutor: Alejandra Martínez Monés.