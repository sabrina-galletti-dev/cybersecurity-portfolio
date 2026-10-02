# 📝 Informe de Laboratorio: Introducción a la Seguridad Ofensiva y Defensiva

- **Plataforma:** TryHackMe
- **Ruta:** Comienza tu camino hacia la ciberseguridad (*Cyber Security 101*)
- **Laboratorio:** Introducción a la seguridad ofensiva / Defensiva (FakeBank)
- **Estado:** Completado 100%

---

## 🎯 Objetivo del Laboratorio
Comprender los conceptos fundamentales de la **Seguridad Ofensiva** (descubrimiento de activos y explotación de vulnerabilidades en un entorno simulado de *FakeBank*) y la **Seguridad Defensiva** (monitoreo, contención y respuesta a incidentes en un equipo SOC).

---

## 🛠️ Herramientas Utilizadas
**FakeBank Admin Panel:** Panel de administración web simulado donde se realizó el análisis y contención del incidente.
**Módulo de Alertas SOC:** Interfaz para identificar las direcciones IP y nombres de usuario involucrados en el ataque.

---

## 🛡️ Conceptos Clave y Metodología Defensiva (SOC)

### 1. Gestión de Brechas de Seguridad
Cuando un equipo SOC (*Security Operations Center*) detecta una amenaza activa, **no debe eliminarla de inmediato de forma impulsiva**. Se debe priorizar:
* **Contención y Análisis:** Aislar el peligro mientras se analiza el comportamiento de la amenaza.
* **Preservación de Evidencia:** Proteger los registros e imágenes de memoria para el análisis forense posterior.
* **Comprender el Alcance:** Verificar si el atacante logró persistencia (instaló *backdoors* o accesos secundarios por otra vía).

### 2. Flujo de Trabajo en la Detección y Respuesta
* **Alerta e Identificación:** Revisar los paneles de alerta para identificar al usuario o cuenta comprometida (`username`).
* **Contención Activa:** Detener y bloquear al usuario/cuenta involucrada.
* **Investigación de Comportamiento:** Rastrear y analizar todos los intentos de ataque del actor de amenaza. Conocer la intención del atacante permite aplicar medidas correctivas efectivas.
* **Remediación:** Actualizar el sistema y aplicar parches de seguridad.

---

## 📋 Informe de Incidentes
Al finalizar la respuesta ante un incidente, se debe documentar la siguiente información técnica:
* **Tipo de ataque**
* **Grupo atacante (Atribución)**
* **Dirección IP del atacante**
* **Página / Activo objetivo (*Target*)**

---

## 💡 Lecciones Aprendidas
1. La seguridad ofensiva ayuda a pensar como un atacante para descubrir rutas no documentadas o páginas ocultas antes de que sean explotadas.
2. La respuesta a incidentes requiere metodologías claras y estructuradas; actuar apresuradamente puede destruir evidencia vital o ignorar accesos secundarios del atacante.
