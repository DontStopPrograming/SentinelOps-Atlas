# SentinelOps-Atlas 🛡️

Proyecto Operaciones de ciberseguridad desarrollado desde cero.
Se aplicara la documentacion del diseño, despliegue, automatizacion y gestion de controles de seguridad utilizando herramientas Open Source y estandares de la industria.
<br><br><br>




## 🎯 Objetivo

Demostrar el uso de la gestion de vulnerabilidades, monitoreo SIEM, proteccion de endpoints, gestion de identidades (IAM), y documentacion de evidencias para auditorias.
<br><br><br>

## 🛠️ Herramientas Desplegadas

* **SIEM / XDR:** Wazuh (Manager, Indexer, Dashboard) en Docker.
* **Gestion de Vulnerabilidades:** Nessus Essentials (Docker).
* **Sistemas Operativos:** Ubuntu Server (como Infraestructura), Linux Mint (como Agente / Endpoint).
<br><br><br>

## 📂 Estructura del Proyecto

- `docs/`: Documentacion, guias de instalacion, arquitectura e inventario de herramientas.
- `evidence/`: Capturas y evidencias organizadas por fases sanitizadas.
- `scripts/`: Automatizaciones en Python/Bash.
- `bitacoras/`: Plantillas operativas (.ods) y reportes.
<br><br><br>

## 🚦 Fases del Proyecto

- **Fase 01:** Fundamentos y arquitectura
- **Fase 02:** Gestion de vulnerabilidades con Nessus Essentials
- **Fase 03:**
- **Fase 04:**
- **Fase 05:**
- **Fase 06:**
- **Fase 07:**
- **Fase 08:**
- **Fase 09:**
- **Fase 10:**
- **Fase 11:**
- **Fase 12:**
- **Fase 13:**
<br><br><br>

## ⚖️ Licencia y Herramientas

El contenido del repositorio esta bajo la licencia **MIT**.
Las herramientas de terceros utilizadas manejan sus propias licencias.
<br><br><br>



# Instalacion de Nessus Essentials en Docker

## 1. Despliegue
Se utilizo la imagen oficial de Tenable en Docker:
`docker run -d --name nessus -p 8834:8834 tenable/nessus:latest-ubuntu`

## 2. Registro
Se accedio a `https://localhost:8834` y se selecciono la opcion "Register for Nessus Essentials".

## 3. Escaneo
Se configuro un "Basic Network Scan" apuntando a la IP de la maquina Linux Mint para evaluar vulnerabilidades.


<br><br><br>
