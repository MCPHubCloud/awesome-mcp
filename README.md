# awesome-mcp
A collection of **Model Context Protocol** (MCP) servers/clients. 
The project is actively maintained and welcomes contributions or pull requests (PRs) to help improve it further

**mcphub.cloud aims to hosting mcp servers to make mcp easy use for everyone. (On the way)**

## Model Context Protocol
The Model Context Protocol (MCP), an open-standard developed by Anthropic, addresses challenges in integrating large language models (LLMs) with external data sources, tools, and resources. It standardizes how LLMs interact with these systems, simplifying tasks like input handling and data processing to enhance AI applications' practicality and security.

MCP acts as a standardized bridge, enabling seamless access for LLMs to diverse data sources and tools while ensuring reliable and safe interactions in AI development. This protocol reduces complexity by providing a unified framework for connecting models with external systems.

For more detail usage or develop, you can visit https://modelcontextprotocol.io/introduction.

### Marks
**Organization**
- Official:  From ModelContextProtocol (github.com/modelcontextprotocol/servers)
- ThirdParty: From developers

**Deploy mode**
- 🖥️ Local
- ☁️  Cloud
- 🧩 Hosted by mcp provider

### Catagory
- 📂 - [Browser Automation](https://github.com/MCPHubCloud/awesome-mcp#-browser-automation)
- 🎨 - [Art & Culture](https://github.com/MCPHubCloud/awesome-mcp#-art--culture)
- ☁️  - [Cloud Platforms](https://github.com/MCPHubCloud/awesome-mcp#%EF%B8%8F-cloud-platforms)
- 🖥️ - [Command Line](https://github.com/MCPHubCloud/awesome-mcp#%EF%B8%8F-command-line)
- 💬 - [Communication](https://github.com/MCPHubCloud/awesome-mcp#-communication)
- 👤 - [Customer Data Platforms](https://github.com/MCPHubCloud/awesome-mcp#-customer-data-platforms)
- 🗄️ - [Databases](https://github.com/MCPHubCloud/awesome-mcp#%EF%B8%8F-databases)
- 🛠️ - [Developer Tools](https://github.com/MCPHubCloud/awesome-mcp#-developer-tools)
- 📂 - [File Systems](https://github.com/MCPHubCloud/awesome-mcp#-file-systems)
- 💰 - [Finance & Fintech](https://github.com/MCPHubCloud/awesome-mcp#finance--fintech)
- 🎮 - [Gaming](https://github.com/MCPHubCloud/awesome-mcp#-gaming)
- 🧠 - [Knowledge & Memory](https://github.com/MCPHubCloud/awesome-mcp#-knowledge--memory)
- 🗺️ - [Location Services](https://github.com/MCPHubCloud/awesome-mcp#%EF%B8%8F--location-services)
- 🎯 - [Marketing](https://github.com/MCPHubCloud/awesome-mcp#-marketing)
- 📊 - [Monitoring](https://github.com/MCPHubCloud/awesome-mcp#-monitoring)
- 🔎 - [Search](https://github.com/MCPHubCloud/awesome-mcp#-search)
- 🔒 - [Security](https://github.com/MCPHubCloud/awesome-mcp#-security)
- 🚆 - [Travel & Transportation](https://github.com/MCPHubCloud/awesome-mcp#-travel--transportation)
- 🔄 - [Version Control](https://github.com/MCPHubCloud/awesome-mcp#-version-control)
- 🛠️ - [Other Tools and Integrations](https://github.com/MCPHubCloud/awesome-mcp#%EF%B8%8F-other-tools-and-integrations)

## MCP Servers

### 📂 Browser Automation
Web content access and automation capabilities. Enables searching, scraping, and processing web content in AI-friendly formats.

- [@blackwhite084/playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp) - An MCP python server using Playwright for browser automation,more suitable for llm
- [@executeautomation/playwright-mcp-server](https://github.com/executeautomation/mcp-playwright) - An MCP server using Playwright for browser automation and webscrapping
- [@microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) - A Model Context Protocol (MCP) server that provides browser automation capabilities using Playwright
- [@automatalabs/mcp-server-playwright](https://github.com/Automata-Labs-team/MCP-Server-Playwright) - An MCP server for browser automation using Playwright
- [@modelcontextprotocol/server-puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) - Browser automation for web scraping and interaction
- [@kimtaeyoon83/mcp-server-youtube-transcript](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript) - Fetch YouTube subtitles and transcripts for AI analysis
- [@recursechat/mcp-server-apple-shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) - An MCP Server Integration with Apple Shortcuts
- [@kimtth/mcp-aoai-web-browsing](https://github.com/kimtth/mcp-aoai-web-browsing) - A `minimal`server/client MCP implementation using Azure OpenAI and Playwright.
- [@pskill9/web-search](https://github.com/pskill9/web-search) - An MCP server that enables free web searching using Google search results, with no API keys required.
- [@co-browser/browser-use-mcp-server](https://github.com/co-browser/browser-use-mcp-server) - browser-use packaged as an MCP server with SSE transport. includes a dockerfile to run chromium in docker + a vnc server.
- [Firecrawl MCP Server](https://github.com/mendableai/firecrawl-mcp-server) - Official Firecrawl MCP Server - Adds powerful web scraping to Cursor, Claude and any other LLM clients.
- [Fetch MCP Server](https://github.com/modelcontextprotocol/servers/src/fetch) - Web content fetching and conversion for efficient LLM usage

### 🎨 Art & Culture

Access and explore art collections, cultural heritage, and museum databases. Enables AI models to search and analyze artistic and cultural content.

  
- [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp) - Add, Analyze, Search, and Generate Video Edits from your Video Jungle Collection
- [r-huijts/rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp) - Rijksmuseum API integration for artwork search, details, and collections
- [yuna0x0/anilist-mcp](https://github.com/yuna0x0/anilist-mcp) - A MCP server integrating AniList API for anime and manga information



### ☁️ Cloud Platforms

Cloud platform service integration. Enables management and interaction with cloud infrastructure and services.

  

- [Cloudflare MCP Server](https://github.com/cloudflare/mcp-server-cloudflare) - Integration with Cloudflare services including Workers, KV, R2, and D1
- [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) - A lightweight but powerful server that enables AI assistants to execute AWS CLI commands, use Unix pipes, and apply prompt templates for common AWS tasks in a safe Docker environment with multi-architecture support
- [Kubernetes MCP Server](https://github.com/strowk/mcp-k8s-go) - Kubernetes cluster operations through MCP
- [@flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) - Typescript implementation of Kubernetes cluster operations for pods, deployments, services.
- [@manusa/Kubernetes MCP Server](https://github.com/manusa/kubernetes-mcp-server) - A powerful Kubernetes MCP server with additional support for OpenShift. Besides providing CRUD operations for **any**Kubernetes resource, this server provides specialized tools to interact with your cluster.
- [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye) MCP Server for kubernetes management, and analyze your cluster, application health
- [johnneerdael/netskope-mcp](https://github.com/johnneerdael/netskope-mcp) - An MCP to give access to all Netskope Private Access components within a Netskope Private Access environments including detailed setup information and LLM examples on usage.
- [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) - A Terraform MCP server allowing AI assistants to manage and operate Terraform environments, enabling reading configurations, analyzing plans, applying configurations, and managing Terraform state.
-  [Aws Kb Retrieval Server](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-kb-retrieval-server) - An MCP server implementation for retrieving information from the AWS Knowledge Base using the Bedrock Agent Runtime.

### 🖥️ Command Line

Run commands, capture output and otherwise interact with shells and command line tools.

- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) - A Model Context Protocol server that provides access to iTerm. You can run commands and ask questions about what you see in the iTerm terminal.
- [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) - Run any command with `run_command` and `run_script` tools.
- [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) - Command line interface with secure execution and customizable security policies
- [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server) A secure shell command execution server implementing the Model Context Protocol (MCP)

### 💬 Communication 

Integration with communication platforms for message management and channel operations. Enables AI models to interact with team communication tools.

  

- [zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp) - An MCP server to Manage Google Tasks
- [hannesrudolph/imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server) - An MCP server that provides safe access to your iMessage database through Model Context Protocol (MCP), enabling LLMs to query and analyze iMessage conversations with proper phone number validation and attachment handling
- [@modelcontextprotocol/server-slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) - Slack workspace integration for channel management and messaging
- [@modelcontextprotocol/server-bluesky](https://github.com/keturiosakys/bluesky-context-server) - Bluesky instance integration for querying and interaction
- [MarkusPfundstein/mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite) - Integration with gmail and Google Calendar.
- [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit) - Interact with Twitter search and timeline
- [gotoolkits/wecombot](https://github.com/gotoolkits/mcp-wecombot-server.git) - An MCP server application that sends various types of messages to the WeCom group robot.
- [AbdelStark/nostr-mcp](https://github.com/AbdelStark/nostr-mcp) - A Nostr MCP server that allows to interact with Nostr, enabling posting notes, and more.
- [elie222/inbox-zero](https://github.com/elie222/inbox-zero/tree/main/apps/mcp-server) - An MCP server for Inbox Zero. Adds functionality on top of Gmail like finding out which emails you need to reply to or need to follow up on.
- [carterlasalle/mac_messages_mcp](https://github.com/carterlasalle/mac_messages_mcp) - An MCP server that securely interfaces with your iMessage database via the Model Context Protocol (MCP), allowing LLMs to query and analyze iMessage conversations. It includes robust phone number validation, attachment processing, contact management, group chat handling, and full support for sending and receiving messages.
- [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp) - This is an MCP server for interacting with the VRChat API. You can retrieve information about friends, worlds, avatars, and more in VRChat.
- [arpitbatra123/mcp-googletasks](https://github.com/arpitbatra123/mcp-googletasks) - An MCP server to interface with the Google Tasks API

### 👤 Customer Data Platforms

Provides access to customer profiles inside of customer data platforms

  

- [sergehuber/inoyu-mcp-unomi-server](https://github.com/sergehuber/inoyu-mcp-unomi-server) - An MCP server to access and updates profiles on an Apache Unomi CDP server.
- [OpenDataMCP/OpenDataMCP](https://github.com/OpenDataMCP/OpenDataMCP) - Connect any Open Data to any LLM with Model Context Protocol.
- [tinybirdco/mcp-tinybird](https://github.com/tinybirdco/mcp-tinybird) - An MCP server to interact with a Tinybird Workspace from any MCP client.
- [@iaptic/mcp-server-iaptic](https://github.com/iaptic/mcp-server-iaptic) - Connect with [iaptic](https://www.iaptic.com/) to ask about your Customer Purchases, Transaction data and App Revenue statistics.

### 🗄️ Databases

Secure database access with schema inspection capabilities. Enables querying and analyzing data with configurable security controls including read-only access.

  

- [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server) - MCP service for Tablestore, features include adding documents, semantic search for documents based on vectors and scalars, RAG-friendly, and serverless.
- [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) - MCP Server implementation that provides Elasticsearch interaction
- [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) - Airtable database integration with schema inspection, read and write capabilities
- [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp) - Connect AI tools directly to Airtable. Query, create, update, and delete records using natural language. Features include base management, table operations, schema manipulation, record filtering, and data migration through a standardized MCP interface.
- [LucasHild/mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery)  - BigQuery database integration with schema inspection and query capabilities
- [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) - TiDB database integration with schema inspection and query capabilities
- [ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) - Server implementation for Google BigQuery integration that enables direct BigQuery database access and querying capabilities
- [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) - ClickHouse database integration with schema inspection and query capabilities
- [get-convex/convex-backend](https://stack.convex.dev/convex-mcp-server) - Convex database integration to introspect tables, functions, and run oneoff queries ([Source](https://github.com/get-convex/convex-backend/blob/main/npm-packages/convex/src/cli/mcp.ts))
- [@gannonh/firebase-mcp](https://github.com/gannonh/firebase-mcp) - Firebase services including Auth, Firestore and Storage.
- [jovezhong/mcp-timeplus](https://github.com/jovezhong/mcp-timeplus) - MCP server for Apache Kafka and Timeplus. Able to list Kafka topics, poll Kafka messages, save Kafka data locally and query streaming data with SQL via Timeplus
- [@fireproof-storage/mcp-database-server](https://github.com/fireproof-storage/mcp-database-server) - Fireproof ledger database with multi-user sync
- [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) - MySQL database integration with configurable access controls, schema inspection, and comprehensive security guidelines
- [f4ww4z/mcp-mysql-server](https://github.com/f4ww4z/mcp-mysql-server) - Node.js-based MySQL database integration that provides secure MySQL database operations
- [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server) – A high-performance multi-database MCP server built with Golang, supporting MySQL & PostgreSQL (NoSQL coming soon). Includes built-in tools for query execution, transaction management, schema exploration, query building, and performance analysis, with seamless Cursor integration for enhanced database workflows.
- [@modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - PostgreSQL database integration with schema inspection and query capabilities
- [@modelcontextprotocol/server-sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) - SQLite database operations with built-in analysis features
- [@joshuarileydev/supabase-mcp-server](https://github.com/joshuarileydev/supabase) - Supabase MCP Server for managing and creating projects and organisations in Supabase
- [@alexanderzuev/supabase-mcp-server](https://github.com/alexander-zuev/supabase-mcp-server) - Supabase MCP Server with support for SQL query execution and database exploration tools
- [ktanaka101/mcp-server-duckdb](https://github.com/ktanaka101/mcp-server-duckdb) - DuckDB database integration with schema inspection and query capabilities
- [Dataring-engineering/mcp-server-trino](https://github.com/Dataring-engineering/mcp-server-trino) - Trino MCP Server to query and access data from Trino Clusters.
- [furey/mongodb-lens](https://github.com/furey/mongodb-lens) - MongoDB Lens: Full Featured MCP Server for MongoDB Databases
- [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp) - MongoDB integration that enables LLMs to interact directly with databases.
- [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) - A Model Context Protocol Server for MongoDB
- [tinybirdco/mcp-tinybird](https://github.com/tinybirdco/mcp-tinybird) - Tinybird integration with query and API capabilities
- [KashiwaByte/vikingdb-mcp-server](https://github.com/KashiwaByte/vikingdb-mcp-server) - VikingDB integration with collection and index introduction, vector store and search capabilities.
- [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) - Model Context Protocol with Neo4j
- [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) MCP server for Nile's Postgres platform - Manage and query Postgres databases, tenants, users, auth using LLMs
- [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) - Snowflake integration implementing read and (optional) write operations as well as insight tracking
- [hannesrudolph/sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) - An MCP server that provides safe, read-only access to SQLite databases through Model Context Protocol (MCP). This server is built with the FastMCP framework, which enables LLMs to explore and query SQLite databases with built-in safety features and query validation.
- [sirmews/mcp-pinecone](https://github.com/sirmews/mcp-pinecone) - Pinecone integration with vector search capabilities
- [runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy) 
-  [Redis MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/redis) - A Model Context Protocol server that provides access to Redis databases. This server enables LLMs to interact with Redis key-value stores through a set of standardized tools.
- [edwinbernadus/nocodb-mcp-server](https://github.com/edwinbernadus/nocodb-mcp-server) - MCP Server for NocoDB database. Read and write capabilities

### 💻 Developer Tools

Tools and integrations that enhance the development workflow and environment management.

- [21st-dev/Magic-MCP](https://github.com/21st-dev/magic-mcp) - Create crafted UI components inspired by the best 21st.dev design engineers.
- [Coment-ML/Opik-MCP](https://github.com/comet-ml/opik-mcp) - Talk to your LLM observability, traces and monitoring captured by Opik using natural language.
- [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) - Provide coding agents direct access to Figma data to help them one-shot design implementation.
- [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp) - Docker container management and operations through MCP
- [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) - An MCP server to flexibly fetch JSON, text, and HTML data
- [r-huijts/xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server) - Xcode integration for project management, file operations, and build automation
- [snaggle-ai/openapi-mcp-server](https://github.com/snaggle-ai/openapi-mcp-server) - Connect any HTTP/REST API server using an Open API spec (v3)
- [jetbrains/mcpProxy](https://github.com/JetBrains/mcpProxy) - Connect to JetBrains IDE
- [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor) - A line-oriented text file editor. Optimized for LLM tools with efficient partial file access to minimize token usage.
- [@joshuarileydev/simulator-mcp-server](https://github.com/JoshuaRileyDev/simulator-mcp-server) - An MCP server to control iOS Simulators
- [@haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) - An Excel manipulation server providing workbook creation, data operations, formatting, and advanced features (charts, pivot tables, formulae).
- [xcodebuild](https://github.com/ShenghaiWang/xcodebuild) Build iOS Xcode workspace/project and feed back errors to llm.
- [@jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) - An MCP Server and VS Code Extension which enables (language agnostic) automatic debugging via breakpoints and expression evaluation.
- [@Jktfe/serveMyAPI](https://github.com/Jktfe/serveMyAPI) - A personal MCP (Model Context Protocol) server for securely storing and accessing API keys across projects using the macOS Keychain.
- [@xzq.xu/jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server) - An implementation project of a JVM-based MCP (Model Context Protocol) server.
- [@yangkyeongmo@/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) - MCP server that connects to [Apache Airflow](https://airflow.apache.org/) using official client.
- [hyperb1iss/droidmind](https://github.com/hyperb1iss/droidmind) - Control Android devices with AI through MCP, enabling device control, debugging, system analysis, and UI automation with a comprehensive security framework.
- [Rootly-AI-Labs/Rootly-MCP-server](https://github.com/Rootly-AI-Labs/Rootly-MCP-server) - MCP server for the incident management platform [Rootly](https://rootly.com/).
- [YuChenSSR/mindmap-mcp-server](https://github.com/YuChenSSR/mindmap-mcp-server) - A Model Context Protocol (MCP) server for generating a beautiful interactive mindmap.
-  [BlenderMCP](https://github.com/ahujasid/blender-mcp) - BlenderMCP connects Blender to Claude AI through the Model Context Protocol (MCP), allowing Claude to directly interact with and control Blender. This integration enables prompt assisted 3D modeling, scene creation, and manipulation.
- [Figma MCP Server](https://github.com/GLips/Figma-Context-MCP) - MCP server to provide Figma layout information to AI coding agents like Cursor
- [github/github-mcp-server](https://github.com/github/github-mcp-server) - The GitHub MCP Server is a Model Context Protocol (MCP) server that provides seamless integration with GitHub APIs, enabling advanced automation and interaction capabilities for developers and tools.

### 📂 File Systems


### 💰Finance & Fintech

- [ferdousbhai/tasty-agent](https://github.com/ferdousbhai/tasty-agent) - Tastyworks API integration to handle trading activities on Tastytrade
- [ferdousbhai/investor-agent](https://github.com/ferdousbhai/investor-agent) - Yahoo Finance integration to fetch stock market data including options recommendations
- [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) - Comprehensive blockchain services for 30+ EVM networks, supporting native tokens, ERC20, NFTs, smart contracts, transactions, and ENS resolution.
- [bankless/onchain-mcp](https://github.com/Bankless/onchain-mcp/) - Bankless Onchain API to interact with smart contracts, query transaction and token information
- [kukapay/cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server) - Providing latest cryptocurrency news to AI agents, powered by CryptoPanic.

### 🎮 Gaming



### 🧠 Knowledge & Memory



### 🗺️  Location Services


### 🎯 Marketing

- [Open Strategy Partners Marketing Tools](https://github.com/open-strategy-partners/osp_marketing_tools) - A suite of marketing tools from Open Strategy Partners including writing style, editing codes, and product marketing value map creation.

### 📊 Monitoring



### 🔎 Search
- [Perplexity Ask MCP Server](https://github.com/ppl-ai/modelcontextprotocol) - A Model Context Protocol Server connector for Perplexity API, to enable web search without leaving the MCP ecosystem
- ✨[ArXiv MCP Server](https://github.com/blazickjp/arxiv-mcp-server) - The ArXiv MCP Server provides a bridge between AI assistants and arXiv's research repository through the Message Control Protocol (MCP)


### 🔒 Security

- [VirusTotal MCP Server](https://github.com/BurtTheCoder/mcp-virustotal) - MCP server for querying the VirusTotal API. This server provides tools for scanning URLs, analyzing file hashes, and retrieving IP address reports.
- [ORKL MCP Server](https://github.com/fr0gger/MCP_Security) - MCP server for querying the ORKL API. This server provides tools for fetching threat reports, analyzing threat actors, and retrieving intelligence sources.
- [Security Audit MCP Server](https://github.com/qianniuspace/mcp-security-audit) A powerful MCP (Model Context Protocol) Server that audits npm package dependencies for security vulnerabilities. Built with remote npm registry integration for real - time security checks.

### 🚆 Travel & Transportation


### 🔄 Version Control

- [masondelan/selvedge](https://github.com/masondelan/selvedge) - Live capture of *why* AI agents change code. Local SQLite, seven MCP tools including `prior_attempts` (the agent reads prior reasoning before it edits), entity-level history with reasoning. Python 3.10+, MIT. 🖥️ Local.


### 🛠️ Other Tools and Integrations

- [sirmews/apple-notes-mcp](https://github.com/sirmews/apple-notes-mcp) - Allows the AI to read from your local Apple Notes database (macOS only)
- [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server) - Coinmarket API integration to fetch cryptocurrency listings and quotes
- [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server) - Interacting with Notion API
- [amidabuddha/unichat-mcp-server](https://github.com/amidabuddha/unichat-mcp-server) - Send requests to OpenAI, MistralAI, Anthropic, xAI, Google AI or DeepSeek using MCP protocol via tool or predefined prompts. Vendor API key required
- [evalstate/mcp-miro](https://github.com/evalstate/mcp-miro) - Access MIRO whiteboards, bulk create and read items. Requires OAUTH key for REST API.
- [@tacticlaunch/mcp-linear](https://github.com/tacticlaunch/mcp-linear) - Integrates with Linear project management system
- [pierrebrunelle/mcp-server-openai](https://github.com/pierrebrunelle/mcp-server-openai) - Query OpenAI models directly from Claude using MCP protocol
- [@modelcontextprotocol/server-everything](https://github.com/modelcontextprotocol/servers/tree/main/src/everything) - MCP server that exercises all the features of the MCP protocol
- [baba786/phabricator-mcp-server](https://github.com/baba786/phabricator-mcp-server) - Interacting with Phabricator API
- [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) - Interacting with Obsidian via REST API
- [calclavia/mcp-obsidian](https://github.com/calclavia/mcp-obsidian) - This is a connector to allow Claude Desktop (or any MCP client) to read and search any directory containing Markdown notes (such as an Obsidian vault).
- [anaisbetts/mcp-youtube](https://github.com/anaisbetts/mcp-youtube) - Fetch YouTube subtitles
- [@pskill9/hn-server](https://github.com/pskill9/hn-server) - Parses the HTML content from [news.ycombinator.com](https://news.ycombinator.com/) (Hacker News) and provides structured data for different types of stories (top, new, ask, show, jobs).
- [@mediar-ai/screenpipe](https://github.com/mediar-ai/screenpipe) - Local - first system capturing screen/audio with timestamped indexing, SQL/embedding storage, semantic search, LLM - powered history analysis, and event - triggered actions - enables building context - aware AI agents through a NextJS plugin ecosystem.
- [akseyh/bear-mcp-server](https://github.com/akseyh/bear-mcp-server) - Allows the AI to read from your Bear Notes (macOS only)
- [mcp-server-jfx](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jfx) - Draw on JavaFX canvas.
- [hmk/attio-mcp-server](https://github.com/hmk/attio-mcp-server) - Allows AI clients to manage records and notes in Attio CRM
- [NON906/omniparser-autogui-mcp](https://github.com/NON906/omniparser-autogui-mcp) - Automatic operation of on - screen GUI.
- [kj455/mcp-kibela](https://github.com/kj455/mcp-kibela) - Allows AI models to interact with [Kibela](https://kibe.la/)
- [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql) - Allows the AI to query GraphQL servers
- [@awkoy/replicate-flux-mcp](https://github.com/awkoy/replicate-flux-mcp) - Provides the ability to generate images via Replicate's API.
- [kenliao94/mcp-server-rabbitmq](https://github.com/kenliao94/mcp-server-rabbitmq) - Enable interaction (admin operation, message enqueue/dequeue) with RabbitMQ
- [marcelmarais/Spotify](https://github.com/marcelmarais/spotify-mcp-server) - Control Spotify playback and manage playlists.
- [NakaokaRei/swift-mcp-gui](https://github.com/NakaokaRei/swift-mcp-gui.git) - MCP server that can execute commands such as keyboard input and mouse movement
- [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) - Chat with any other OpenAI SDK Compatible Chat Completions API, like Perplexity, Groq, xAI and more
- [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer) - An MCP server that installs other MCP servers for you.
- [tanigami/mcp-server-perplexity](https://github.com/tanigami/mcp-server-perplexity) - Interacting with Perplexity API.
- [future-audiences/wikimedia-enterprise-model-context-protocol](https://gitlab.wikimedia.org/repos/future-audiences/wikimedia-enterprise-model-context-protocol) - Wikipedia Article lookup API
- [andybrandt/mcp-simple-timeserver](https://github.com/andybrandt/mcp-simple-timeserver) - An MCP server that allows checking local time on the client machine or current UTC time from an NTP server
- [Time MCP Server](https://github.com/modelcontextprotocol/servers/blob/main/src/time) - A Model Context Protocol server that provides time and timezone conversion capabilities. This server enables LLMs to get current time information and perform timezone conversions using IANA timezone names, with automatic system timezone detection.
- [zueai/mcp-manager](https://github.com/zueai/mcp-manager) - Simple Web UI to install and manage MCP servers for Claude Desktop App.
- [wong2/mcp-cli](https://github.com/wong2/mcp-cli) - CLI tool for testing MCP servers
- [isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) - Generate visualizations from fetched data using the VegaLite format and renderer.
- [tevonsb/homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp) - Access Home Assistant data and control devices (lights, switches, thermostats, etc).
- [allenporter/mcp-server-home-assistant](https://github.com/allenporter/mcp-server-home-assistant) - Expose all Home Assistant voice intents through a Model Context Protocol Server allowing home control.
- [@magarcia/mcp-server-giphy](https://github.com/magarcia/mcp-server-giphy) - Search and retrieve GIFs from Giphy's vast library through the Giphy API.
- [nguyenvanduocit/all-in-one-model-context-protocol](https://github.com/nguyenvanduocit/all-in-one-model-context-protocol) - Some useful tools for developer, almost everything an engineer need: confluence, Jira, Youtube, run script, knowledge base RAG, fetch URL, Manage youtube channel, emails, calendar, gitlab
- [@joshuarileydev/mac-apps-launcher-mcp-server](https://github.com/JoshuaRileyDev/mac-apps-launcher) - An MCP server to list and launch applications on MacOS
- [ZeparHyfar/mcp-datetime](https://github.com/ZeparHyfar/mcp-datetime) - MCP server providing date and time functions in various formats
- [SecretiveShell/MCP-wolfram-alpha](https://github.com/SecretiveShell/MCP-wolfram-alpha) - An MCP server for querying wolfram alpha API.
- [awwaiid/mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior) - An MCP server for basic local taskwarrior usage (add, update, remove tasks)
- [Sequential Thinking MCP Server](https://github.com/modelcontextprotocol/servers/tree/HEAD/src/sequentialthinking) - An MCP server implementation that provides a tool for dynamic and reflective problem-solving through a structured thinking process.
- [AgentQL MCP Server](https://github.com/tinyfish-io/agentql-mcp) - Model Context Protocol server that integrates AgentQL's data extraction capabilities.


## MCP SDK
- [mcp-golang](https://github.com/metoro-io/mcp-golang) - mcp-golang is an unofficial implementation of the Model Context Protocol in Go.
- [mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) - The mcp-proxy is a tool that lets you switch between server transports. There are two supported modes: stdio-sse, sse-stdio


## Star History

<a href="https://www.star-history.com/#MCPHubCloud/awesome-mcp&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=MCPHubCloud/awesome-mcp&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=MCPHubCloud/awesome-mcp&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=MCPHubCloud/awesome-mcp&type=Date" />
 </picture>
</a>


## Thanks
most mcp list come from https://github.com/punkpeye/awesome-mcp-servers which is the popular awesome  project of mcps;
