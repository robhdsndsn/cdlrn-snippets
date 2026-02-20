# CDLRN Snippets

Code snippets for the CDLRN WordPress site (`cdlrn.the-ria.ca`), managed by [SnipForge](https://github.com/robhdsndsn/snipforge).

## Structure

```
cdlrn-snippets/
├── php/           # PHP snippets (hooks, shortcodes, etc.)
├── js/            # JavaScript snippets (frontend scripts)
├── css/           # CSS snippets (custom styles)
├── api/           # API endpoint snippets
└── sf-manifest.json   # Snippet registry and metadata
```

## Usage

1. Add snippet files to the appropriate folder (`php/`, `js/`, `css/`, or `api/`)
2. Register each snippet in `sf-manifest.json`
3. Commit and push -- SnipForge will sync automatically via webhook

## Setup

Connect this repo in WordPress:
- **Settings > SnipForge > GitHub Repository**: `robhdsndsn/cdlrn-snippets`
- **Branch**: `main`
- Configure the webhook for automatic sync on push
