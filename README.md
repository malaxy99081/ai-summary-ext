# ai-summary-ext

MV3 extension: one click, tl;dr of any article

## Features

- Manifest V3 service worker, no build step
- Options page for API base and key
- Reads the page, extracts main text, sends to your endpoint
- Popup shows a 5-bullet summary

## Installation

```bash
# chrome://extensions -> load unpacked -> select this folder
# set your API base + key on the options page
```

## How to use

```bash
# open any article, click the icon, get a 5-bullet summary
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── workflows/
│   │   └── ci.yml
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── background.js
├── manifest.json
├── options.html
├── popup.html
└── popup.js
```

## Development

```bash
npm install
```
