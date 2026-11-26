# MSFS VFR Bridge Privacy Policy

MSFS VFR Bridge is a Microsoft Edge extension with a companion Windows application. It shows the position of a simulated aircraft on supported maps and adds route planning and flight logging on AirQuest and LPS.

## Position and local storage

The Windows companion reads flight position and aircraft telemetry from Microsoft Flight Simulator. Edge on Windows receives that information via Native Messaging. Edge on Android can connect to the companion over a user-configured private local network address. Aircraft telemetry is used for the moving-map display and flight log. It is not sent to a developer-operated server.

If you select Device GPS, the extension may ask the browser for permission to use your device location. You can revoke that permission in browser settings. If you choose camera pairing, the extension processes camera frames on your device to read the Windows Bridge QR code. It saves the decoded connection address and does not upload camera frames.

The extension stores preferences, the Bridge address, imported route data, aircraft performance profiles, route planning settings and flight logs locally. You can clear saved flight data using the extension controls or remove locally stored extension data by uninstalling the extension.

## Requests to external services

- **AirQuest** provides the selected route, aerodrome or waypoint data and airspace information. The extension uses the site's existing browser session when a requested route requires it. The extension does not collect or store account credentials. [AirQuest](https://v3.airquest.cz/)
- **Open-Meteo** receives planned route coordinates for terrain elevations and forecast winds. [Open-Meteo](https://open-meteo.com/)
- **Aviation Weather Center** receives airport codes or an approximate local search area to retrieve METAR information. [Aviation Weather Center](https://aviationweather.gov/)
- **LPS SR** provides the VFR Manual map and published documents for the optional Slovak circuit-height check. [LPS VFR Manual](https://gis.lps.sk/vfrm/)

Those services process requests under their own terms and policies. The developer does not sell personal data or use it for advertising.

## Contact

Contact the developer through the project listing on [Flightsim.to](https://flightsim.to/addon/119118/msfs-vfr-bridge-live-aircraft-tracking-for-msfs-2024).
