# Geonode Integrations

Web data for your applications, AI agents and automated workflows.

[Website](https://geonode.com) · [Documentation](https://docs.geonode.com/docs/scraper-api) · [Browse integrations](https://geonode.com/integrations) · [Get an API key](https://app.geonode.com/sign-up) · [Contact us](https://geonode.com/contact)

## Start building

Use the **REST API** from any language, connect your assistant through **MCP**, or work from your terminal with the **CLI**.

| Integration | What it does | Status | Documentation | Package |
| --- | --- | --- | --- | --- |
| **REST API** | Use Geonode from any language. | Available | [Geonode API reference](https://docs.geonode.com/docs/scraper-api/v1/reference) | — |
| **Geonode MCP Server** | Connect your AI assistant to the live web. | Available | [Geonode MCP Server docs](https://docs.geonode.com/docs/scraper-api/guides/mcp/00_overview) | — |
| **CLI** | From a URL to web data, in your terminal. | Available | [View CLI on PyPI](https://pypi.org/project/geonode-scraper-cli/) | [View on PyPI](https://pypi.org/project/geonode-scraper-cli/) |

### Connect an AI assistant

Geonode's hosted MCP endpoint is:

```text
https://scraper.geonode.io/mcp
```

Start with the [MCP setup guide](https://docs.geonode.com/docs/scraper-api/guides/mcp/00_overview). Limited anonymous page extraction is available; additional tools and account usage require a Geonode API key. This is a hosted service, not a self-hosted scraping backend.

## Choose your integration

### SDKs

| Integration | What it does | Status | Documentation | Package |
| --- | --- | --- | --- | --- |
| **Python SDK** | Web data, with the Python you already know. | Available | [Geonode Python SDK docs](https://docs.geonode.com/docs/scraper-api/developer-guides/python-sdk) | [View on PyPI](https://pypi.org/project/geonode-scraper-sdk/) |
| **TypeScript SDK** | Typed web extraction for your application. | Available | [View TypeScript SDK on npm](https://www.npmjs.com/package/@geonode_scraper/scraper-sdk) | [View on npm](https://www.npmjs.com/package/@geonode_scraper/scraper-sdk) |

### Frameworks

| Integration | What it does | Status | Documentation | Package |
| --- | --- | --- | --- | --- |
| **Agent tools core** | One shared foundation for your agent tools. | Available | [View Agent tools core on PyPI](https://pypi.org/project/geonode-scraper-tools-core/) | [View on PyPI](https://pypi.org/project/geonode-scraper-tools-core/) |
| **CrewAI** | Put fresh web data in your crew’s hands. | Available | [Geonode CrewAI docs](https://docs.geonode.com/docs/scraper-api/developer-guides/crewai) | [View on PyPI](https://pypi.org/project/geonode-scraper-crewai/) |
| **LangChain** | Give your LangChain agents web data tools. | Available | [Geonode LangChain docs](https://docs.geonode.com/docs/scraper-api/developer-guides/langchain) | [View on PyPI](https://pypi.org/project/geonode-scraper-langchain/) |

### Automation

| Integration | What it does | Status | Documentation | Package |
| --- | --- | --- | --- | --- |
| **Make** | Connect extraction to a Make scenario. | Private app | [Geonode API docs](https://docs.geonode.com/docs/scraper-api) | — |
| **n8n** | Bring web data into your n8n workflows. | Available · self-hosted community node | [View n8n on npm](https://www.npmjs.com/package/n8n-nodes-scraperapi) | [View on npm](https://www.npmjs.com/package/n8n-nodes-scraperapi) |
| **Zapier** | Bring Geonode into your Zaps. | Private app | [Geonode API docs](https://docs.geonode.com/docs/scraper-api) | — |

### Which Python package do I need?

- **Python SDK**: call the API from your Python application.
- **LangChain or CrewAI**: add Geonode tools to the framework you already use. The shared runtime installs as a dependency.
- **Agent tools core**: build a custom framework adapter using shared schemas and request handling. It is a Python library, not an MCP server.

## Availability

- **Available** means the package or documented service is available. It does not imply third-party marketplace verification or that every workflow has been tested.
- **n8n** is a self-hosted community node; n8n Cloud support and platform verification have not been established.
- **Make and Zapier** are private apps. [Contact Geonode](https://geonode.com/contact) to discuss access; there is no verified public marketplace listing linked here.
- The agent onboarding guide is being reviewed. Use the current [MCP documentation](https://docs.geonode.com/docs/scraper-api/guides/mcp/00_overview) for setup.

## Machine-readable catalog

[Download catalog.json](./catalog.json) for the 12 current integration records: package versions, installation commands, documentation links, compatibility and verification status. Each record includes its review date. `published`, `private`, `planned` and `audit-required` describe integration availability, not this repository's visibility.

The catalog is generated from a maintained registry. Source links remain empty where code is not publicly accessible. Installation and API usage can require a Geonode account; API requests are subject to your plan's pricing and limits.

## Feedback and support

[Contact Geonode](https://geonode.com/contact) for setup help or to request an integration. Include the package name, version and a minimal example with credentials removed.
