.
├── Aspectos Técnicos
│   └── LoRa_APRS_Tracker-2.2.3
│       ├── common_settings.ini
│       ├── data
│       │   └── tracker_conf.json
│       ├── data_embed
│       │   ├── bootstrap.css
│       │   ├── bootstrap.js
│       │   ├── favicon.png
│       │   ├── index.html
│       │   ├── script.js
│       │   └── style.css
│       ├── extra
│       │   └── turn_slope_calculations.xlsx
│       ├── images
│       │   ├── github-sponsors.png
│       │   ├── OledScreen2.jpeg
│       │   ├── paypalme.png
│       │   ├── Web001-Beacons.png
│       │   ├── Web002-StationConfig.png
│       │   ├── Web003-Display.png
│       │   ├── Web004-LoRa.png
│       │   ├── Web005-WxTelemetry.png
│       │   ├── Web006-Bluetooth.png
│       │   ├── Web007-Battery.png
│       │   ├── Web008-Notifications.png
│       │   ├── Web009-PttTrigger.png
│       │   ├── Web010-Winlink.png
│       │   ├── Web011-WiFiAP.png
│       │   └── WebFlasherTrackerGithub.png
│       ├── include
│       │   ├── battery_utils.h
│       │   ├── ble_utils.h
│       │   ├── bluetooth_utils.h
│       │   ├── button_utils.h
│       │   ├── configuration.h
│       │   ├── custom_characters.h
│       │   ├── custom_colors.h
│       │   ├── display.h
│       │   ├── gps_utils.h
│       │   ├── joystick_utils.h
│       │   ├── keyboard_utils.h
│       │   ├── kiss_utils.h
│       │   ├── lora_utils.h
│       │   ├── menu_utils.h
│       │   ├── msg_utils.h
│       │   ├── notification_utils.h
│       │   ├── power_utils.h
│       │   ├── sleep_utils.h
│       │   ├── smartbeacon_utils.h
│       │   ├── station_utils.h
│       │   ├── touch_utils.h
│       │   ├── utils.h
│       │   ├── web_utils.h
│       │   ├── wifi_utils.h
│       │   ├── winlink_utils.h
│       │   └── wx_utils.h
│       ├── LICENSE
│       ├── platformio.ini
│       ├── README.md
│       ├── src
│       │   ├── battery_utils.cpp
│       │   ├── ble_utils.cpp
│       │   ├── bluetooth_utils.cpp
│       │   ├── button_utils.cpp
│       │   ├── configuration.cpp
│       │   ├── display.cpp
│       │   ├── gps_utils.cpp
│       │   ├── joystick_utils.cpp
│       │   ├── keyboard_utils.cpp
│       │   ├── kiss_utils.cpp
│       │   ├── LoRa_APRS_Tracker.cpp
│       │   ├── lora_utils.cpp
│       │   ├── menu_utils.cpp
│       │   ├── msg_utils.cpp
│       │   ├── notification_utils.cpp
│       │   ├── power_utils.cpp
│       │   ├── sleep_utils.cpp
│       │   ├── smartbeacon_utils.cpp
│       │   ├── station_utils.cpp
│       │   ├── touch_utils.cpp
│       │   ├── utils.cpp
│       │   ├── web_utils.cpp
│       │   ├── wifi_utils.cpp
│       │   ├── winlink_utils.cpp
│       │   └── wx_utils.cpp
│       ├── tools
│       │   └── compress.py
│       └── variants
│           ├── esp32_c3_DIY_LoRa_GPS
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── esp32_c3_DIY_LoRa_GPS_915
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ESP32_DIY_1W_LoRa_GPS
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ESP32_DIY_1W_LoRa_GPS_915
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ESP32_DIY_1W_LoRa_GPS_LLCC68
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ESP32_DIY_LoRa_GPS
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ESP32_DIY_LoRa_GPS_915
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ESP32S3_DIY_LoRa_GPS
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ESP32S3_DIY_LoRa_GPS_915
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── F4GOH_1W_LoRa_Tracker
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── heltec_ht-ct62_GPS
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── heltec-lora32-v2_GPS
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── heltec-lora32-v2_GPS_915
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── heltec-lora32-v2_TNC
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── heltec_wifi_lora_32_v3_2_GPS
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── heltec_wifi_lora_32_v3_2_TNC
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── heltec_wifi_lora_32_v3_GPS
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── heltec_wifi_lora_32_v3_TNC
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── heltec_wireless_stick_lite_v3_GPS_display
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── heltec_wireless_tracker
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── OE5HWN_MeshCom
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── QRPLabs_LightTracker_Plus_1_0
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── TROY_LoRa_APRS
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ttgo_t_beam_s3_SUPREME_v3
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ttgo-t-beam-v0_7
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ttgo-t-beam-v1
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ttgo-t-beam-v1_2
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ttgo-t-beam-v1_2_915
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ttgo-t-beam-v1_2_SX1262
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ttgo-t-beam-v1_915
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ttgo-t-beam-v1_SX1268
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ttgo_t_deck_GPS
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ttgo_t_deck_plus
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ttgo-t-lora32-v2_1_GPS
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ttgo-t-lora32-v2_1_GPS_915
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ttgo-t-lora32-v2_1_TNC
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           ├── ttgo-t-lora32-v2_1_TNC_915
│           │   ├── board_pinout.h
│           │   └── platformio.ini
│           └── Wemos_ESP32_Bat_LoRa_GPS
│               ├── board_pinout.h
│               └── platformio.ini
├── Documentación
│   ├── Cronograma
│   ├── Referencias_papers
│   │   ├── sensors-21-00338-v3.pdf
│   │   ├── sensors-23-08859.pdf
│   │   ├── sensors-24-01801.pdf
│   │   ├── sensors-25-08859.pdf
│   │   └── sensors-26-08859.pdf
│   └── Reporte
└── project_structure.md

52 directories, 161 files
