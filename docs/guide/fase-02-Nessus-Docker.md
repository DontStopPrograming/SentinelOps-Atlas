# Instalacion de Nessus Essentials en Docker

## 1. Despliegue
Se utilizo la imagen oficial de Tenable en Docker:
`docker run -d --name nessus -p 8834:8834 tenable/nessus:latest-ubuntu`
<br><br><br>

## 2. Registro
Se accedio a `https://localhost:8834` y se selecciono la opcion "Register for Nessus Essentials".
<br><br><br>

## 3. Escaneo
Se configuro un "Basic Network Scan" apuntando a la IP de la maquina Linux Mint para evaluar vulnerabilidades.

