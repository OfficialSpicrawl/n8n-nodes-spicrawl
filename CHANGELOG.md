# Changelog

## 0.1.1

- Source moved from the `n8n/` folder of `OfficialSpicrawl/agent-plugins` to its own repository, `OfficialSpicrawl/n8n-nodes-spicrawl`, with the package at the repository root (`credentials/`, `nodes/`, `package.json`). n8n's verification reads the credential file from the repository root and could not find it in a subfolder.
- `repository`, `homepage` and `bugs` in `package.json` point at the new repository. No code change.
## 0.1.0

- Initial release: `Spicrawl` node with Scrape URL and Batch Scrape, and the `Spicrawl API` credential.
