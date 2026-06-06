# Zigbee2MQTT Setup — Tipps & Stolperfallen

Gesammelte Praxis-Notizen zur Einrichtung von Zigbee2MQTT in Home Assistant.

Vollständige Anleitung: **https://smarthome-praxis.de/home-assistant/zigbee2mqtt-einrichten/**

---

## Empfohlene Koordinatoren 2026

| Koordinator | Chip | Empfehlung |
|------------|------|-----------|
| SONOFF Zigbee 3.0 USB Dongle Plus (ZBDongle-P) | CC2652P | Beste Wahl für Einsteiger |
| SONOFF Zigbee 3.0 USB Dongle Plus-E (ZBDongle-E) | EFR32MG21 | Zukunftssicher (Matter) |
| Home Assistant SkyConnect | EFR32MG21 | Für HA-Nutzer ideal |

Vergleich aller Koordinatoren: **https://smarthome-praxis.de/smart-home-grundlagen/beste-zigbee-koordinatoren-2026/**

---

## Häufige Fehler

### Dongle wird nicht erkannt
```bash
# USB-Geräte auflisten
ls /dev/ttyUSB* /dev/ttyACM*

# Bei Docker: Gerät einbinden
--device /dev/ttyUSB0:/dev/ttyUSB0
```

### Geräte pairen nicht
- Zigbee2MQTT muss im Permit-Join-Modus sein
- Gerät nah am Koordinator halten beim Pairing
- Zigbee-Netz braucht Router-Geräte für größere Reichweite

### ZHA vs Zigbee2MQTT — was nehmen?
Ausführlicher Vergleich: **https://smarthome-praxis.de/zigbee-z-wave/zha-vs-zigbee2mqtt/**

---

## Nützliche Zigbee-Geräte

- Beste Zigbee-Steckdosen: https://smarthome-praxis.de/ratgeber/beste-zigbee-steckdosen/
- Beste Zigbee-Sensoren: https://smarthome-praxis.de/zigbee-z-wave/zigbee-sensor-home-assistant/
- Beste Zigbee-Lampen: https://smarthome-praxis.de/ratgeber/beste-zigbee-lampen-2026/
- Beste Zigbee-Bewegungsmelder: https://smarthome-praxis.de/smart-home-grundlagen/beste-zigbee-bewegungsmelder-2026/
