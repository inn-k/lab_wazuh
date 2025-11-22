# 🛡️ LAB: Implementación de Wazuh | SIEM

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Networking](https://img.shields.io/badge/Networking-008CFF?style=for-the-badge&logo=cisco&logoColor=white)
![Security](https://img.shields.io/badge/Blue_Team-101345?style=for-the-badge&logo=hackthebox&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-3585f9?style=for-the-badge&logo=wazuh&logoColor=white)
![SOC](https://img.shields.io/badge/SOC-171434?style=for-the-badge)
![Ubuntu](https://img.shields.io/badge/Ubuntu-e95420?style=for-the-badge&logo=ubuntu&logoColor=white)


Este laboratorio presenta la instalación y puesta en marcha de Wazuh como plataforma de monitoreo de seguridad, mostrando su funcionamiento básico y las capacidades principales del entorno una vez desplegado.

---

## 🌟 Descripción general

Este laboratorio documenta la instalación y configuración básica de **Wazuh** como plataforma SIEM/EDR de código abierto.  
Incluye el despliegue del servidor, el acceso al dashboard, la incorporación de agentes y la verificación de sus capacidades de monitoreo y análisis, orientado a prácticas iniciales de **SOC / Blue Team**.

---

## 📁 Evidencias Técnicas

Configuración Inicial \
• Máquina virtual dedicada con credenciales locales (`wazuh-user / wazuh`) \
• Configuración de red estática: `192.168.1.34/24`

Acceso al Dashboard \
• Ingreso vía navegador web \
• Credenciales por defecto: `admin / admin`

Estado de la Plataforma \
• Agentes: 1 activo \
• Métricas básicas visibles desde el panel \
• Alertas clasificadas por severidad

Despliegue de Agentes \
• Instalación del agente en **Ubuntu 24.04** \
• Enlace correcto al servidor Wazuh Manager \
• Verificación de servicios (`wazuh-agent`, `wazuh-dashboard`)

---

## 🎯 Objetivos

•  Monitorización de endpoints  
•  Detección de vulnerabilidades  
•  File Integrity Monitoring  
•  Threat Hunting básico  
•  Integración con MITRE ATT&CK  
•  Alertas de malware y anomalías

---

## 📬 Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ingrid-k)  
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ingridkaufmannok@gmail.com)
