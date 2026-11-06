# Fase 06: Linea base de Seguridad

## 1. Evaluacion de Cumplimiento
Se intento utilizar OpenSCAP con el perfil CIS para Ubuntu 22.04, sin embargo, la version del escaner disponible en los repositorios (1.2.17) es incompatible con las reglas CIS (que requieren la version 1.3.x), generando un reporte vacio de 0% evaluacion.

## 2. Alternativa: Lynis
Como alternativa valida y compatible, se utilizo **Lynis**, una herramienta de auditoria de seguridad de codigo abierto.

**Comando ejecutado en Linux Mint:**
```bash
  sudo lynis audit system
```
