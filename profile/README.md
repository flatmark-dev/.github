**Document to Markdown API and MCP server for PDF, Word, PowerPoint, Excel and HTML. OCR queue for large files. Hosted in Germany.**

flatmark converts PDF, Word, PowerPoint, Excel and HTML to Markdown over a REST API and an MCP server. Files up to 8 MB convert in one call with MarkItDown. Files up to 25 MB and 200 pages go through a queue that runs Docling with OCR and table detection. The queue returns Markdown and a JSON structure file, by polling or a signed webhook. The servers are in Germany. The free plan has 100 credits a month and needs no card.

## Repositories

- [flatmark](https://github.com/flatmark-dev/flatmark): start here, for the MCP server, the Claude Code plugin and the API.
- [flatmark-integrations](https://github.com/flatmark-dev/flatmark-integrations): n8n, Zapier, Make, Dify, SDKs and templates.
- [flatmark-action](https://github.com/flatmark-dev/flatmark-action): use flatmark in GitHub Actions.

## Links

- **Website:** https://flatmark.dev/go/github
- **API docs:** https://api.flatmark.dev/docs
- **Pricing:** https://flatmark.dev/pricing
- **Support:** https://flatmark.dev/support
