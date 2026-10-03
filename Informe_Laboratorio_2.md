# Informe de Laboratorio: Searching Skills (TryHackMe)

## 📌 Descripción General
Informe correspondiente a la sala **Searching Skills** de TryHackMe. Se abordan herramientas de búsqueda de información, reconocimiento (OSINT) e inteligencia de amenazas para ciberseguridad defensiva y ofensiva.

---

## 📑 Índice de Contenidos
1. [Introducción a la Búsqueda de Información](#1-introducción-a-la-búsqueda-de-información)
2. [Shodan (TryScanMe)](#2-shodan-tryscanme)
3. [VirusTotal](#3-virustotal)
4. [Bases de Datos de Vulnerabilidades (CVE)](#4-bases-de-datos-de-vulnerabilidades-cve)
5. [Documentación Técnica y Páginas Man](#5-documentación-técnica-y-páginas-man)
6. [GitHub como Fuente de Inteligencia](#6-github-como-fuente-de-inteligencia)
7. [Conclusiones](#7-conclusiones)

---

## 🔍 Desarrollo del Laboratorio 

### 1. Introducción a la Búsqueda de Información
- **Concepto:** El uso eficiente de fuentes abiertas en internet es una habilidad crítica en ciberseguridad para rastrear vectores de ataque, evaluar vulnerabilidades y comprender el comportamiento del adversario.

### 2. Shodan (TryScanMe)
- **Concepto:** Motor de búsqueda para dispositivos conectados a Internet (IoT, servidores, sistemas industriales).
- **Filtros de Búsqueda Aplicados:**
  - `country:` Filtra por código de país (ej. `country:IE`).
  - `port:` Filtra por puertos abiertos (ej. `port:22`).
  - `org:` Filtra por organización o ASN (ej. `AS7224`).
  - `hostname:` Coincidencia por nombre de dominio.

### 3. VirusTotal
- **Concepto:** Servicio de análisis multimotor (más de 70 antivirus y escáneres de sitios web).
- **Aplicación:** Inspección de hashes, direcciones IP, dominios y archivos sospechosos para lograr consenso sobre la presencia de malware o amenazas.

### 4. Bases de Datos de Vulnerabilidades (CVE)
- **Concepto:** Diccionario estandarizado de vulnerabilidades conocidas (`CVE-AAAA-NNNN`) mantenido por el NIST y el NVD.
- **Métrica CVSS:** Evaluación objetiva del riesgo analizando factores de impacto, complejidad y disponibilidad de exploits.
- **Uso de PoCs:** Consulta de pruebas de concepto en plataformas como Exploit-DB.

### 5. Documentación Técnica y Páginas Man
- **Concepto:** Priorización de fuentes oficiales frente a tutoriales de terceros.
- **Uso de Linux Man Pages:** Consulta directa en terminal con el comando `man <comando>` (ej. `man nc`).

### 6. GitHub como Fuente de Inteligencia
- **Concepto:** Búsqueda directa de repositorios que alojan códigos PoC o de prueba de vulnerabilidades (ej. `CVE-2026-1337`).
- **Análisis de Riesgo:** Verificación cuidadosa del código fuente antes de su ejecución para evitar descargar malware o scripts defectuosos.

---

## 💡 Conclusiones
La capacidad de investigar y recopilar inteligencia de fuentes abiertas (OSINT) minimiza los tiempos de respuesta ante incidentes y permite identificar de forma proactiva sistemas vulnerables antes de que sean explotados.
