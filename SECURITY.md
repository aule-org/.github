# Security and privacy policy

Capricorn is used by children, so we treat privacy problems as security problems.

## Reporting

Email **admin@meetaule.com** with a description, the affected repository and version, and steps to reproduce. Please do not open a public issue, and never post device IDs, MAC addresses, tokens, Wi-Fi details or recordings anywhere public.

We acknowledge reports within 3 working days and keep you updated until the problem is fixed. If you would like credit, say so and we will name you in the fix.

## In scope

- [capricorn-fw](https://github.com/aule-org/capricorn-fw): anything that sends audio or identifiers without the user's intent, bypasses the hardware microphone mute, or weakens updates or device credentials.
- [capricorn-sw](https://github.com/aule-org/capricorn-sw): access to another family's data or a child's audio, account takeover, token leaks.
- [capricorn-app](https://github.com/aule-org/capricorn-app): exposure of a child's data on the phone or in transit.
- [capricorn-hw](https://github.com/aule-org/capricorn-hw): designs that could hurt a child: battery, heat, small parts, sharp edges.

Problems in [xiaozhi-esp32](https://github.com/78/xiaozhi-esp32) or [LiveKit](https://github.com/livekit) that are not specific to Capricorn should also be reported to those projects.
