# Afterglow 1.0 Community Edition 🩵

**A transparent, music-reactive Rainmeter desktop suite for Windows.**

Afterglow brings together a vinyl-style Spotify player, responsive audio visualizers, automatic album-art colors, weather, a clock, system monitoring, and a customizable theme studio.

## Download

**[Open Afterglow Releases](https://github.com/silentfox662/Afterglow-Rainmeter/releases)**

Download `Afterglow_1.0_Community.rmskin` from the latest published release's **Assets** section, then double-click it to install with Rainmeter.

> The first public release will appear here after the installer has been uploaded and the release has been published.

## Features

- **Vinyl player:** circular album art, rotating artist name, Spotify playback controls
- **Wave Bars:** thin, audio-reactive spectrum visualizer
- **Album Art / Auto:** accents change with the current Spotify album art, even when the Settings skin is closed
- **Frosted Glacier Blue:** `#B8DCE5` default/fallback accent
- **Weather:** configurable city or postal code, current weather, forecast, °F / °C
- **System tools:** clock, CPU/RAM statistics, network, Windows shortcuts
- **Studio:** color palettes, fonts, scaling, positioning, manual/automatic colors
- **Modular layout:** move and enable widgets independently

## Requirements

- Windows 10/11
- [Rainmeter](https://www.rainmeter.net/)
- [WebNowPlaying](https://wnp.keifufu.dev/rainmeter/getting-started) for Spotify metadata, artwork, and controls
- A compatible **Spicetify WebNowPlaying extension** for Spotify Desktop, or the supported browser integration
- Windows PowerShell 5.1 for local artwork color extraction
- Internet access for [Open-Meteo](https://open-meteo.com/) weather

The horizontal/circular visualizers use Rainmeter's audio output. **Third-party plugins and Spotify bridges are not bundled.**

## Quick start

1. Install Rainmeter and download the `.rmskin` installer from **Releases**.
2. Double-click the installer. Back up an earlier Afterglow skin before upgrading.
3. Load `Afterglow/Welcome/Welcome.ini` if the welcome screen does not open automatically.
4. Set your weather location and temperature units.
5. Connect Spotify through WebNowPlaying and your chosen supported bridge.
6. Open `Afterglow/Settings/Settings.ini` to choose **Album Art / Auto** or a manual palette.
7. Leave `Afterglow/Colors/Colors.ini` loaded for automatic album-art colors. Settings can be closed.

Automatic color extraction runs locally. It does not upload your album artwork. The fallback color is Frosted Glacier Blue.

## Help and feedback

If a widget is blank or isn't changing colors, check **Rainmeter → About → Log** and open a GitHub [issue](https://github.com/silentfox662/Afterglow-Rainmeter/issues) with the relevant error message and Afterglow version.

## Project status

Version 1.0 Community Edition. The creator has confirmed album-color updates working on their Windows setup. Wider clean-install and compatibility testing is still welcome.

**Note:** Artwork, fonts, wallpapers, and third-party plugins are not included. A source-code license has not yet been selected.
