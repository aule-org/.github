## Capricorn · the open-source AI tutor for kids

<p align="center">
  <img src="https://raw.githubusercontent.com/aule-org/capricorn-hw/main/hardware/enclosure/view.png" alt="Capricorn: a 7.5-inch e-ink tutor on a folding desk dock" width="420">
</p>

Every child deserves a patient tutor. **Capricorn** is one you can inspect, build and run yourself: a calm e-ink device that listens and talks, firmware on open standards, a server you can host, and an app for the family. No feed, no ads, no glowing screen.

| Repository | What you'll find |
|---|---|
| [capricorn-hw](https://github.com/aule-org/capricorn-hw) | ESP32-S3 board, 7.5" e-ink touch display, voice with echo cancellation, hardware mic mute. KiCad 10, JLCPCB-ready files, 3D-printable dock |
| [capricorn-fw](https://github.com/aule-org/capricorn-fw) | ESP32-S3 firmware built on [xiaozhi-esp32](https://github.com/78/xiaozhi-esp32) with a [LiveKit](https://livekit.io) transport. Builds on every commit |
| [capricorn-sw](https://github.com/aule-org/capricorn-sw) | Self-hosted server: LiveKit Agents voice tutor, device activation and updates, family API |
| [capricorn-app](https://github.com/aule-org/capricorn-app) | Family app: setup over Bluetooth, progress, privacy controls |

### For builders

1. **Order the board.** Gerbers, BOM and placement files are ready for JLCPCB: about US$66 per assembled board in a batch of five ([BOM](https://github.com/aule-org/capricorn-hw/blob/main/bom/README.md)).
2. **Print the dock.** Seven PETG parts, about 13.5 hours ([enclosure](https://github.com/aule-org/capricorn-hw/blob/main/hardware/enclosure/README.md)).
3. **Flash the firmware** from the [CI builds](https://github.com/aule-org/capricorn-fw/actions). It connects to the [server](https://github.com/aule-org/capricorn-sw), which is not live yet; browser flashing is on the way too.
4. **Tell us how it went.** Capricorn is a prototype; your build report is the most useful contribution there is.

### Children first

A hardware microphone mute the firmware cannot override. Parental consent. Children's data is never used to train models. Report privacy or security problems to admin@meetaule.com ([policy](https://github.com/aule-org/.github/blob/main/SECURITY.md)).

Made in Lima, Peru · [meetaule.com](https://meetaule.com)
