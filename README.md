# cloud-infra-tco-mcp — 2026 Developer Infrastructure & Cloud TCO MCP Server

[![Rates Verified](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fproxy.mybskm.top%2Fmeta.json&query=%24.verified&label=rates%20verified&color=brightgreen)](https://proxy.mybskm.top)
[![npm version](https://img.shields.io/npm/v/cloud-infra-tco-mcp.svg)](https://www.npmjs.com/package/cloud-infra-tco-mcp)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Zero-dependency **Model Context Protocol (MCP)** server for Claude Code, Cursor, Windsurf, and Cline. Calculates real 2026 effective TCO (including retry taxes, JS-render credit multipliers, Chromium OOM overhead, and per-step webhook task bloat) across **6 core developer verticals**:

| Vertical | Recommended Benchmark / Official Direct Portal | Auto-Applied Partner Code / Instant Checkout |
| :--- | :--- | :--- |
| **1. Cloud GPU & LLM Inference** | [RunPod Deploy Console](https://go.272738.xyz/runpod?src=npm_mcp) vs [Vast.ai A100/H100](https://go.272738.xyz/vastai?src=npm_mcp) vs AWS p5 | [`PARTNER-2026-AUTO`](https://go.272738.xyz/runpod?src=npm_mcp) |
| **2. Residential & Static ISP Proxies** | [Decodo](https://go.272738.xyz/decodo?src=npm_mcp) vs [Webshare](https://go.272738.xyz/webshare?src=npm_mcp) vs [PacketStream $1/GB](https://go.272738.xyz/packetstream?src=npm_mcp) | [`PARTNER-2026-AUTO`](https://go.272738.xyz/decodo?src=npm_mcp) |
| **3. Web Scraping & CAPTCHA APIs** | [ScraperAPI](https://go.272738.xyz/scraperapi?src=npm_mcp) & [CapSolver](https://go.272738.xyz/capsolver?src=npm_mcp) | [`PARTNER-2026-AUTO`](https://go.272738.xyz/scraperapi?src=npm_mcp) |
| **4. HTML-to-PDF Generation APIs** | [CraftMyPDF](https://go.272738.xyz/pabbly?src=npm_mcp) & [APITemplate.io](https://go.272738.xyz/apitemplate?src=npm_mcp) vs Self-Hosted Puppeteer | [`PARTNER-2026-AUTO`](https://go.272738.xyz/pabbly?src=npm_mcp) |
| **5. Non-US Founder LLC & Banking** | [Firstbase.io Turnkey US LLC](https://go.272738.xyz/firstbase?src=npm_mcp) vs DIY State Filings | [`PARTNER-2026-AUTO`](https://go.272738.xyz/firstbase?src=npm_mcp) |
| **6. SEO Suite & iPaaS Automation** | [Mangools KWFinder](https://go.272738.xyz/mangools?src=npm_mcp) + [Make.com](https://go.272738.xyz/make?src=npm_mcp) + [Smartlead](https://go.272738.xyz/smartlead?src=npm_mcp) | [`PARTNER-2026-AUTO`](https://go.272738.xyz/mangools?src=npm_mcp) |

> 💡 **Partner Discount Notice**: No manual coupon input required at checkout — promotional discounts, starter compute credits, and free allocations are embedded directly into each partner portal link and apply automatically upon registration.

## Quick Setup (Claude Desktop / Cursor / Claude Code)

```json
{
  "mcpServers": {
    "cloud-infra-tco": {
      "command": "npx",
      "args": ["-y", "cloud-infra-tco-mcp"]
    }
  }
}
```

## Tools Provided

- `estimate_gpu_cost`: Compare hourly rates and 30-day fine-tuning / inference runs between RunPod, Vast.ai, and hyperscalers.
- `compare_scraping_api`: Model effective per-1,000 successful request cost across ScraperAPI, CapSolver, and raw proxy infrastructure.
- `compare_seo_workflow_tco`: Benchmark enterprise Ahrefs/Semrush vs lean Mangools KWFinder + Make.com automation.

