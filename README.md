# 🛡️ Implementación de Wazuh

![Wazuh](https://img.shields.io/badge/Wazuh-Platform-005C84?style=for-the-badge&logo=wazuh&logoColor=white)
![SOC](https://img.shields.io/badge/SOC-Level%201-F97316?style=for-the-badge)
![Ubuntu](https://img.shields.io/badge/Ubuntu-24.04-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Estado](https://img.shields.io/badge/Estado-Completado-10B981?style=for-the-badge)

Este laboratorio presenta la instalación y puesta en marcha de Wazuh como plataforma de monitoreo de seguridad, mostrando su funcionamiento básico y las capacidades principales del entorno una vez desplegado.

---

## 📘 Descripción general

Este laboratorio documenta la instalación y configuración básica de **Wazuh** como plataforma SIEM/EDR de código abierto.  
Incluye el despliegue del servidor, el acceso al dashboard, la incorporación de agentes y la verificación de sus capacidades de monitoreo y análisis, orientado a prácticas iniciales de **SOC / Blue Team**.

---

## 🛠️ Evidencias Técnicas

### Configuración Inicial
• Máquina virtual dedicada con credenciales locales (`wazuh-user / wazuh`)
• Configuración de red estática: `192.168.1.34/24`

### Acceso al Dashboard
• Ingreso vía navegador web  
• Credenciales por defecto: `admin / admin`

### Estado de la Plataforma
• Agentes: 1 activo  
• Métricas básicas visibles desde el panel  
• Alertas clasificadas por severidad

### Despliegue de Agentes
• Instalación del agente en **Ubuntu 24.04**  
• Enlace correcto al servidor Wazuh Manager  
• Verificación de servicios (`wazuh-agent`, `wazuh-dashboard`)

---

## 📊 Capacidades Verificadas

•  Monitorización de endpoints  
•  Detección de vulnerabilidades  
•  File Integrity Monitoring  
•  Threat Hunting básico  
•  Integración con MITRE ATT&CK  
•  Alertas de malware y anomalías

---

## 🎯 Resultados

### Vulnerabilidades destacadas
• CVE-2023-3326  
• CVE-2022-3219  
• CVE-2024-52615 / 52616  

### Sistema monitorizado
• **OS:** Ubuntu 24.04.3 LTS  
• **Agente:** `ubuntu2025`  
• **Eventos registrados:** 1524 alertas  

---

## 💡 Conclusión

La implementación de Wazuh permitió validar funciones clave de seguridad, demostrando su utilidad como herramienta accesible para quienes inician en monitoreo, correlación y análisis de eventos dentro de un entorno SOC.

---

## 📬 Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ingrid-k)  
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ingridkaufmannok@gmail.com)
