# HAUS Apps for Home Assistant

Home Assistant apps (add-ons) by HAUS.

## Install

[![Add the HAUS Apps repository to your Home Assistant.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fmedakstore%2Fhaus-ha-apps)

Or manually:

1. In Home Assistant go to **Settings → Apps → Install app**.
2. Open the **⋮** menu → **Repositories**, add `https://github.com/medakstore/haus-ha-apps`, and close the dialog.
3. Find **HAUS Agent** in the store, open it and click **Install**.
4. On the **Configuration** tab, enter the pairing code from the HAUS app
   (Settings → Remote access → HAUS Gateway), save, and **Start** the app.

## Apps

| App | Description |
|---|---|
| [HAUS Agent](haus_agent) | Connects this Home Assistant to the HAUS app through HAUS Cloud — securely, from anywhere, with no port forwarding. |

Supported: Home Assistant OS and Supervised installations on 64-bit ARM (Raspberry Pi 4/5), 32-bit ARM and x86-64 (mini PCs).
