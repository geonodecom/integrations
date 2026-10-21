![Geonode — Your stack. Connected.](./assets/banner.svg)

# Geonode Integrations

Web data for your applications, AI agents and workflows. Extract readable page content, discover URLs, and connect the results to the tools you already use.

**[Create an account →](https://app.geonode.com/sign-up)** &nbsp; · &nbsp; [Documentation](https://docs.geonode.com/docs/scraper-api) &nbsp; · &nbsp; [Geonode](https://geonode.com)

[Start here](#start-here) · [SDKs](#sdks) · [Agent frameworks](#agent-frameworks) · [Automation](#automation) · [What's next](#whats-next) · [Catalog](#machine-readable-catalog)

## Start here

| Connection | Choose it when | Documentation |
| --- | --- | --- |
| **API** | You're building an application in any language. | [REST API reference](https://docs.geonode.com/docs/scraper-api/v1/reference) |
| **MCP** | Your AI assistant needs to read and work with web data. | [MCP setup guide](https://docs.geonode.com/docs/scraper-api/guides/mcp/00_overview) |
| **CLI** | You're working in a terminal or automating a shell script. | [CLI on PyPI](https://pypi.org/project/geonode-scraper-cli/) |

**New to Geonode?** [Create an account](https://app.geonode.com/sign-up), get your API key from the dashboard, and follow the guide for your stack. MCP also offers limited anonymous page extraction. [Authentication and limits →](https://docs.geonode.com/docs/scraper-api/guides/mcp/01_before-you-start)

## SDKs

Use typed clients in your application.

| Integration | Use it for | Start building |
| --- | --- | --- |
| **Python SDK** | Web data, with the Python you already know. | [Geonode guide](https://docs.geonode.com/docs/scraper-api/developer-guides/python-sdk) · [PyPI](https://pypi.org/project/geonode-scraper-sdk/) |
| **TypeScript SDK** | Typed web extraction for your application. | [npm & setup](https://www.npmjs.com/package/@geonode_scraper/scraper-sdk) |

## Agent frameworks

Give an agent tools to extract pages, map sites, search the web and work with longer jobs.

| Integration | Use it for | Start building |
| --- | --- | --- |
| **LangChain** | Give your LangChain agents web data tools. | [Geonode guide](https://docs.geonode.com/docs/scraper-api/developer-guides/langchain) · [PyPI](https://pypi.org/project/geonode-scraper-langchain/) |
| **CrewAI** | Put fresh web data in your crew’s hands. | [Geonode guide](https://docs.geonode.com/docs/scraper-api/developer-guides/crewai) · [PyPI](https://pypi.org/project/geonode-scraper-crewai/) |

<details>
<summary><strong>Building your own Python adapter?</strong></summary>

**Agent tools core** provides shared schemas, request handling, polling and an operation registry above the Python SDK. LangChain, CrewAI and the CLI install it as a dependency.

Install it directly when building a custom adapter. It is a Python library, not an MCP server.

[View agent tools core on PyPI](https://pypi.org/project/geonode-scraper-tools-core/)

</details>

## Automation

Bring extracted content into a workflow and send it to the next step.

| Integration | Use it for | Start building |
| --- | --- | --- |
| **n8n**<br><sub>Self-hosted community node</sub> | Bring web data into your n8n workflows. | [npm & setup](https://www.npmjs.com/package/n8n-nodes-scraperapi) |
| **Make**<br><sub>Private app</sub> | Connect extraction to a Make scenario. | [Geonode guide](https://docs.geonode.com/docs/scraper-api) |
| **Zapier**<br><sub>Private app</sub> | Bring Geonode into your Zaps. | [Geonode guide](https://docs.geonode.com/docs/scraper-api) |

**n8n:** the community node supports self-hosted installations. This listing does not provide n8n Cloud access. **Make and Zapier:** private apps; [contact Geonode](https://geonode.com/contact) to confirm access and supported actions.

## What's next

We're exploring more SDKs, frameworks and workflow tools. [Tell us which connection would help you](https://geonode.com/contact).

<details>
<summary>Explore the integrations under consideration</summary>

Go SDK · Java SDK · Rust SDK · Ruby SDK · PHP SDK · .NET SDK · LlamaIndex · OpenAI Agents SDK · Vercel AI SDK · Mastra · Dify · Coze · Pipedream · Google Sheets · Airbyte · Snowflake · BigQuery · Amazon S3 · Postman

These are proposals, not released integrations or committed launch dates. The catalog below covers the current inventory; proposed connectors do not have install commands or package listings yet.

</details>

## Machine-readable catalog

[**Open catalog.json →**](./catalog.json)

The 12 current records include package versions, installation commands, documentation links, compatibility and review dates. Availability is recorded separately from verification: a published package does not establish a successful end-to-end connection test.

Source links are added when repositories become publicly accessible. The agent setup guide is currently in review; use the [current MCP documentation](https://docs.geonode.com/docs/scraper-api/guides/mcp/00_overview) for assistant setup.

## Account, usage and support

Authenticated requests use your Geonode plan and limits. [Read the API pricing guide](https://docs.geonode.com/docs/scraper-api/additional-resources/pricing). Assistants and automation platforms may have separate subscriptions.

**[Create your account](https://app.geonode.com/sign-up)** &nbsp; · &nbsp; [Get help](https://geonode.com/contact) &nbsp; · &nbsp; [Browse all integrations](https://geonode.com/integrations)
