# Case 001 – Validación del Entorno del Sistema
## Objetivo

Documentar la validación inicial del entorno Linux utilizado como laboratorio SOC para análisis de seguridad.

Este proceso garantiza que el sistema, red, almacenamiento y privilegios funcionan correctamente antes de realizar investigaciones.

# Información del Sistema

## Sistema operativo:
Ubuntu 24.04.3 LTS

## Usuario:
ricardo-barboza-diaz

## Nombre de la máquina virtual:
Ubuntu Analyst

## Comandos Ejecutados
## 1. Versión del sistema
lsb_release -a

## 2. Versión del kernel
uname -a

## 3. Interfaces de red
ip a

## 4. Información del host
hostnamectl

## 5. Uso de disco
df -h

## 6. Conectividad a Internet
ping -c 3 google.com

## 7. Tabla de ruteo
ip route

## 8. Validación de privilegios
sudo -v

# Observaciones

El sistema reconoce correctamente Ubuntu 24.04.3 LTS.
La red está activa con dirección IP asignada.
Existe conectividad a Internet.
El almacenamiento está correctamente montado.
Las rutas de red están configuradas.
El usuario tiene privilegios administrativos.

# Evidencia








# Conclusión

El entorno Linux se encuentra validado y listo para ser utilizado como plataforma de laboratorio SOC para análisis de incidentes de seguridad.

# Estado

✔ Entorno validado
✔ Listo para operaciones SOC
