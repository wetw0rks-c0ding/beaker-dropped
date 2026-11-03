# beaker-dropped

Public downloads for **Beakarr** — one Flutter app for your self-hosted
media stack on Android and iOS:

> Seerr, Sonarr, Radarr, Lidarr, Prowlarr, Bazarr, NZBGet, Nginx Proxy
> Manager, OpenMediaVault, Wizarr, qBittorrent, Navidrome and SoulSync,
> with Authentik single sign-on across the *arr fleet.

This repository hosts the installable builds and release notes only —
**no source code**. It exists so you can grab the app without needing
the development repo.

## Before you install — source availability

Beakarr is licensed **MIT**. The full source of the app, including this
release, lives at **https://github.com/wetw0rks-c0ding/Beakarr** — the
same code this binary was built from, per the MIT notice below
(`NOTICE.txt`). You have your usual MIT rights to that source: use,
copy, modify, merge, publish, distribute, sublicense and permit such
dealings.

## Install

1. Grab the latest files from [**Releases**](../../releases):
   - Android: `beakarr-<version>.apk`
   - iOS: `beakarr-<version>.ipa` (unsigned, for TrollStore sideloading —
     install via Files → Share → TrollStore)
2. Android: enable "install unknown apps" for your browser/file manager,
   then open the APK.
   - Updating over an older install requires the release signature to
     match; if you installed a debug/dev build side by side, uninstall it
     or use the dev channel from the source repo.
3. iOS: TrollStore signs at install time; no Apple account needed.

Release notes are attached to each release and in `docs/` if provided.

## Security / privacy

- Config (URLs, API keys) is stored on-device with `flutter_secure_storage`.
- No telemetry; no data leaves your network except to your own services.
- Nothing secret is distributed in these builds.

## License

MIT. Copyright (c) 2026 matthw-labs and Beakarr contributors.
Upstream [Seekarr by matthw-labs](https://github.com/matthw-labs/seekarr)
is credited; its license text is reproduced in `LICENSE`.

---

Issues/support: file them on the source repository —
[wetw0rks-c0ding/Beakarr](https://github.com/wetw0rks-c0ding/Beakarr).
Do not report credentials or personal data in public issues.
