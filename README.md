# Home Assistant Configs & Automationen 🏠

Nützliche Home Assistant YAML-Konfigurationen, Automationen und Blueprints aus dem Blog [smarthome-praxis.de](https://smarthome-praxis.de).

Alle Configs sind praxisnah und getestet — für Einsteiger und Fortgeschrittene.

---

## Inhalt

| Datei | Beschreibung | Tutorial |
|-------|-------------|---------|
| [automations/heizung_fenster.yaml](automations/heizung_fenster.yaml) | Heizung bei offenem Fenster abschalten | [→ Artikel](https://smarthome-praxis.de/smart-home-geraete/heizung-home-assistant-thermostat/) |
| [automations/anwesenheit.yaml](automations/anwesenheit.yaml) | Anwesenheitserkennung mit Personen-Tracking | [→ Artikel](https://smarthome-praxis.de/home-assistant/home-assistant-automationen-erstellen/) |
| [automations/zigbee_bewegung.yaml](automations/zigbee_bewegung.yaml) | Licht per Bewegungsmelder schalten | [→ Artikel](https://smarthome-praxis.de/smart-home-grundlagen/beste-zigbee-bewegungsmelder-2026/) |
| [automations/shelly_schalter.yaml](automations/shelly_schalter.yaml) | Shelly 1 Mini als Smart-Schalter | [→ Artikel](https://smarthome-praxis.de/smart-home-geraete/shelly-1-mini-gen3-einrichten/) |
| [automations/zigbee_steckdose.yaml](automations/zigbee_steckdose.yaml) | Steckdose nach Zeitplan steuern | [→ Artikel](https://smarthome-praxis.de/ratgeber/beste-zigbee-steckdosen/) |
| [automations/benachrichtigung.yaml](automations/benachrichtigung.yaml) | Push-Benachrichtigung bei Ereignissen | [→ Artikel](https://smarthome-praxis.de/home-assistant/home-assistant-automationen-erstellen/) |

---

## Voraussetzungen

- Home Assistant (empfohlen: aktuelle Version)
- Für Zigbee-Automationen: [Zigbee2MQTT](https://smarthome-praxis.de/zigbee2mqtt-einrichten/) oder [ZHA](https://smarthome-praxis.de/zha-vs-zigbee2mqtt/)
- Für Shelly: [Shelly Integration](https://smarthome-praxis.de/shelly-1-mini-gen3-einrichten/)

---

## Installation

1. YAML-Datei herunterladen
2. In Home Assistant: **Einstellungen → Automationen → Automation importieren**
3. YAML einfügen → Speichern
4. Entitäts-Namen an deine Geräte anpassen

---

## Mehr Tutorials

Ausführliche Anleitungen zu allen Themen auf **[smarthome-praxis.de](https://smarthome-praxis.de)**:

- [Home Assistant auf Raspberry Pi installieren](https://smarthome-praxis.de/home-assistant/home-assistant-raspberry-pi-installieren/)
- [Zigbee2MQTT einrichten](https://smarthome-praxis.de/home-assistant/zigbee2mqtt-einrichten/)
- [Matter & Thread 2026](https://smarthome-praxis.de/smart-home-grundlagen/matter-thread-smart-home/)
- [Smart Home absichern](https://smarthome-praxis.de/smart-home-grundlagen/smart-home-absichern-sicherheit/)
- [Node-RED in Home Assistant](https://smarthome-praxis.de/home-assistant/node-red-home-assistant/)

---

## Lizenz

MIT — frei verwendbar und anpassbar.
