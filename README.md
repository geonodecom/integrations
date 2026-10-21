![Geonode — Web scraping API, MCP, SDKs and automation connectors](./assets/banner.svg)

# Geonode Integrations — Web Scraping API, MCP & Automation

Web data for your applications, AI agents and workflows. Extract readable page content, discover URLs, and connect the results to the tools you already use.

**[Sign up to get 10,000 free credits](https://app.geonode.com/sign-up)** &nbsp; · &nbsp; [Documentation](https://docs.geonode.com/docs/scraper-api) &nbsp; · &nbsp; [Geonode](https://geonode.com)

[Start here](#start-here) · [SDKs](#sdks) · [Agent frameworks](#agent-frameworks) · [Automation](#automation) · [Proposed integrations](#proposed-integrations) · [Catalog](#machine-readable-catalog)

## Start here

| Connection | Choose it when | Documentation |
| --- | --- | --- |
| **API** | You're building an application in any language. | [REST API reference](https://docs.geonode.com/docs/scraper-api/v1/reference) |
| **MCP** | Your AI assistant needs to read and work with web data. | [MCP setup guide](https://docs.geonode.com/docs/scraper-api/guides/mcp/00_overview) |
| **CLI** | You're working in a terminal or automating a shell script. | [CLI on PyPI](https://pypi.org/project/geonode-scraper-cli/) |

**Your first connection:** create a Geonode account, get an API key from the [dashboard](https://app.geonode.com/), then follow one setup guide and test a single URL.

MCP also supports limited anonymous page extraction. [Try MCP without a key →](https://docs.geonode.com/docs/scraper-api/guides/mcp/01_use-without-an-api-key)

## SDKs

Use typed clients in your application.

| Integration | Use it for | Start building |
| --- | --- | --- |
| <img src="assets/python.svg" width="24" height="24" alt="Python SDK logo" /> **Python SDK** | Typed requests and responses in Python. | [Geonode guide](https://docs.geonode.com/docs/scraper-api/developer-guides/python-sdk) · [PyPI](https://pypi.org/project/geonode-scraper-sdk/) |
| <img src="assets/typescript.svg" width="24" height="24" alt="TypeScript SDK logo" /> **TypeScript SDK** | Typed API calls from server-side JavaScript or TypeScript. | [npm & setup](https://www.npmjs.com/package/@geonode_scraper/scraper-sdk) |

## Agent frameworks

Give an agent tools to extract pages, map sites, search the web and work with longer jobs.

| Integration | Use it for | Start building |
| --- | --- | --- |
| <img src="assets/langchain.svg" width="24" height="24" alt="LangChain logo" /> **LangChain** | Native tools for LangChain agents and workflows. | [Geonode guide](https://docs.geonode.com/docs/scraper-api/developer-guides/langchain) · [PyPI](https://pypi.org/project/geonode-scraper-langchain/) |
| <img src="assets/crewai.svg" width="24" height="24" alt="CrewAI logo" /> **CrewAI** | Native tools for CrewAI agents and tasks. | [Geonode guide](https://docs.geonode.com/docs/scraper-api/developer-guides/crewai) · [PyPI](https://pypi.org/project/geonode-scraper-crewai/) |

<details>
<summary><strong>Building your own Python adapter?</strong></summary>

**Agent tools core** provides shared schemas, request handling, polling and an operation registry above the Python SDK. LangChain, CrewAI and the CLI install it as a dependency.

Install it directly when building a custom adapter. This is a supporting Python dependency, not a separate integration or a planned standalone repository.

[View agent tools core on PyPI](https://pypi.org/project/geonode-scraper-tools-core/)

</details>

## Automation

Bring extracted content into a workflow and send it to the next step.

| Integration | Use it for | Start building |
| --- | --- | --- |
| <img src="assets/n8n.svg" width="24" height="24" alt="n8n logo" /> **n8n**<br><sub>Self-hosted community node</sub> | Extraction and completion triggers in n8n workflows. | [npm & setup](https://www.npmjs.com/package/n8n-nodes-scraperapi) |
| <img src="assets/make.svg" width="24" height="24" alt="Make logo" /> **Make.com**<br><sub>Private app</sub> | Scrape pages, crawl sites and process URL lists in Make.com scenarios. | [Discuss access](https://geonode.com/contact) |
| <img src="assets/zapier.svg" width="24" height="24" alt="Zapier logo" /> **Zapier**<br><sub>Private app</sub> | Extract pages, run batches and crawls, then continue a Zap when a job finishes. | [Discuss access](https://geonode.com/contact) |

**n8n:** a community node for self-hosted installations. **Make.com:** 15 source-defined modules cover extraction, batches, crawls, URL mapping and usage. **Zapier:** four actions, a job lookup and a completion trigger. Make and Zapier require [private app access](https://geonode.com/contact); live workflow execution has not been verified in this review.

## Proposed integrations

We're exploring more SDKs, frameworks and workflow tools. [Tell us which connection would help you](https://geonode.com/contact).

<details>
<summary>Explore the integrations under consideration</summary>

- **SDKs:** Go SDK, Java SDK, Rust SDK, Ruby SDK, PHP SDK, .NET SDK.
- **Agent frameworks:** LlamaIndex, OpenAI Agents SDK, Vercel AI SDK, Mastra.
- **Automation and data:** Dify, Coze, Pipedream, Google Sheets, Airbyte, Snowflake, BigQuery, Amazon S3.
- **API tooling:** Postman.

These are proposals, not released integrations or committed launch dates. The catalog below covers the current inventory; proposed connectors do not have install commands or package listings yet.

</details>

## Machine-readable catalog

[**Open catalog.json →**](./catalog.json)

The 10 current records include package versions, installation commands, documentation links, compatibility and review dates. Availability is recorded separately from verification: a published package does not establish a successful end-to-end connection test.

For programmatic use, check `lifecycle`, `installation.status` and `verification` before choosing an installation path. Check source_visibility before linking to source; private GitHub URLs require access. A null link means no destination is listed.

<details>
<summary><strong>Source repositories · private</strong></summary>

These repositories have been created and remain private while we prepare them for release. GitHub access is required; use the published packages and setup guides above today. Repository names do not change the current npm or PyPI package names.

| Integration | GitHub repository |
| --- | --- |
| MCP | [geonodecom/mcp](https://github.com/geonodecom/mcp) |
| CLI | [geonodecom/cli](https://github.com/geonodecom/cli) |
| Python SDK | [geonodecom/sdk-python](https://github.com/geonodecom/sdk-python) |
| TypeScript SDK | [geonodecom/sdk-typescript](https://github.com/geonodecom/sdk-typescript) |
| LangChain | [geonodecom/integration-langchain](https://github.com/geonodecom/integration-langchain) |
| CrewAI | [geonodecom/integration-crewai](https://github.com/geonodecom/integration-crewai) |
| n8n | [geonodecom/integration-n8n](https://github.com/geonodecom/integration-n8n) |
| Make | [geonodecom/integration-make](https://github.com/geonodecom/integration-make) |
| Zapier | [geonodecom/integration-zapier](https://github.com/geonodecom/integration-zapier) |

</details>

Agent skills are documentation resources, not an integration. The [skills source](https://github.com/geonodecom/skills) remains private and the agent setup guide is currently in review; use the [current MCP documentation](https://docs.geonode.com/docs/scraper-api/guides/mcp/00_overview) for assistant setup.

## Account, usage and support

Authenticated requests use your Geonode plan and limits. [Read the API pricing guide](https://docs.geonode.com/docs/scraper-api/additional-resources/pricing). Assistants and automation platforms may have separate subscriptions.

**[Sign up to get 10,000 free credits](https://app.geonode.com/sign-up)** &nbsp; · &nbsp; [Get help](https://geonode.com/contact) &nbsp; · &nbsp; [Browse all integrations](https://geonode.com/integrations)
