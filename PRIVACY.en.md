# NetScope Privacy Policy

23 November 2026 · Author: ivevkz

NetScope is free and requires no account. Network activity history stays on your computer. NetScope does not send it to the author or use advertising analytics.

## Data on your computer

NetScope stores preferences, traffic history and reports in %LOCALAPPDATA%\NetScope. Depending on the features you use, these can include application names and paths, byte counts, connection times, addresses and ports, host names from the DNS cache, network device identifiers and security events. Wi-Fi monitoring can use access point identifiers. IP country lookups use a database bundled with the app.

The installed Windows service temporarily stores pending traffic measurements locally in a protected ServiceData folder under the installation directory. The desktop app imports them into the existing history and acknowledges receipt. The service keeps up to 24 hours or 64 MB of pending measurements, whichever limit is reached first.

NetScope stores publisher certificate fingerprints locally to suggest moving block rules after signed updates. Windows may contact certificate validation services during verification. Daily adapter and application byte counts are also stored locally.

## External connections and sharing

• Updates. Manual and automatic checks contact GitHub Releases. GitHub and its delivery network receive ordinary request information, including your IP address. You can disable automatic updates under About.

• File checks. On request, NetScope sends a file’s SHA-256 hash to VirusTotal and includes your key for API requests. NetScope does not upload the file contents there. Windows encrypts the stored key for the current user. You can remove it in File checks. Microsoft Defender follows your Windows protection settings, including your cloud protection preferences.

• Speed tests. Participating servers, such as Cloudflare or LibreSpeed endpoints, see your IP address and exchange test data with the app. Server suggestions use the Windows region.

• Threat lists and device discovery. When enabled, NetScope downloads the Feodo Tracker address list and compares connections locally. Device discovery sends requests to devices on the selected local network.

• Exports and remote viewing. You choose the destination for exported reports. If you enable snapshot sharing, the selected folder receives the computer name, graph, connections and recent events. Folder permissions control access to these files. You can also enable writing security events to the Windows event log.

## Retention and contact

Choose how long to keep detailed history in General settings. Monthly reports are retained separately. To erase the local database and preferences, quit NetScope from the tray and delete %LOCALAPPDATA%\NetScope. Exports, shared snapshots, Windows event logs and firewall rules are managed separately.

Contact the author at https://github.com/ivevkz/NetScope/issues. Issues are public. Remove keys, private paths and network addresses before attaching files.
