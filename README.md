# WikiBrand MCP

Logo, colors, typefaces, tone of voice and CSS theme of any brand, read from its own website.

Remote MCP server: `https://wikibrand.org/api/mcp` (Streamable HTTP, no authentication).

## Tools

- `search_brands`: find brands in the WikiBrand catalogue by name or domain, optionally within a category.
- `get_brand`: get a brand's logo, colors, typography, tone of voice and full CSS theme from its domain (e.g. `stripe.com`).

## Install in Cursor

Add this to `.cursor/mcp.json` (or `~/.cursor/mcp.json`):

```json
{
  "mcpServers": {
    "wikibrand": {
      "type": "http",
      "url": "https://wikibrand.org/api/mcp"
    }
  }
}
```

Website: https://wikibrand.org
