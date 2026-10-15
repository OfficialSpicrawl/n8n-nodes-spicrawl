# Changelog

## 0.1.2

- Discoverability, no code change. `package.json` description and keywords now say what the node does (web scraping, Markdown, data extraction, AI Agent tool).
- Node codex file: added `Data & Storage` to the categories and search aliases (scrape, crawl, web, html, markdown, extract, website and others) for n8n's in-app node search.
- Node description in the node panel names the output formats, CSS selector extraction and batch scraping.
- README: opens with a direct answer to "How do I scrape a website in n8n?", and adds a quick start, use cases and an FAQ (JavaScript sites, AI Agent tool, free tier, field extraction). Links the n8n guide at docs.spicrawl.com/agents/n8n.

## 0.1.1

- Source moved from the `n8n/` folder of `OfficialSpicrawl/agent-plugins` to its own repository, `OfficialSpicrawl/n8n-nodes-spicrawl`, with the package at the repository root (`credentials/`, `nodes/`, `package.json`). n8n's verification reads the credential file from the repository root and could not find it in a subfolder.
- `repository`, `homepage` and `bugs` in `package.json` point at the new repository. No code change.
## 0.1.0

- Initial release: `Spicrawl` node with Scrape URL and Batch Scrape, and the `Spicrawl API` credential.
