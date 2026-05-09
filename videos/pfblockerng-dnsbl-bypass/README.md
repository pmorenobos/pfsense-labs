# pfBlockerNG DNSBL Bypass con Unbound en pfSense

Este laboratorio muestra cómo excluir una IP específica del filtrado DNSBL de pfBlockerNG usando vistas de Unbound en pfSense.

## Escenario

- Firewall: pfSense
- Paquete: pfBlockerNG
- Servicio DNS: Unbound Resolver
- Función: bypass de DNSBL por IP
- Cliente excluido del filtrado: `192.168.8.99/32`
- Red filtrada 1: `192.168.8.0/24`
- Red filtrada 2: `192.168.100.0/24`

## Archivo relacionado

En esta carpeta se agregará el archivo de configuración:

```text
pfblockerng-dnsbl-bypass.conf
