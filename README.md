# Implementación de Wazuh

![Wazuh](https://img.shields.io/badge/Wazuh-Platform-blue)
![SOC](https://img.shields.io/badge/SOC-Level%201-orange)
![Ubuntu](https://img.shields.io/badge/OS-Ubuntu%2024.04-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📋 Descripción del Proyecto

Este laboratorio documenta la implementación exitosa de **Wazuh**. Se incluyó el despliegue completo de la plataforma de seguridad de código abierto para la monitorización y análisis de seguridad.

## 🛠️ Evidencias Técnicas Implementadas

### 🔹 Evidencia 1: Configuración Inicial
- Máquina virtual con credenciales de acceso:
  - Usuario: `wazuh-user`
  - Contraseña: `wazuh`

### 🔹 Evidencia 2: Verificación de Red
- Configuración de interfaz de red `eth0` con IP: `192.168.1.34/24`
- Verificación mediante comando `ip addr`

### 🔹 Evidencia 3: Acceso a la Interfaz Web
- Acceso al dashboard de Wazuh via Mozilla Firefox
- Credenciales: `admin` / `admin`

### 🔹 Evidencia 4: Panel de Control Operativo
- Dashboard principal con métricas de seguridad
- Resumen de agentes: 1 activo, 0 desconectados
- Visualización de alertas por nivel de severidad

### 🔹 Evidencia 5: Despliegue de Agentes
- Instalación del agente Wazuh en sistema Ubuntu
- Configuración de conexión al servidor manager
- Verificación del servicio `wazuh-dashboard`

## 📊 Capacidades Demostradas

- ✅ **Monitorización de Endpoints**
- ✅ **Detección de Vulnerabilidades**
- ✅ **File Integrity Monitoring**
- ✅ **Threat Hunting**
- ✅ **Integración MITRE ATT&CK**
- ✅ **Detección de Malware**

## 🎯 Resultados Obtenidos

### Top Vulnerabilidades Detectadas
- CVE-2023-3326 (16 ocurrencias)
- CVE-2022-3219 (11 ocurrencias)
- CVE-2024-52615/52616 (7 ocurrencias cada una)

### Sistema Monitorizado
- **OS**: Ubuntu 24.04.3 LTS
- **Agente**: `ubuntu2025`
- **Alertas**: 1,524 eventos registrados

## 💡 Conclusión

Wazuh se demostró como una herramienta poderosa e intuitiva para la recolección y análisis de logs, ideal para usuarios que comienzan en el ámbito SOC. A pesar de los desafíos técnicos durante la instalación, la implementación final fue exitosa y educativa.

---
 
## 👩‍💻 Autora

**Ingrid K.**  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ingrid-k)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ingridkaufmannok@gmail.com)
