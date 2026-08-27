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

## 📄 Licencia y Derechos
Proyecto académico desarrollado para la Universidad Autónoma de Guadalajara (UAG). Todos los derechos reservados sobre el contenido intelectual y documental.
