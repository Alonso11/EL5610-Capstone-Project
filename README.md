# EL5610 - Taller Integrador - Proyecto - Gr4

## 🔗 Tabla de Contenidos

- [📍 Descripción](#descripción)
  
- [📁 Estructura del Proyecto](#structur)
  - [📂 Aspectos Técnicos](#especificación-del-módulo)  
  - [📂 Documentación](#configuración)  


- [📡 Teoría](#teoría)
  - [📘 APRS](#aprs)  
  - [⚙ LoRa](#protocolo-aprs)  
  - [⚖️ Legislación](#legis)

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


  **Protocolos que utiliza APRS**

  APRS está construido sobre el protocolo AX.25, este se encuentra en la capa 2 del modelo OSI (Data Link Layer). La comunicación se hace a través de paquetes llamados frames, APRS usa **Unnumbered Frame (U frame)**.

![image](https://github.com/user-attachments/assets/3abebb41-3f9a-4ae7-95fa-1a45c566eae7)

Ese paquete se modula, normalmente mediante **AFSK 1200 baud** o **PSK31**, y se transmite. Puede ser repetido por una estación **digipeater** o recibido por un **iGate**.
</details>

<details>
  
  <summary>⚙LoRa</summary>
  <a id="protocolo-aprs"></a>
**¿Qué es?** 
Protocolo de cumunicacion queue utiliza
a proprietary spread spectrum modulation that is similar to
and a derivative of chirp spread spectrum (CSS) modulation.
Each symbol is represented by a cyclic shifted chirp over the
bandwidth centered around the base frequency. The spreading
factor (SF) is a selectable radio parameter from 5 to 12[13] and
represents the number of bits sent per symbol and in addition
determines how much the information is spread over time.



</details>




<details>
  
  <summary>⚖️ Legislación</summary>
  <a id="legis"></a>


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
  [1] R. C. Capitol, “Formación aprs,” 2025. [Online]. Available: https://www.radioclubcapitol.es/formacion/aprs


  
[2] U. F. do Rio Grande do Sul, “Cac - computador analógico e computador
digital,” s.f. [Online]. Available: http://penta2.ufrgs.br/tp951/cac pro.html


[3] P. G. de la República de Costa Rica, “Normativa y
legislación - artículo específico,” 2023. [Online]. Available:
http://www.pgrweb.go.cr/scij/Busqueda/Normativa/Normas/nrm articulo.
aspx?param1=NRA&nValor1=1&nValor2=99551&nValor3=136249&
nValor4=-1&nValor5=2&nValor6=16/03/2023&strTipM=FA


[4] MICITT, “Permisos y concesiones de telecomunicaciones,” 2025. [Online]. Available: https://www.micitt.go.cr/tramites/
permisos-y-concesiones-de-telecomunicaciones


[5] Wikipedia contributors, “Tipos de emisiones de radio,” 2025. [Online].
Available: https://es.wikipedia.org/wiki/Tipos de emisiones de radio


[6] L. Antenna. (2024) Lorawan frequency plans by
country/region. [Online]. Available: https://www.loraantenna.com/es/
lorawan-frequency-plans-by-country-region/


[7] R. C. Rica, “Plan nacional de atribución de frecuencias,”
2020. [Online]. Available: https://www.radioaficioncr.net/2020/06/
plan-nacional-atribucion-de-frecuencias.html


[8] T. T. Network, “Lorawan regional parameters - us915,” 2022.
[Online]. Available: https://www.thethingsnetwork.org/docs/lorawan/
regional-parameters/us915/
</details>
