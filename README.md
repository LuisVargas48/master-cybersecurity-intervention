# Diseño e Implementación de un Plan de Respuesta a Incidentes (IRP) para Canvas y SSO en AWS

Repositorio oficial del Proyecto de Intervención Profesional para la obtención del grado de **Maestría en Ciberseguridad Online** por la Universidad Autónoma de Guadalajara (UAG) / Arizona State University.

* **Autor:** Ing. Luis Alberto Vargas Gonzalez
* **Asesor:** Mtro. José de Jesús García Camarena
* **Institución:** Universidad Autónoma de Guadalajara (UAG)
* **Fecha:** Agosto, 2026

---

## 📋 Resumen Ejecutivo
Este proyecto aborda la vulnerabilidad operativa y el elevado Tiempo Medio de Contención (MTTC con un rango inicial de  45 a 90 minutos) ante incidentes de ciberseguridad en el Sistema de Gestión de Aprendizaje (LMS) Canvas y el portal de autenticación centralizada (SSO) de la Universidad Digital de las Américas (UDA). 

El objetivo principal fue diseñar e implementar un Plan de Respuesta a Incidentes (IRP) especializado en Amazon Web Services (AWS) para mitigar amenazas de alta criticidad (Ransomware y ataques DDoS), asegurando la continuidad académica de 25,000 estudiantes y el cumplimiento normativo con la **LFPDPPP**, **ISO/IEC 27001** y el estándar **NIST SP 800-61 r2**.

---

## 🛠️ Componentes Clave del Proyecto
1. **Gobernanza y Matriz de Escalación:** Delimitación de 4 niveles de severidad y flujos de decisión directiva para eliminar cuellos de botella operativos.
2. **Playbooks Tácticos de Contención:** Protocolos estructurados para la mitigación de secuestro de cuentas (*Account Takeover*) e infecciones por Ransomware.
3. **Defensa Perimetral Cloud:** Propuesta de filtrado automatizado mediante arquitectura elástica en AWS para neutralizar saturaciones de tráfico.
4. **Validación y Métricas:** Reducción exitosa del MTTC proyectado a menos de 5 minutos en entornos de prueba (Sandbox).

---

## 📂 Estructura del Repositorio

* **`docs/`** $\rightarrow$ Entregables oficiales finales del proyecto.
  * `IRP-UDA.pdf` (Documento en extenso).
  * `Presentacion_IRP_UDA.pdf` (Presentación ejecutiva para la defensa).
* **`evidencias_y_formatos/`** $\rightarrow$ Historial documental de avance y planeación metodológica.
  * Formatos de idea inicial del proyecto.
  * Tablas de congruencia y diseño de instrumentos de diagnóstico.
  * Plan de acción, cronograma de actividades y matrices de evaluación de resultados.

---    
## Alineación con Estándares Internacionales y Cumplimiento

Este Plan de Respuesta a Incidentes (IRP) se diseñó bajo los lineamientos de gobernanza, gestión del riesgo y cumplimiento normativo:

### ISO/IEC 27001:2022 (Anexo A)
* **A.5.24 - Planificación y preparación de la gestión de incidentes de seguridad:** Definición formal de la cadena de mando, roles de respuesta y procedimientos de escalación entre TI, Legal y Dirección.
* **A.5.25 - Evaluación y decisión sobre eventos de seguridad:** Criterios de clasificación y severidad para incidentes en Canvas y AWS SSO.
* **A.5.26 - Respuesta a incidentes de seguridad de la información:** Playbooks de contención técnica orientados a reducir el MTTC a menos de 30 minutos.
* **A.5.31 - Requisitos legales, estatutarios, reglamentarios y contractuales:** Alineación con la Ley Federal de Protección de Datos Personales (LFPDPPP) y garantía de SLA de disponibilidad (99.9%).

### NIST Cybersecurity Framework (CSF 2.0)
* **GOVERN (GV.OC / GV.PO):** Establecimiento de políticas de respuesta y contexto organizacional con la Alta Dirección.
* **RESPOND (RS.MA / RS.CO / RS.AN):** Protocolos de gestión de incidentes, comunicación con stakeholders y análisis de eventos críticos en nube.
* **RECOVER (RC.RP):** Procedimientos de restauración coordinados para mitigar impacto operativo.

---

## 📄 Licencia y Derechos
Proyecto académico desarrollado para la Universidad Autónoma de Guadalajara (UAG). Todos los derechos reservados sobre el contenido intelectual y documental.
