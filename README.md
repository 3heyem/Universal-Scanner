# Universal-Scanner

## Features
- **Multi-Service Scanning**: Recursively scans Workspace, ReplicatedStorage, Lighting, SoundService, CoreGui, and Players with customizable category toggles.
- **Keyword Filtering**: Filter instances dynamically by name, class, path, values, or attributes on the fly.
- **Automated Asset Tracking**: Automatically isolates and extracts all `RemoteEvent`, `RemoteFunction`, `UnreliableRemoteEvent`, `LocalScript`, and `ModuleScript` paths into dedicated summary sections.
- **Class Breakdown & Tree**: Generates a sorted class-type statistical tally alongside a clean, indented instance hierarchy tree.
- **Clipboard Integration**: Auto-copies the generated log file path straight to your clipboard the second a scan completes.
- **Clean UI**: Minimalist, two-section layout (*Search & Filter* and *Export Settings*).

## Usage
```
loadstring(game:HttpGet('https://raw.githubusercontent.com/3heyem/Universal-Scanner/refs/heads/main/Scanner'))()

Open the menu (F5), configure your filters and options, and hit Run Scanner. Dumps are saved directly to your workspace folder at C:\matcha\workspace\Universal Scanner\.
