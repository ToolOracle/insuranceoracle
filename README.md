# 🛡️ insuranceOracle

**Insurance MCP Server** — 12 tools | Part of [ToolOracle](https://tooloracle.io)

![Tools](https://img.shields.io/badge/MCP_Tools-12-10B898?style=flat-square)
![Status](https://img.shields.io/badge/Status-Live-00C853?style=flat-square)
![Tier](https://img.shields.io/badge/Tier-Enterprise-FF6D00?style=flat-square)

## Quick Connect

```bash
# Claude Desktop / Cursor / Windsurf
npx -y mcp-remote https://tooloracle.io/insurance/mcp/
```

```json
// claude_desktop_config.json
{
  "mcpServers": {
    "insuranceoracle": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://tooloracle.io/insurance/mcp/"]
    }
  }
}
```

## Tools (12)

| Tool | Description |
|------|-------------|
| `insurance_company` | Look up EU insurance company by name or LEI number. Returns GLEIF registration s |
| `insurance_news` | Insurance industry news by topic. Topics: solvency, life, health, property, liab |
| `natcat_live` | Live natural catastrophe alerts worldwide from GDACS. Returns earthquakes, flood |
| `earthquake_risk` | Real-time earthquake data from USGS. Filter by time period, minimum magnitude, a |
| `weather_risk` | 7-day weather risk assessment for any location. Returns storm, flood, and wind r |
| `natcat_history` | Historical natural catastrophe statistics for risk modeling. Significant events  |
| `solvency_check` | Solvency II compliance news and GLEIF registration status for an insurer. |
| `insurance_regulation` | EU and German insurance regulatory news and updates. Topics: general, bafin, eio |
| `risk_score` | Combined location risk score (0-100) for underwriting: earthquake + weather/stor |
| `insurance_glossary` | Explain insurance and Solvency II terms in German or English. Covers: SCR, MCR,  |
| `claim_news` | Major insurance claim news by event type: storm, flood, earthquake, hail, fire,  |
| `health_check` | InsuranceOracle server status and backend connectivity check. |

## Pricing

| Tier | Rate Limit | Price |
|------|-----------|-------|
| Free | 10 calls/day | €0 |
| Pro | 1,000 calls/day | €99/month |
| Enterprise | Unlimited | Custom |

> **Note:** This is a compliance oracle. Full tool access requires a Pro or Enterprise subscription. Free tier includes read-only assessment tools.

## Part of ToolOracle

insuranceOracle is one of **42 specialized MCP servers** in the [ToolOracle](https://tooloracle.io) ecosystem — the largest collection of production-ready MCP tools for AI agents.



**Related Oracles:**
- [FeedOracle](https://feedoracle.io) — Evidence-grade compliance data infrastructure
- [ToolOracle](https://tooloracle.io) — 42 Oracles, 390+ MCP Tools

## Links

- 🌐 Live: `https://tooloracle.io/insurance/mcp/`
- 📚 Docs: [tooloracle.io/docs](https://tooloracle.io/docs)
- 🏠 Platform: [tooloracle.io](https://tooloracle.io)

---

*Built by [FeedOracle](https://feedoracle.io) — Evidence by Design*
