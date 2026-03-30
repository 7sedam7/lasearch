# LaSearch

**Find anything, anywhere.** A fast, private search engine that runs entirely on your device.

LaSearch indexes your local files and lets you search them using natural language. No cloud, no data collection — everything stays on your machine.

![macOS](https://img.shields.io/badge/macOS-Apple%20Silicon-purple) ![macOS](https://img.shields.io/badge/macOS-Intel-purple) ![Version](https://img.shields.io/badge/version-0.5.1-blue) ![Beta](https://img.shields.io/badge/status-beta-orange) [![Discord](https://img.shields.io/badge/Discord-community-5865F2?logo=discord&logoColor=white)](https://discord.gg/F5RE5ErKw)

## Download

- **[Download for macOS (Apple Silicon)](https://github.com/7sedam7/lasearch/releases/latest/download/lasearch_aarch64.dmg)**
- **[Download for macOS (Intel)](https://github.com/7sedam7/lasearch/releases/latest/download/lasearch_x86_64.dmg)**
- **Windows** — build available for testing on request via [Discord](https://discord.gg/F5RE5ErKw)

## How It Works

LaSearch lives in your menu bar and is summoned with a global keyboard shortcut. Type your query and results appear instantly — powered by a search engine that understands context and meaning, not just keywords.

### Sources

A **Source** is something LaSearch can index and search. Add a source and LaSearch indexes everything inside.

- **Local folders** — point at any directory on your machine (e.g., your Obsidian vault, a project folder, Downloads). The source name is the folder name.
- **Gmail** — connect a Gmail account to search your email (currently in beta — request access on [Discord](https://discord.gg/F5RE5ErKw)). The source name is the email address.
- More source types (cloud storage, etc.) are coming soon
- Each source is indexed independently
- Filter search to specific sources with `@`

### Search

Just type and results stream in as they're found.

- **Smart search** — goes beyond simple keyword matching to understand what you're looking for
- **Filename matching** — fuzzy matching on file and folder names
- **`@sourcename`** — filter results to one or more specific sources
- **Real-time results** — results appear as they're found, no waiting

### Commands

Type `/` to access commands:

| Command | Description |
|---------|-------------|
| `/source add` | Add a new source |
| `/source <name>` | View source details |
| `/theme` | Change UI theme (with color previews) |
| `/hotkey` | Configure global keyboard shortcut |
| `/update application` | Check for updates |
| `/logs` | View application logs |
| `/help` | Show help |
| `/feedback` | Report issue or suggest a feature |
| `/beta` | Beta features |
| `/exit` | Exit LaSearch |

### Supported File Types

LaSearch can index and search a wide range of file types:

- **Documents** — PDF, DOCX, XLSX, PPTX, ODT, EPUB, HTML
- **Text & Code** — TXT, MD, JSON, YAML, CSV, and 20+ programming languages
- **Email** — EML, MSG
- **Media** — images, audio, and video (metadata for now, OCR, STT, etc coming soon)
- **Archives** — ZIP, TAR, 7Z, RAR (currently disabled)

## Privacy

LaSearch never sends your data anywhere. Search indices are built and stored locally. The only network requests the app makes are checking for updates and fetching open issues for the feedback command (both via GitHub). Online service integrations like Gmail connect directly to the service provider — no data passes through LaSearch servers.

See the full [Privacy Policy](https://lasearch.app/privacy-policy).

## Pricing

LaSearch is completely free for now. When paid options are introduced down the road, they'll be around convenience features. Any version released as free stays free forever.

## Transparency

- Third-party licenses are included in the app bundle
- SBOMs: [Cargo](https://github.com/7sedam7/lasearch/releases/latest/download/lasearch-cargo.cdx.json) · [NPM](https://github.com/7sedam7/lasearch/releases/latest/download/lasearch-npm.cdx.json)

## Built With

LaSearch is built on top of some amazing open-source projects:

- [Tauri](https://github.com/tauri-apps/tauri) — app framework
- [Svelte](https://github.com/sveltejs/svelte), [Tailwind CSS](https://github.com/tailwindlabs/tailwindcss), [shadcn-svelte](https://github.com/huntabyte/shadcn-svelte) — UI
- [Kreuzberg](https://github.com/kreuzberg-dev/kreuzberg), [pdf_oxide](https://github.com/yfedoseev/pdf_oxide), [lopdf](https://github.com/J-F-Liu/lopdf) — document text extraction
- [syntect](https://github.com/trishume/syntect) — syntax highlighting
- [fst](https://github.com/BurntSushi/fst) — fuzzy search
- [rkyv](https://github.com/rkyv/rkyv) — zero-copy deserialization

## Feedback

This is an early beta — feedback is hugely appreciated.

- [Open an issue](https://github.com/7sedam7/lasearch/issues)
- [Send an email](mailto:joel@lasearch.app)

## Links

- **Website** — [lasearch.app](https://lasearch.app)
- **Live Demo** — [epstein.lasearch.app](https://epstein.lasearch.app) (1.4M documents)
- **Privacy Policy** — [lasearch.app/privacy-policy](https://lasearch.app/privacy-policy)
- **Terms of Service** — [lasearch.app/terms-of-service](https://lasearch.app/terms-of-service)
