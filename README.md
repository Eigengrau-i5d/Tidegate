# Tidegate

Paddle route planning for New Zealand waters. Pick a launch and a destination, choose your craft (sea kayak, SUP, rec kayak or canoe, rowing or outrigger), and Tidegate finds a route over water around land. It weighs every departure time against forecast tidal and ocean currents, wind, gusts and waves, and shows when to leave so the water works for you.

> **Planning aid only. Not for navigation.** Check official forecasts (MetService marine) and conditions on the day.

## Use it

- **Tidegate Web** (phones and browsers, nothing to install): <https://diffraction-works.github.io/Tidegate/>. On a phone, add it to your Home Screen to use it like an app and to open it offline.
- **Tidegate Desktop** (Windows): download `Tidegate-Setup-<version>-x64.exe` (installer) or `Tidegate-<version>-win-x64.zip` (portable) from [Releases](../../releases). The build is not code-signed, so Windows SmartScreen may warn. Choose **More info**, then **Run anyway**. Check the download against `SHA256SUMS.txt`.

Your saved trips stay on your own device. On the web they live in the browser, which can clear them, so use **Export trips** now and then to keep a copy.

## Network use

Tidegate only contacts `api.open-meteo.com` (wind), `marine-api.open-meteo.com` (currents and waves) and `tiles.openfreemap.org` (the map). There is no telemetry and there are no accounts.

## Credits

- Weather and ocean data by [Open-Meteo.com](https://open-meteo.com/) (CC BY 4.0).
- Map © OpenFreeMap, © OpenMapTiles, © OpenStreetMap contributors.
- Land data © OpenStreetMap contributors (ODbL).
- Tide predictions sourced from Land Information New Zealand (LINZ), Crown Copyright Reserved.

See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for the open-source components Tidegate includes.

## Licence

Copyright © 2026 Diffraction Works. All rights reserved. This repository holds release files only; the source code is not published. See [LICENSE](LICENSE).
