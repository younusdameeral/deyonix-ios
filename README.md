# Deyonix – iPhone app

- `www/` – the Deyonix app (same files as the Netlify website)
- `resources/` – app icon (1024×1024) and splash screen
- `capacitor.config.json` – app id `comdameeral.deyonix`, name Deyonix
- `codemagic.yaml` – Codemagic builds the app on a Mac and sends it to TestFlight

To update the app: replace the files in `www/` and start a new build in Codemagic.
