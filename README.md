# Shoko Relocation+ Plugin

A [Shoko](https://shokoanime.com/) plugin that relocates video extra files near the video files.

## Features

- **Relocates Extras** — Moves video extra files (e.g., trailers, extras) near the video files they belong to.
- **Background Service** — Runs as a hosted service within Shoko.

## Installation

### GUI (Recommended)

1. Open the Shoko Web UI and navigate to **Settings → Plugins → Repositories**.
2. Add the manifest URL:
   ```
   https://raw.githubusercontent.com/revam/dotnet-shoko-plugin-relocation-plus/stable/manifest.json
   ```
3. Go to **Server → Plugins → Browse** and find **Relocation+**.
4. Click **Install** on the desired version.
5. Restart Shoko.

### Manual

1. Download the latest `Shoko.Plugin.RelocationPlus-<version>-any.zip` from the [Releases](../../releases) page.
2. Extract the ZIP and place `Shoko.Plugin.RelocationPlus.dll` into your Shoko **Plugins** folder.
3. Restart Shoko.

## Building from Source

Requires the [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0).

```bash
dotnet restore
dotnet build --configuration Release
```

The compiled assembly will be located at `bin/Release/net10.0/Shoko.Plugin.RelocationPlus.dll`.

## License

This project is licensed under the MIT License.
