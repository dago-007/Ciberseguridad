# 🛡️ Estrategia de Ciberseguridad 2026
**Protección Unificada para una Empresa Diversificada en Nube Híbrida**

---

## 📽️ Diapositiva 1: Portada
# ESTRATEGIA CIBERSEGURIDAD 2026
### PROTECCIÓN UNIFICADA // NUBE HÍBRIDA
**Departamento de Tecnología y Transformación GFG**

---

## 📽️ Diapositiva 2: El Desafío
### ⚠️ EL DESAFÍO: COMPLEJIDAD HÍBRIDA

* **Superficie Expandida:** La combinación de on-premise, AWS, Azure y múltiples sedes ha creado puntos ciegos críticos.
* **Visibilidad Fragmentada:** Las herramientas aisladas (silos) impiden la correlación de datos y la detección rápida.
* **Brechas de Cumplimiento:** Niveles de madurez inconsistentes entre unidades de negocio aumentan el riesgo regulatorio.
* **Movimiento Lateral:** Alto riesgo de que un compromiso en una filial se propague al núcleo corporativo.

---

## 📽️ Diapositiva 3: Pilar 1 - Zero Trust
### 🔒 PILAR 1: ARQUITECTURA ZERO TRUST

| Componente | Acción Clave | Tecnologías Sugeridas |
| :--- | :--- | :--- |
| **Identidad (IAM)** | SSO y MFA obligatorio para todo acceso. | *Okta, Entra ID* |
| **Micro-segmentación** | Aislamiento de cargas de trabajo críticas. | *Illumio* |
| **Acceso Privilegiado** | Acceso Just-in-Time (JIT) para Admins. | *CyberArk* |
| **Validación (ZTNA)** | Acceso seguro sin dependencia de VPN. | *Zscaler* |



---

## 📽️ Diapositiva 4: Pilar 2 - Email Security
### 📧 PILAR 2: SEGURIDAD DE EMAIL
**Protección contra el vector de ataque #1: Phishing y BEC.**

* **Secure Email Gateway (SEG):** Filtrado avanzado de spam y malware. *(Proofpoint)*
* **Protección API (Next-Gen):** IA para detectar fraudes internos y anomalías. *(Abnormal)*
* **Autenticación de Dominio:** Implementación estricta de **DMARC, SPF y DKIM**.
* **Concientización:** Simulaciones continuas para fortalecer el "Firewall Humano".

---

## 📽️ Diapositiva 5: Pilar 3 - Cloud Security
### ☁️ PILAR 3: SEGURIDAD EN NUBE (CNAPP)

1.  **Postura (CSPM):** Remediación automática de errores en AWS/Azure. *(Wiz)*
2.  **Workloads (CWPP):** Seguridad en runtime para contenedores. *(Crowdstrike)*
3.  **Gestión de Secretos:** Rotación automatizada de llaves y BYOK. *(HashiCorp Vault)*
4.  **DevSecOps:** Análisis SAST integrado en el pipeline CI/CD. *(Snyk)*

---

## 📽️ Diapositiva 6: Pilar 4 - SOC Moderno
### ⚡ PILAR 4: SOC MODERNO (VISIBILIDAD)

> **"No se puede proteger lo que no se puede ver."**

* **SIEM Híbrido:** Correlación centralizada de logs on-prem y nube. *(Splunk)*
* **XDR (Detección Extendida):** Respuesta automatizada en endpoints. *(SentinelOne)*
* **SOAR (Automatización):** Orquestación para reducir tiempos de respuesta.
* **Resiliencia de Datos:** Backups inmutables contra Ransomware. *(Rubrik)*

---

## 📽️ Diapositiva 7: Hoja de Ruta
### 📅 HOJA DE RUTA DE IMPLEMENTACIÓN 2026

* **Q1 - VISIBILIDAD:** Inventario de activos y despliegue inicial de EDR.
* **Q2 - HIGIENE:** MFA Global, Email Security y endurecimiento de Nube.
* **Q3 - ZERO TRUST:** Micro-segmentación de red y acceso condicional.
* **Q4 - OPTIMIZACIÓN:** Automatización SOAR y ejercicios de *Red Teaming*.

---

## 📽️ Diapositiva 8: KPIs
### 📈 MÉTRICAS DE ÉXITO

* ✅ **100%** Cobertura de MFA en aplicaciones críticas.
* ⏱️ **< 4h** Tiempo Medio de Respuesta (MTTR).
* 🛡️ **95%** Aplicación de parches críticos en menos de 48h.

---

## 📽️ Diapositiva 9: Conclusión
> "La seguridad no es un freno para el negocio, es el habilitador que nos permite innovar con confianza en la nube híbrida."
>
> — **DEPARTAMENTO DE TECNOLOGÍA Y TRANSFORMACIÓN GFG**
