# EL5610 - Taller Integrador - Proyecto - Gr4

## 🔗 Tabla de Contenidos

- [📍 Descripción](#descripción)
  
- [📁 Estructura del Proyecto](#structur)
  - [📂 Aspectos Técnicos](#especificación-del-módulo)  
  - [📂 Documentación](#configuración)  


- [📡 Teoría](#teoría)
  - [📘 APRS](#aprs)  
  - [⚙ Protocolo APRS](#protocolo-aprs)  


- [🤝 Agradecimientos](#agradecimientos)  
- [📑 Referencias](#referencias)

---

## 📍 Descripción
<a id="descripción"></a>

<details>
  <summary>📜 Descripción</summary>

  Este proyecto tiene como objetivo desarrollar un sistema de comunicaciones eléctricas basado en el protocolo APRS (Automatic Packet Reporting System) utilizando una ESP32.  

  APRS es un protocolo de comunicación digital utilizado en radioaficionados, monitoreo de activos y redes de sensores, permitiendo la transmisión de paquetes de datos a través de radiofrecuencia.  

  Este proyecto puede ser aplicado en el seguimiento de vehículos, estaciones meteorológicas, comunicaciones de emergencia y exploraciones en áreas remotas sin acceso a infraestructura de telecomunicaciones convencional.

</details>

---

## 📁 Estructura del Proyecto
<a id="structur"></a>

```
Estructura del Proyecto
│  
└───Documentación
│   │
│   └───Reporte
│   │   
│   └───Referencias_papers
│   
└───Aspectos Técnicos
    │       
    └───Especificación del Módulo
    │   README.md
    │   
    └───Configuración   
        │
        └───LoRa_APRS_Tracker-2.2.3

 README.md
```



<details>

<summary>📂 Aspectos Técnicos</summary>
<a id="especificación-del-módulo"></a>
Información relevante de la especificación y aplicación del proyecto.

</details>


<details>

<summary> 📂 Documentación</summary>
<a id="configuración"></a>

Archivos creados a lo largo de las etapas de diseño del proyecto.

</details>

---

## 📡 Teoría
<a id="teoría"></a>

<details>
  <summary>📘 APRS</summary>
  <a id="aprs"></a>
  APRS es un protocolo de comunicación digital utilizado para transmitir paquetes de datos a través de frecuencias de radio. Algunos usos incluyen:
  - Seguimiento en tiempo real de vehículos, barcos y aeronaves.
  - Comunicaciones de emergencia y operaciones de rescate.
  - Radioaficionados.
</details>

<details>
  <summary>⚙ Protocolo APRS</summary>
  <a id="protocolo-aprs"></a>
APRS está construido sobre el protocolo AX.25, este se encuentra en la capa 2 del modelo OSI (Data Link Layer). La comunicación se hace a través de paquetes llamados frames, APRS usa **Unnumbered Frame (U frame)**.

![image](https://github.com/user-attachments/assets/3abebb41-3f9a-4ae7-95fa-1a45c566eae7)

Ese paquete se modula, normalmente mediante **AFSK 1200 baud** o **PSK31**, y se transmite. Puede ser repetido por una estación **digipeater** o recibido por un **iGate**.

</details>


## 🤝 Agradecimientos
<a id="agradecimientos"></a>

<details>
  <summary>Mostrar Agradecimientos</summary>
  - Ricardo Guzman (CA2RXU)
</details>

---

## 📑 Referencias
<a id="referencias"></a>

<details>
  <summary>Mostrar Referencias</summary>
  
</details>
