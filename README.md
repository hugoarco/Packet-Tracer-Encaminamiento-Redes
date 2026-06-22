<h1 align = "center" >🌐 Manual de Encaminamiento y Conectividad en Packet Tracer</h1> 

[![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)](https://www.cisco.com/)
[![Packet Tracer](https://img.shields.io/badge/Packet%20Tracer-8.0+-blue?style=for-the-badge)](https://www.netacad.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)]()

## 📖 Descripción

Manual completo y guía paso a paso para la configuración de **encaminamiento estático** y **conectividad entre subredes** utilizando **Cisco Packet Tracer**. Este proyecto incluye la planificación de direccionamiento IP, configuración de interfaces de routers y tablas de enrutamiento, así como pruebas de conectividad y soluciones de redundancia.

Diseñado como material educativo para estudiantes de **Sistemas Microinformáticos y Redes (SMR)**, aunque su contenido es aplicable a **ASIR** y a cualquier persona que quiera aprender los fundamentos del encaminamiento.

## 🎯 Objetivos del proyecto

- ✅ **Diseñar** una topología de red con 5 subredes.
- ✅ **Calcular** direcciones IP, máscaras de subred, rangos y broadcast.
- ✅ **Configurar** interfaces de routers en Packet Tracer.
- ✅ **Implementar** tablas de enrutamiento estático.
- ✅ **Verificar** la conectividad entre equipos de diferentes subredes con `ping`.
- ✅ **Añadir** un enlace físico de respaldo para garantizar la redundancia.
- ✅ **Documentar** todo el proceso en un manual detallado.

## 🛠️ Contenido del repositorio

| Archivo | Descripción |
|---------|-------------|
| `PRÁCTICA ENCAMINAMIENTO CLASE ARCONES MARTINEZ HUGO.docx` | Manual completo con explicaciones, capturas y pasos. |
| `encaminamiento.pkt` | Archivo de Packet Tracer con la red completamente configurada. |

## 📊 Topología de la red

El escenario está compuesto por **5 subredes** interconectadas a través de **3 routers**. A continuación se detalla el direccionamiento:

| Subred | Dirección de red | Mascara | Rango | Broadcast | Gateway |
|--------|------------------|---------|-------|-----------|---------|
| **Subred 1** | 172.16.1.0/24 | 255.255.255.0 | 172.16.1.1 - 172.16.1.254 | 172.16.1.255 | 172.16.1.1 |
| **Subred 2** | 172.16.2.0/24 | 255.255.255.0 | 172.16.2.1 - 172.16.2.254 | 172.16.2.255 | 172.16.2.1 |
| **Subred 3** | 172.16.3.0/24 | 255.255.255.0 | 172.16.3.1 - 172.16.3.254 | 172.16.3.255 | 172.16.3.1 |
| **Subred 4** | 172.16.4.0/24 | 255.255.255.0 | 172.16.4.1 - 172.16.4.254 | 172.16.4.255 | - |
| **Subred 5** | 172.16.5.0/24 | 255.255.255.0 | 172.16.5.1 - 172.16.5.254 | 172.16.5.255 | - |

## 🚀 Cómo usar este proyecto

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/hugoarco/Packet-Tracer-Encaminamiento-Redes.git
Abre el archivo .pkt con Cisco Packet Tracer (versión 8.0 o superior).

Revisa las configuraciones:

Accede a los routers y verifica las tablas de enrutamiento con show ip route.

Realiza pruebas de conectividad desde cualquier PC con ping.

Consulta el manual para entender el proceso paso a paso y los fundamentos teóricos.

📸 Capturas de pantalla
Topología final
https://media/topologia.png

Tabla de enrutamiento Router 0
https://media/router0_routing.png

Prueba de conectividad
https://media/ping_test.png

👤 Autor
Hugo Arco
Estudiante de SMR | Apasionado por la automatización, redes y administración de sistemas
GitHub · Gmail

📄 Licencia
Este proyecto está bajo la licencia MIT.
Consulta el archivo LICENSE para más información.

<p align="center"> <b>Hecho con ❤️, cables virtuales y mucho enrutamiento</b> </p>
