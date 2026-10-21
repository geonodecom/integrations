![Geonode — Your stack. Connected.](./assets/banner.svg)

# Geonode Integrations

Bring fresh web data into what you're building. Extract readable page content, discover URLs, and connect the results to your applications, AI agents and everyday workflows.

**[Create your Geonode account →](https://app.geonode.com/sign-up)** &nbsp; · &nbsp; [Explore the docs](https://docs.geonode.com/docs/scraper-api) &nbsp; · &nbsp; [Visit Geonode](https://geonode.com)

## Start with the way you work

| What would you like to build? | Start here |
| --- | --- |
| **An application that uses web data** | [REST API reference](https://docs.geonode.com/docs/scraper-api/v1/reference) — call Geonode from any language. |
| **An AI assistant that can work with the web** | [Connect with MCP](https://docs.geonode.com/docs/scraper-api/guides/mcp/00_overview) — use Geonode tools from a compatible assistant. |
| **A script or terminal workflow** | [Install the CLI](https://pypi.org/project/geonode-scraper-cli/) — extract, search, crawl and map from your terminal. |

**New to Geonode?** [Create an account](https://app.geonode.com/sign-up), get your API key from the dashboard, and follow the guide for your stack below. MCP also offers limited anonymous page extraction if you want to try connecting first. [See authentication and limits](https://docs.geonode.com/docs/scraper-api/guides/mcp/01_before-you-start).

## Your tools, connected

Use an SDK in your application, add web tools to an agent, or bring extracted content into an automation. These integrations use the Geonode Scraper API, so you can choose the interface that fits your project.

### SDKs

| Integration | What it does | Status | Documentation | Package |
| --- | --- | --- | --- | --- |
| **Python SDK** | Web data, with the Python you already know. | Available | [Geonode Python SDK docs](https://docs.geonode.com/docs/scraper-api/developer-guides/python-sdk) | [View on PyPI](https://pypi.org/project/geonode-scraper-sdk/) |
| **TypeScript SDK** | Typed web extraction for your application. | Available | [View TypeScript SDK on npm](https://www.npmjs.com/package/@geonode_scraper/scraper-sdk) | [View on npm](https://www.npmjs.com/package/@geonode_scraper/scraper-sdk) |

### Frameworks

| Integration | What it does | Status | Documentation | Package |
| --- | --- | --- | --- | --- |
| **Agent tools core** | Shared Python tools for custom agent integrations. | Available | [View Agent tools core on PyPI](https://pypi.org/project/geonode-scraper-tools-core/) | [View on PyPI](https://pypi.org/project/geonode-scraper-tools-core/) |
| **CrewAI** | Put fresh web data in your crew’s hands. | Available | [Geonode CrewAI docs](https://docs.geonode.com/docs/scraper-api/developer-guides/crewai) | [View on PyPI](https://pypi.org/project/geonode-scraper-crewai/) |
| **LangChain** | Give your LangChain agents web data tools. | Available | [Geonode LangChain docs](https://docs.geonode.com/docs/scraper-api/developer-guides/langchain) | [View on PyPI](https://pypi.org/project/geonode-scraper-langchain/) |

### Automation

| Integration | What it does | Status | Documentation | Package |
| --- | --- | --- | --- | --- |
| **Make** | Connect extraction to a Make scenario. | Private app | [Geonode API docs](https://docs.geonode.com/docs/scraper-api) | — |
| **n8n** | Bring web data into your n8n workflows. | Available · self-hosted community node | [View n8n on npm](https://www.npmjs.com/package/n8n-nodes-scraperapi) | [View on npm](https://www.npmjs.com/package/n8n-nodes-scraperapi) |
| **Zapier** | Bring Geonode into your Zaps. | Private app | [Geonode API docs](https://docs.geonode.com/docs/scraper-api) | — |

<details>
<summary><strong>Which Python package should I choose?</strong></summary>

### Choose a Python package

- **Python SDK**: call the API from your Python application.
- **LangChain or CrewAI**: add Geonode tools to the framework you already use. The shared runtime installs as a dependency.
- **Agent tools core**: build a custom framework adapter using shared schemas and request handling. It is a Python library, not an MCP server.

</details>

## A few things to know

- **n8n** is available as a community node for self-hosted installations; n8n Cloud support is not available through this listing.
- **Make and Zapier** are private apps. [Talk to us about your workflow](https://geonode.com/contact) to discuss access.
- Authenticated requests use your Geonode plan and limits. [Check API pricing](https://docs.geonode.com/docs/scraper-api/additional-resources/pricing). AI assistants and automation platforms may have separate subscriptions.

## Help shape what comes next

Which connection would make your work easier? We're exploring more SDKs, agent frameworks and automation tools. [Tell us what you want to build](https://geonode.com/contact).

<details>
<summary>See the integrations under consideration</summary>

Go SDK · Java SDK · Rust SDK · Ruby SDK · PHP SDK · .NET SDK · LlamaIndex · OpenAI Agents SDK · Vercel AI SDK · Mastra · Dify · Coze · Pipedream · Google Sheets · Airbyte · Snowflake · BigQuery · Amazon S3 · Postman

These are proposals, not released integrations or committed launch dates. [Tell us which workflow you need](https://geonode.com/contact). The machine-readable catalog below covers the current inventory; proposed connectors do not have install commands or package listings yet.

</details>

## For developers and agents

[Download catalog.json](./catalog.json) for the 12 current integration records: package versions, installation commands, documentation links, compatibility and verification status. Each record includes its review date. `published`, `private`, `planned` and `audit-required` describe integration availability, not this repository's visibility.

Source links are added as repositories become publicly accessible. The catalog includes review dates and verification details so you can distinguish published packages, private apps and work in progress.

## Let's build something useful

**[Create your account](https://app.geonode.com/sign-up)** and start with your preferred integration. Have a question or a workflow in mind? [Talk to the Geonode team](https://geonode.com/contact).
