# Red Multi-Sitio — Cisco Packet Tracer
Diseño e implementación de una red empresarial de 6 sitios con segmentación por VLANs, enrutamiento dinámico dual-stack (IPv4/IPv6), telefonía VoIP y políticas de seguridad mediante ACLs.
Características principales
Enrutamiento dinámico con OSPF (IPv4 e IPv6) entre 6 routers interconectados.
Dual stack IPv4/IPv6 en todas las zonas, con DHCP y DNS funcionando en ambos protocolos.
Segmentación VLAN por función (administración, servidores, usuarios, wireless, VoIP) en cada sitio.
Telefonía IP (VoIP) con plan de numeración propio y dial-peer configurados entre sedes.
Red inalámbrica con Wireless Router y dispositivos móviles integrados a la topología.
Políticas de seguridad (ACLs) para restringir acceso administrativo (SSH/HTTPS) y aislar tráfico wireless, en IPv4 e IPv6.
Servicios de red propios: DHCP, DNS y servidor web configurados y validados con pruebas de conectividad.

# Documentación técnica

El diseño completo —justificación de decisiones (OSPF vs. RIP, dual stack), esquema de direccionamiento por zona, configuraciones completas de cada router y switch, y pruebas de validación (conectividad, VoIP, DNS)— está detallado en el manual técnico.

# Cómo abrir el proyecto
1. Instalar Cisco Packet Tracer 
2. Abrir el archivo .pkt incluido en este repositorio.
