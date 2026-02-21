# LaSearch

**Find anything, anywhere.** A fast, private search engine that runs entirely on your device.

LaSearch indexes your local files and lets you search them using natural language. No cloud, no data collection — everything stays on your machine.

![macOS](https://img.shields.io/badge/macOS-Apple%20Silicon-purple) ![Version](https://img.shields.io/badge/version-0.4.4-blue) ![Beta](https://img.shields.io/badge/status-beta-orange)

## Download

**[Download for macOS (Apple Silicon)](https://github.com/7sedam7/lasearch/releases/latest/download/lasearch_aarch64.dmg)** — more platforms coming soon.

## How It Works

LaSearch lives in your menu bar and is summoned with a global keyboard shortcut. Type your query and results appear instantly — powered by a search engine that understands context and meaning, not just keywords.

### Spaces

A **Space** is a searchable collection of files. Create a space, point it at one or more folders, and LaSearch indexes everything inside.

- Organize your files into logical groups (e.g., "Work Documents", "Photos", "Code Projects")
- Each space is indexed independently
- Filter search to specific spaces with `@`
- More sources beyond local folders (email, cloud storage, etc.) are coming soon

### Search

Just type and results stream in as they're found.

- **Smart search** — goes beyond simple keyword matching to understand what you're looking for
- **Filename matching** — fuzzy matching on file and folder names
- **`@spacename`** — filter results to one or more specific spaces
- **Real-time results** — results appear as they're found, no waiting

### Commands

Type `/` to access commands:

| Command | Description |
|---------|-------------|
| `/space new` | Create a new space |
| `/space <name>` | View space details |
| `/theme` | Change UI theme (with color previews) |
| `/hotkey` | Configure global keyboard shortcut |
| `/update application` | Check for updates |
| `/logs` | View application logs |
| `/help` | Show help |
| `/exit` | Exit LaSearch |

### Supported File Types

LaSearch can index and search a wide range of file types:

- **Documents** — PDF, DOCX, XLSX, PPTX, ODT, EPUB, HTML
- **Text & Code** — TXT, MD, JSON, YAML, CSV, and 20+ programming languages
- **Email** — EML, MSG
- **Media** — images, audio, and video (metadata for now, OCR, STT, etc coming soon)
- **Archives** — ZIP, TAR, 7Z, RAR (currently disabled)

## Privacy

LaSearch never sends your data anywhere. Search indices are built and stored locally. The only network requests the app makes are checking for updates (via GitHub). When online service integrations (email, cloud storage) are added, they will connect directly to the service provider — no data will ever pass through LaSearch servers.

See the full [Privacy Policy](https://lasearch.app/privacy-policy).

## Pricing

LaSearch is completely free for now. When paid options are introduced down the road, they'll be around convenience features. Any version released as free stays free forever.

## Transparency

- Third-party licenses are included in the app bundle
- SBOMs: [Cargo](https://github.com/7sedam7/lasearch/releases/latest/download/lasearch-cargo.cdx.json) · [NPM](https://github.com/7sedam7/lasearch/releases/latest/download/lasearch-npm.cdx.json)

## Feedback

This is an early beta — feedback is hugely appreciated.

- [Open an issue](https://github.com/7sedam7/lasearch/issues)
- [Send an email](mailto:joel@lasearch.app)

## Links

- **Website** — [lasearch.app](https://lasearch.app)
- **Live Demo** — [epstein.lasearch.app](https://epstein.lasearch.app) (1.4M documents)
- **Privacy Policy** — [lasearch.app/privacy-policy](https://lasearch.app/privacy-policy)
- **Terms of Service** — [lasearch.app/terms-of-service](https://lasearch.app/terms-of-service)
