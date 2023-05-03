# LISTADO DE COMANDOS PARA MIKROTIK 
---
![mikrotik](https://user-images.githubusercontent.com/83385717/227599696-f5dba4fb-90d3-4485-ba8a-f456732bb2f2.png)


   ![Badge](https://img.shields.io/badge/STATUS-En%20desarrollo-blue)
   ![Badge](https://img.shields.io/pypi/status/aiogram.svg?style=flat-square)
   ![Badge](https://img.shields.io/badge/MikroTik%20RouterOS%20-6.48.6-blue)
## Este manual introduce los comandos que son usados para realizar la siguientes funciones:

**Sección 1: Comandos Generales / Destacados (Disponibles desde directorio raíz)**:
 - `/?`: Visualización de ayuda (comandos adicionales disponibles desde la interfaz de MikroTik).
 - `Tecla TAB`: IMPORTANTE--> Presionar cuando se escriba una palabra reservada de color azul para ver comandos adicionales o cuando se desee completar de forma automática algún otro comando.
 - `file print`: Muestra archivos almacenados en el router.
 - `interface print`: Muestra datos de las interfaces disponibles (Incluye -> NAME, TYPE, ACTUAL-MTU, L2MTU , MAX-L2MTU, MAC-ADDRESS).
 - `ip address print`: Visualizar dirección IP, red e interfaz.
 - `interface bridge print`: Despliega datos de interface bridge.
 - `user print`: Muestra lista de usuarios, grupos y direcciones (Incluyendo LAST-LOGGED-IN).
 - `log print`: Imprime lista de logs del MT.
 - `export`: Visualizar o guardar un script.
 - `system reboot`: Reiniciar el router.
 - `system shutdown`: Apagar el router.
 - `system reset-configuration`: Limpia toda la configuración del router y setea la configuración por defecto.
 - `system upgrade download-all`: Actualizar el router a la version más actual disponible.
 - `system resource print`: Ver recursos del sistema.
 - `tool profile`: Muestra el uso de CPU de los procesos en ejecución
 - `certificate print`: Permite visualizar datos del certificado (Name, fingerprint, etc).
 - `snmp print`: Despliega informacion sobre SNMP.
 - `snmp community print`: Muestra: NAME, ADDRESSES, SECURITY, READ-ACCESS WRITE-ACCESS.

---

**Sección 1.1: Comandos del sistema (Disponibles desde `/system`)**:
 - `/?`: Visualización de ayuda (comandos adicionales disponibles desde la interfaz de /system).
 - `Tecla TAB`: IMPORTANTE--> Presionar cuando se escriba una palabra reservada de color azul para ver comandos adicionales o cuando se desee completar de forma automática algún otro comando.
 - `backup save`: Hace una copia de seguridad de la configuración actual.
 - `backup load`: Carga una copia de seguridad previamente guardada.
 - `clock print`: Imprimir/cambiar fecha y hora del sistema.
 - `default-configuration print`: Carga una copia de seguridad previamente guardada.
 - `health print`: Voltage & temperature.
 - `history print`: Historial de comandos.
 - `package print`: Información sobre versión de paquetes del sistema.
 - `reboot`: Reiniciar el router.
 - `reset-configuration`: Limpia toda la configuración del router y setea la configuración por defecto.
 - `resource print`: Ver recursos del sistema.
 - `routerboard print`: Ver version de MikroTik.
 - `scheduler`: Programar scripts para que se ejecuten en cierto momento.
 - `script export`: Visualizar o guardar un script.
 - `shutdown`: Apagar el router.
 - `upgrade download-all`: Actualizar el router a la version más actual disponible.

---

**Sección 2: (Comandos disponibles desde `/interface`)**:
 - `/?`: Visualización de ayuda (comandos adicionales disponibles desde la interfaz de /interface).
 - `Tecla TAB`: IMPORTANTE--> Presionar cuando se escriba una palabra reservada de color azul para ver comandos adicionales o cuando se quiera completar de forma automatica algún otro comando.
 - `print`: Imprime resumen de interfaz.
 - `ethernet print`: Imprime datos de interfaces ethernet.
 - `monitor-traffic`: Monitorea tráfico de la interfaz requerida.
 - `detect-internet print`: Muestra lista de interfaces de internet, LAN y WAN.
 - `ipip print`: Interfaces de tunel IP.
 - `vlan print`: Interfaces VLAN.
 - `vrrp print`:  NAME, INTERFACE, MAC-ADDRESS, VRID PRIORITY INTERVAL, VERSION V3-PROTOCOL.

---

 **Sección 3: (Comandos disponibles desde `/ip`)**:
 - `/?`: Visualización de ayuda (comandos adicionales disponibles desde la interfaz de /ip).
 - `Tecla TAB`: IMPORTANTE--> Presionar cuando se escriba una palabra reservada de color azul para ver comandos adicionales o cuando se quiera completar de forma automatica algún otro comando.
 - `ip arp print`: Adress, MAC-Adress & Interface.
 - `dhcp-client print`: Ajustes del cliente DHCP.
 - `dhcp-server print`: Ajustes del servidor DHCP.
 - `dns print`: Ajustes de DNS.
 - `neighbor print`: Neighbors.
 - `proxy print`: Puerto, cache-client, cache-server etc.
 - `route print`: DST-ADDRESS, PREF-SRC, GATEWAY, DISTANCE, etc.
 - `service print`: NAME, PORT, ADDRESS, CERTIFICATE, etc.
 - `settings print`: Info about--> tcp-syncookies, icmp-rate-limit, ipv4-fast-path-active, etc.

