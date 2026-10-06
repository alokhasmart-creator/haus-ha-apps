# HAUS Agent

Connects this Home Assistant to the **HAUS app** so you can control your home
from anywhere. The connection is outbound only — nothing on your network is
exposed and no port forwarding is needed. Your devices, history and
automations stay in Home Assistant.

## Setup

1. In the HAUS app, open your home and generate a **pairing code**
   (valid for 10 minutes, usable once).
2. Enter it on this add-on's **Configuration** tab as `pairing_code` and save.
3. Start (or restart) the add-on. The log shows `agent_online` when connected.

To move your home to a new Home Assistant, pair the new one with a fresh
code — the old one is disconnected automatically.

## Options

| Option | Description |
|---|---|
| `pairing_code` | One-time code from the HAUS app. Can be left in place after pairing. |
| `api_url` | HAUS Cloud address. Leave the default unless told otherwise. |
| `log_level` | `info` by default; `debug` for troubleshooting. |
