# Privacy Policy for MSFS VFR Bridge

This policy describes how MSFS VFR Bridge for Microsoft Edge on Windows and Android handles information.

## Simulator telemetry

The extension receives simulated aircraft position and flight data from the separately installed Windows Bridge application. On Windows, this connection uses native messaging on the same computer. On Android, it uses HTTP to the Bridge address configured by the user on the local network.

The extension uses this data to display the aircraft, its recent flight trail and selected flight information on supported maps, and to operate the flight log. The developer does not receive this telemetry through the extension.

## Optional device location

When you select Device GPS, the extension requests location through the browser's geolocation API with your permission. Available information can include latitude, longitude, altitude, accuracy, heading and speed. It is used to display your device's location on the supported map.

You can stop this mode by changing the position source or disabling live position. Location permission can also be managed in the browser.

## Locally stored information

The extension stores information in Microsoft Edge's local extension storage. This includes display and language preferences, position source, local Bridge address, planned speed, terrain margin, imported route data, navigation information, flight-log records and the position of movable controls.

Flight-log records can be cleared using the extension's controls, and an imported route can be removed. Extension data can also be removed through the browser's extension-management facilities. The developer does not receive your stored settings, routes or flight logs through the extension.

## AirQuest routes and terrain elevations

When you request an AirQuest route import, the extension reads route and available navigation information from AirQuest, including waypoint coordinates and available airport, runway, frequency and airspace details. This information is used to display the imported route and its navigation information on LPS.

To obtain terrain elevations for imported waypoints, the extension sends those waypoint latitude and longitude coordinates to the Open-Meteo elevation API at api.open-meteo.com. As with other direct internet requests, the provider can receive your public IP address and standard request metadata. These requests are subject to the provider's privacy practices.

[Open-Meteo Privacy Policy](https://open-meteo.com/en/terms#privacy)

## QR connection setup

If you choose to scan a Bridge QR code, the extension requests camera access with your permission. Camera frames are processed on the device to read the connection address. The extension does not upload camera frames to the developer or an external QR-decoding service.

The extension checks the scanned Bridge connection and saves its local address for future connections.

## Supported websites

The extension runs on supported map pages and displays position and route information within those pages. Requests made by the websites themselves remain subject to their respective privacy policies. AirQuest route requests use the user's existing access to that service.

## Data use

The extension has no developer-operated telemetry or analytics collection service. The developer does not sell user data or use it for advertising, creditworthiness or lending decisions. Information processed by the extension is used to provide its mapping, connection, route and flight-log features.

## Contact

For privacy questions, contact the developer through the [MSFS Bridge listing on Flightsim.to](https://flightsim.to/addon/119118/msfs-vfr-bridge-live-aircraft-tracking-for-msfs-2024).

[Project information](project)
