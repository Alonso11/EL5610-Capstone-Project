# TI0IE4-7 Sistema de Rastreo de vehículos con Lora/APRS Tracker

This firmware is for using ESP32 based boards with LoRa Modules and GPS to live in the APRS world to track vehicles.

![Screenshot](https://github.com/Alonso11/EL5610-Capstone-Project/blob/main/Estructura%20del%20Proyecto/Aspectos%20T%C3%A9cnicos/LoRa_APRS_Tracker-2.2.4/images/tracker_grupo4.jpeg)

__(NOTE: To use Tx/Rx capabilities of this tracker you should have also an Tx/Rx <a href="https://github.com/richonguzman/LoRa_APRS_iGate" target="_blank">LoRa iGate</a> near you)__
<br />

____________________________________________________



# WEB FLASHER/INSTALLER is <a href="https://richonguzman.github.io/lora-tracker-web-flasher/installer.html" target="_blank">here</a>

____________________________________________________

- Tracker with complete MENU !!! (see Wiki to know how to access it)
    - Read, Write and Delete Messages (with I2C Keyboard or Phone).
    - Asking Weather Report.
    - Listening to other Trackers arround.
    - Changing Display Eco Mode (turn off after 4 seconds) and Screen Brightness.
- Processor from 240Mhz to 80MHz to save almost 20% power consumption.
- All GPS beacons/packets are encoded for less time on RF/LoRa Tx.
- Oled Screen shows Altitude+Speed+Course or BME280 Wx Data or Number of New Messages Received.
- Oled Screen shows Recent Heard Trackers/Station/iGates Tx.
- Bluetooth capabilities to connect (Android + APRSDroid) or (iPhone + APRS.fi app) and use it as TNC.
- Led Notifications for Tx and Messages Received.
- Sound Notifications with YL44 Buzzer Module.
- Wx data with BME280 Module showed on Screen and transmited as Wx Telemetry.
- Winlink Mails through APRSLink.
- Posibility to change between 3 major Frequencies used by LoRa APRS Worldwide.
____________________________________________________

# WIKI (English / Español)

### 1. Installation Guide --> <a href="https://github.com/richonguzman/LoRa_APRS_Tracker/wiki/01.-Installation-Guide-%23-Guia-de-Instalacion" target="_blank">here</a>

### 2. Tracker Configuration and Explanation for each setting --> <a href="https://github.com/richonguzman/LoRa_APRS_Tracker/wiki/02.-Tracker-Configuration--%23--Configuracion-del-Tracker" target="_blank">here</a>

### 3. Upload Firmware and Filesystem --> <a href="https://github.com/richonguzman/LoRa_APRS_Tracker/wiki/03.-Upload-Firmware-and-Filesystem-%23-Subir-Firmware-y-sistema-de-archivos" target="_blank">here</a>

### 4. Tracker Menu Guide --> <a href="https://github.com/richonguzman/LoRa_APRS_Tracker/wiki/04.-Menu-Guide-%23-Guía-del-menú" target="_blank">here</a>


____________________________________________________
## This code was based on the work of :
- https://github.com/richonguzman/LoRa_APRS_Tracker/wiki/01.-Installation-Guide-%23-Guia-de-Instalacion
- https://github.com/aprs434/lora.tracker : Serge - ON4AA on base91 byte-saving/encoding
- https://github.com/lora-aprs/LoRa_APRS_Tracker : Peter - OE5BPA LoRa Tracker
- https://github.com/Mane76/LoRa_APRS_Tracker : Manfred - DC2MH (Mane76) mods for multiple Callsigns and processor speed
- https://github.com/dl9sau/TTGO-T-Beam-LoRa-APRS : Thomas - DL9SAU for the Kiss <> TNC2 lib
____________________________________________________

