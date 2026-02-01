# 🛡️ Presupuesto de Inversión en Ciberseguridad 2026 (Enterprise)

**Perfil de la Empresa:** 
* **Usuarios:** ~3,000  
* **Endpoints:** ~3,000  
* **Servidores (Físicos/Virtuales):** 200 aprox.(Entorno optimizado)

> **Nota:** Se mantiene la recomendación de negociar descuentos del **20% al 35%** por volumen de usuarios, aunque el poder de negociación en licencias de servidor disminuye ligeramente al reducirse el conteo.

---

## 📊 1. Resumen Ejecutivo de Inversión (Anual)

| Pilar Estratégico | Costo Estimado (Anual) | Notas de Escalamiento |
| :--- | :--- | :--- |
| **1. Zero Trust (Identidad)** | $250,000 - $480,000 USD | El foco principal por el volumen de 3,000 usuarios. |
| **2. Email Security** | $180,000 - $290,000 USD | Protección crítica; costo ligado a buzones de usuario. |
| **3. Cloud Security (CNAPP)** | $25,000 - $45,000 USD | **Reducción significativa** (ajustado a 200 servers). |
| **4. SOC Moderno (XDR/SIEM)** | $320,000 - $550,000 USD | Menor volumen de logs provenientes de servidores. |
| **5. Resiliencia (Backups)** | $35,000 - $60,000 USD | Ajustado a 150 TBs enfocados en datos de usuario/core. |
| **Servicios Profesionales** | $70,000 - $110,000 USD | Implementación de SOC e Identidad. |
| **TOTAL ESTIMADO** | **$880,000 - $1.5M USD** | **Presupuesto optimizado (OPEX Anual)** |

---

## 🛠️ 2. Desglose Tecnológico Detallado

### A. Pilar Zero Trust (Identidad y Acceso)
| Tecnología | Solución Ejemplo | Cálculo (3,000 Users) | Est. Anual |
| :--- | :--- | :--- | :--- |
| **IAM / SSO / MFA** | Okta / Entra ID P2 | $6 - $10 USD/u/mes | $216k - $360k |
| **ZTNA (VPN Replace)** | Zscaler / Prisma Access | $10 - $14 USD/u/mes | $360k - $500k |
| **PAM (Privilegiados)** | CyberArk / Delinea | 30 Admins x $80/mes | $28,800 |

### B. Pilar Email Security
| Tecnología | Solución Ejemplo | Cálculo (3,000 Users) | Est. Anual |
| :--- | :--- | :--- | :--- |
| **Secure Email Gateway** | Proofpoint / Mimecast | $5 - $8 USD/u/mes | $180k - $288k |
| **DMARC Enforcement** | Valimail / Red Sift | Dominio principal | $15,000 |

### C. Pilar Cloud & Server Security (CNAPP)
*Ajustado a la nueva escala de 200 cargas de trabajo.*

| Tecnología | Solución Ejemplo | Cálculo (200 Workloads) | Est. Anual |
| :--- | :--- | :--- | :--- |
| **CSPM + CWPP** | Wiz / Prisma Cloud | $10 - $15 USD/wk/mes | $24k - $36k |
| **Gestión de Secretos** | HashiCorp Vault | Licencia Standard | $15k - $25k |

### D. Pilar SOC Moderno (Visibilidad)
| Tecnología | Solución Ejemplo | Cálculo | Est. Anual |
| :--- | :--- | :--- | :--- |
| **XDR / EDR** | CrowdStrike / S1 | 3,500 EP x $7-$10/mes | $294k - $420k |
| **SIEM (Logs)** | Splunk / Sentinel | 80-120 GB/día ingesta | $60k - $100k |

---

