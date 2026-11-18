# JuanFiV2-Portal

A customizable captive portal for **MikroTik Hotspot** integrated with **JuanFi**.

This repo contains the HTML pages, scripts, and configuration files needed to replace the default MikroTik hotspot portal with a JuanFi-ready portal.

## Features

- Custom hotspot pages: `login.html`, `alogin.html`, `rlogin.html`, `logout.html`, `status.html`, `redirect.html`, `error.html`
- JuanFi setup script: `juanfi-setup.rsc`
- Login/logout event scripts: `OnLogin.txt`, `OnLogout.txt`
- Config files: `api.json`, `settings.json`
- Assets and favicon for a branded portal

## Files

| File / Folder | Purpose |
|---|---|
| `*.html` | Hotspot portal pages served by MikroTik |
| `juanfi-setup.rsc` | RouterOS script for JuanFi setup |
| `OnLogin.txt` / `OnLogout.txt` | Scripts executed on hotspot login/logout |
| `api.json` / `settings.json` | Portal configuration |
| `assets/` | Images, CSS, and static resources |

## Quick Setup

1. Clone or download this repository.
2. Upload the portal files to your MikroTik hotspot HTML directory.
3. Run/import `juanfi-setup.rsc` to apply the required settings.
4. Set your hotspot to use the custom HTML directory.
5. Connect to your hotspot SSID and test the portal.

> ⚠️ Make sure your MikroTik user has full admin access for JuanFi e-loading to work properly.

## Related

- [JuanFi Official Site](https://juanfi.juansystems.com/)
- [JuanFi on GitHub](https://github.com/ivanalayan15/JuanFi)

## License

No license is specified in this repository. Please contact the repo owner for usage terms.
