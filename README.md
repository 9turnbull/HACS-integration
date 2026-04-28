# HACS (Home Assistant Community Store)

_Manage (Install, track, upgrade) and discover custom elements for Home Assistant directly from the UI._

## What?

HACS is an integration that gives the user a powerful UI to handle downloads of custom needs.

**Highlights of what HACS can do:**

- Help you discover new custom elements.
- Help you download new custom elements.
- Help you keep track of your custom elements.
  - Manage(download/update/remove)
  - Shortcuts to repositories/issue tracker

## Useful links

- [General documentation](https://hacs.xyz/)
- [Configuration](https://hacs.xyz/docs/use/configuration/basic)
- [FAQ](https://hacs.xyz/docs/faq)
- [GitHub](https://github.com/hacs)
- [Discord](https://discord.gg/apgchf8)
- [Become a GitHub sponsor? ❤️](https://github.com/sponsors/ludeeus)
- [BuyMe~~Coffee~~Beer? 🍺🙈](https://buymeacoffee.com/ludeeus)

## Local setup and connect (development)

### 1) Set up a local development environment

From the repository root, run:

```bash
./scripts/setup
```

This script installs Python requirements and frontend assets, then installs pre-commit hooks.

### 2) Start Home Assistant with HACS from this checkout

From the repository root, run:

```bash
./scripts/develop
```

This creates a local `config/` (if missing), enables useful logging for `custom_components.hacs`, and starts Home Assistant with this repository's `custom_components` on `PYTHONPATH`.

### 3) Connect HACS inside Home Assistant

1. Open Home Assistant in the browser.
2. Go to **Settings → Devices & Services**.
3. Click **Add Integration** and select **HACS**.
4. Complete the GitHub/device authorization flow shown by the HACS config flow.
5. After setup, open HACS from the sidebar and add repositories/categories as needed.

> Note: HACS connection/authorization is completed in the Home Assistant UI; it is not finalized purely from the command line.


## Issues

~~If~~ When you experience issues/bugs with this the best way to report them is to open an issue in **this** repo.

[Issue link](https://hacs.xyz/docs/help/issues)
