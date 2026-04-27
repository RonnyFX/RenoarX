<div align="center">

# RenoarX

**Modern WinUI3 client built on [Xray-core](https://github.com/XTLS/Xray-core)**

</div>

## Downloads

### Windows

| Architecture | Installer |
|:-------------|:----------|
| x64 | [Setup EXE](https://github.com/RonnyFX/RenoarX/releases)

## Features
- **Modern UI** -- based on the winui3 framework
- **Fully powered by XRay-core technologies** -- xray tun, xray json with zero override
- **Notifications in headers** -- you can send notifications to your users right in the app

## Notifications usage
```bash
renoarx-notification: json or base64 format
```
Example in json before decode:
```json
{
  "id": "1",
  "severity": "warning",
  "title": "Technical works",
  "message": "Today from 1pm to 3am some servers may be slow.",
  "actionText": "Support",
  "actionUrl": "https://t.me/yoursupport",
  "expiresAt": "2026-04-28T00:00:00Z"
}
```
</details>
