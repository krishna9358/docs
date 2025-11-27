# ShipSec Studio Docs

Documentation for ShipSec Studio - an open source security automation platform.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview docs locally:

```bash
npm i -g mint
```

Run at the root of docs folder:

```bash
mint dev
```

Preview at `http://localhost:3000`

## Structure

```
docs/
├── index.mdx              # Introduction
├── quickstart.mdx         # Quick setup guide
├── installation.mdx       # Full installation guide
├── components/
│   ├── overview.mdx       # Components overview
│   ├── core.mdx           # Core components
│   ├── security.mdx       # Security tools
│   ├── ai.mdx             # AI/LLM integrations
│   └── it-automation.mdx  # IT automation
├── docs.json              # Mintlify config
└── logo/                  # Brand assets
```

## Publishing

Changes pushed to the default branch are automatically deployed.
