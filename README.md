# Universal-Scanner

## Features
- **Multi-Service Scanning**: Recursively scans Workspace, ReplicatedStorage, Lighting, SoundService, CoreGui, Players, StarterGui, and StarterPack with customizable category toggles.
- **Keyword Filtering**: Filter instances dynamically by name, class, path, values, or attributes on the fly.
- **Automated Asset Tracking**: Automatically isolates and extracts all `RemoteEvent`, `RemoteFunction`, `UnreliableRemoteEvent`, `LocalScript`, `ModuleScript`, and `Script` paths into dedicated summary sections.
- **Bytecode Decompilation**: Automatically decompiles scripts with live progress counters, error handling, and a dedicated subfolder structure.
- **Property & Attribute Inspector**: Extracts specific instance properties (like Position, Size, Material, and Transparency) alongside custom attributes and values.
- **Class Breakdown & Tree**: Generates a sorted class-type statistical tally alongside a clean instance hierarchy tree styled with clean connecting lines.
- **Clipboard Integration**: Auto-copies the generated dump folder path straight to your clipboard the second a scan completes.
- **Clean UI**: Minimalist, two-section layout (*Search & Filter* and *Export Settings*).

## Usage
```luau
loadstring(game:HttpGet('https://raw.githubusercontent.com/3heyem/Universal-Scanner/refs/heads/main/Scanner'))()
```
Press F5 to open the UI (this can be changed in the Settings tab).

## Support
Message @prodordie on Discord.
