# MCP Server Patent Integration

This repository contains the Model Context Protocol (MCP) server configuration for patent data integration, including setup scripts and documentation for multiple patent database APIs.

## Structure

```
.
├── config/
│   ├── mcp-config.json     # Main MCP server configuration
│   └── .env.example        # Environment variables template
├── scripts/
│   ├── setup.sh           # Installation script
│   └── test-servers.sh    # Server testing script
└── docs/
    ├── EPO.md            # EPO-OPS API documentation
    ├── WIPO.md           # WIPO API documentation
    ├── USPTO.md          # PatentsView API documentation
    └── SCORING.md        # RapidAPI scoring documentation
```

## Servers

1. EPO-OPS (European Patent Office)
2. WIPO (World Intellectual Property Organization)
3. USPTO PatentsView
4. RapidAPI Patent Scoring
5. Redis Cache
6. Queue Management

## Setup

1. Clone this repository
2. Copy `.env.example` to `.env` and fill in your API keys
3. Run `./scripts/setup.sh` to install dependencies
4. Run `./scripts/test-servers.sh` to verify setup

## License

MIT