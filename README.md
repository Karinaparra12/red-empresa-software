# red-empresa-software
Repositorio para el diseño y documentación de la infraestructura de red de una empresa de desarrollo de software.



# Infraestructura de Red - Empresa de Desarrollo de Software

## 📌 Objetivos de la Red

- Diseñar una red eficiente y escalable para una empresa de desarrollo de software.
- Asegurar la conectividad entre los departamentos de la empresa.
- Segmentar la red para mejorar el rendimiento y la seguridad.
- Facilitar la colaboración entre los equipos mediante el uso de herramientas como GitHub y Webex.

---

## 🏢 Departamentos Incluidos

1. **Desarrollo**
   - Encargado del diseño y programación de software.
   - Alta demanda de ancho de banda.

2. **Soporte Técnico**
   - Encargado de brindar asistencia a usuarios y mantenimiento de sistemas.

3. **Administración**
   - Gestión de recursos humanos, finanzas y operaciones internas.

---

## 🌐 Dirección IP y Subredes Asignadas

Supongamos que usamos la red base **192.168.10.0/24**. La segmentación sería:

| Departamento     | Subred              | Rango de IPs         | IP del Gateway     |
|------------------|---------------------|-----------------------|---------------------|
| Desarrollo       | 192.168.10.0/26     | 192.168.10.1 - 62     | 192.168.10.1        |
| Soporte Técnico  | 192.168.10.64/26    | 192.168.10.65 - 126   | 192.168.10.65       |
| Administración   | 192.168.10.128/26   | 192.168.10.129 - 190  | 192.168.10.129      |
| Servidores       | 192.168.10.192/28   | 192.168.10.193 - 206  | 192.168.10.193      |

---

## 👥 Roles y Responsabilidades del Equipo

| Nombre            | Rol en el Proyecto                         |
|-------------------|--------------------------------------------|
| [Nombre 1]        | Coordinador del proyecto                   |
| [Nombre 2]        | Diseñador de la red (Packet Tracer)        |
| [Nombre 3]        | Documentación y control de versiones (Git) |
| [Nombre 4]        | Encargado de comunicación (Webex)          |

*Cada integrante puede colaborar en distintas fases del proyecto y debe sincronizar sus avances mediante Git.*

---

## 🛠 Herramientas Utilizadas

- **Cisco Packet Tracer**: para el diseño y simulación de la red.
- **Git y GitHub**: para control de versiones y trabajo colaborativo.
- **Webex**: para reuniones, coordinación y revisión de avances.

---

## ✅ Estado del Proyecto

- [x] Repositorio creado en GitHub
- [ ] Red diseñada en Packet Tracer
- [ ] Archivo `.pkt` añadido al repositorio
- [ ] Reuniones realizadas por Webex
- [ ] Presentación final preparada
