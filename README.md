# CDLRN Snippets

Code snippets for the CDLRN WordPress site, managed by [CodePress Connect](https://github.com/robhdsndsn/CodePress_Connect).

## Structure

```
cdlrn-snippets/
├── php/           # PHP snippets (hooks, shortcodes, etc.)
├── js/            # JavaScript snippets (frontend scripts)
├── css/           # CSS snippets (custom styles)
├── api/           # API endpoint snippets
└── cpc-manifest.json  # Snippet registry and metadata
```

## Usage

1. Add snippet files to the appropriate folder (`php/`, `js/`, `css/`, or `api/`)
2. Register each snippet in `cpc-manifest.json`
3. Commit and push -- CodePress Connect will sync automatically via webhook

## Setup

Connect this repo in WordPress:
- **Settings > CodePress Connect > GitHub Repository**: `robhdsndsn/cdlrn-snippets`
- **Branch**: `main`
- Configure the webhook for automatic sync on push
