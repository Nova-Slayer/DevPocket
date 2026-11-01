# DevPocket

**A lightweight, offline-first developer toolkit by Nova Slayer.**

DevPocket brings useful developer utilities into one simple interface. It is designed to run locally in a browser, with an Android APK distributed through GitHub Releases.

> **Status:** Active development  
> **Creator:** Chandan Kumar · Nova Slayer

## Features

- 150 developer tools in one interface
- Organized navigation for easier tool discovery
- Responsive layout for mobile and desktop
- Lightweight interface and smooth interactions
- Offline support for tools that run locally
- Web version distributed as a standalone HTML file
- Android APK distribution through GitHub Releases

**Offline note:** Local tools can work without an internet connection. Tools that rely on external APIs, remote services, or online resources require internet access.

## Download and use

### Web version

1. Download the standalone HTML file from the repository.
2. Open it in a modern browser.
3. Use locally supported tools without hosting a server.

### Android APK

Get the latest APK from **[GitHub Releases](../../releases)**.

1. Open the latest release.
2. Download the APK asset.
3. Install it on your Android device. You may need to allow installation from your browser or file manager.

Only install APKs published in this repository's official Releases.

## Suggested repository structure

```text
DevPocket/
├── README.md
├── LICENSE
├── .gitignore
├── web/
│   └── DevPocket_NovaSlayer_150Tools_Navigation.html
├── android/
│   └── README.md
└── assets/
    ├── screenshots/
    └── branding/
```

- `web/` — standalone HTML version
- `android/` — Android wrapper/source project, if published
- `assets/screenshots/` — screenshots for documentation
- `assets/branding/` — logo and project artwork

If you are publishing only the APK and not the Android source, omit the `android/` folder until you have source files to include.

## Releases and versioning

Use GitHub Releases for stable APK builds.

Suggested version format:

- `v1.0.0` — first stable release
- `v1.0.1` — patch or bug-fix release
- `v1.1.0` — backward-compatible feature release
- `v2.0.0` — major update

Each release should include the version, release date, APK asset, changes, known issues, and minimum Android version (if applicable).

**Example release title:** `DevPocket v1.0.0`

## Security and privacy

- DevPocket is designed to process data locally wherever possible.
- Avoid entering sensitive information unless you understand how the selected tool handles it.
- Tools that connect to third-party services may send data to those services.
- Review Android permissions before installing.
- Report security issues privately to the maintainer.

## Contributing

Bug reports, feature suggestions, and contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make and test your changes.
4. Open a pull request with a clear description.

For bug reports, include your device/OS, browser or Android version, reproduction steps, expected and actual behavior, and screenshots/logs when useful.

## Contact

- **Creator:** Chandan Kumar · Nova Slayer
- **Email:** chandansharma35831@gmail.com
- **Discord:** https://discord.gg/VTU9XYJeqR

## Credits

Made with ❤️ by **Nova Slayer (Chandan Kumar)**.

If you find DevPocket useful, consider starring the repository ⭐
