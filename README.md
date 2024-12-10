# Awesome MCP Servers

> A curated list of Model Context Protocol (MCP) servers

## Reference Implementation Servers

- **[Filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)** - Secure file operations with configurable access controls
- **[GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/github)** - Repository management, file operations, and GitHub API integration
- **[GitLab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab)** - GitLab API, enabling project management
- **[Git](https://github.com/modelcontextprotocol/servers/tree/main/src/git)** - Tools to read, search, and manipulate Git repositories
- **[Google Drive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive)** - File access and search capabilities for Google Drive
- **[PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)** - Read-only database access with schema inspection
- **[Sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite)** - Database interaction and business intelligence capabilities
- **[Slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)** - Channel management and messaging capabilities
- **[Sentry](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry)** - Retrieving and analyzing issues from Sentry.io
- **[Memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory)** - Knowledge graph-based persistent memory system
- **[Puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer)** - Browser automation and web scraping
- **[Brave Search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search)** - Web and local search using Brave's Search API
- **[Google Maps](https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps)** - Location services, directions, and place details
- **[Fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch)** - Web content fetching and conversion for efficient LLM usage

## Community Servers

- **[Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare)** - Interacting with Cloudflare services
- **[OpenAI](https://github.com/pierrebrunelle/mcp-server-openai)** - Query OpenAI models directly from Claude using MCP protocol
- **[Kagi](https://github.com/ac3xx/mcp-servers-kagi)** - Kagi search API integration
- **[Exa](https://github.com/theishangoswami/exa-mcp-server)** - Exa AI Search API
- **[Phabricator](https://github.com/baba786/phabricator-mcp-server)** - Interacting with Phabricator API
- **[Obsidian](https://github.com/MarkusPfundstein/mcp-obsidian)** - Interacting with Obsidian via REST API
- **[YouTube](https://github.com/anaisbetts/mcp-youtube)** - Fetch YouTube subtitles
- **[MCP Installer](https://github.com/anaisbetts/mcp-installer)** - Set up MCP servers in Claude Desktop
- **[Notion](https://github.com/danhilse/notion_mcp)** - Integrates with Notion's API to manage personal todo list
- **[Bluesky](https://github.com/keturiosakys/bluesky-context-server)** - integrates with Bluesky API to query and search feeds and posts.
- **[Minima](https://github.com/dmayboroda/minima)** - Local RAG (on-premises) with MCP server.
- **[Jina Reader](https://github.com/wong2/mcp-jina-reader)** - Fetch the content of a remote URL as Markdown with Jina Reader.
- **[any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp)** - Chat with any other OpenAI SDK Compatible Chat Completions API, like Perplexity, Groq, xAI and more
- **[MySQL](https://github.com/designcomputer/mysql_mcp_server)** - MySQL database integration with configurable access controls and schema inspection
- **[BigQuery](https://github.com/LucasHild/mcp-server-bigquery)** (by LucasHild) - BigQuery database integration with schema inspection and query capabilities
- **[BigQuery](https://github.com/ergut/mcp-bigquery-server)** (by ergut) - Server implementation for Google BigQuery integration that enables direct BigQuery database access and querying capabilities
- **[Windows CLI](https://github.com/SimonB97/win-cli-mcp-server)** - MCP server for secure command-line interactions on Windows systems, enabling controlled access to PowerShell, CMD, and Git Bash shells.
- **[Playwright MCP Server](https://github.com/executeautomation/mcp-playwright)** - An MCP server using Playwright for browser automation and webscrapping
- **[Perplexity](https://github.com/tanigami/mcp-server-perplexity)** - Interacting with Perplexity
- **[Docker](https://github.com/QuantGeekDev/docker-mcp)** - Run and manage docker containers, docker compose, and logs
- **[Mongo](https://github.com/QuantGeekDev/mongo-mcp)** - A Model Context Protocol (MCP) server that enables LLMs to interact directly with MongoDB databases
- **[Google Search Console](https://github.com/ahonn/mcp-server-gsc)** - A Model Context Protocol (MCP) server providing access to Google Search Console.
- **[MongoDB](https://github.com/kiliczsh/mcp-mongo-server)** - A Model Context Protocol Server for MongoDB
- **[Kubernetes](https://github.com/Flux159/mcp-server-kubernetes)** - Connect to Kubernetes cluster and manage pods, deployments, services.
- **[Pandoc](https://github.com/vivekVells/mcp-pandoc)** - MCP server for seamless document format conversion using Pandoc, supporting Markdown, HTML, and plain text, with other formats like PDF, csv and docx in development.
- **[HuggingFace Spaces](https://github.com/evalstate/mcp-hfspace)** - Server for using HuggingFace Spaces, supporting Images, Audio, Text and more. Claude Desktop mode for ease-of-use.
- **[Data Exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration)** - MCP server for autonomous data exploration on .csv-based datasets, providing intelligent insights with minimal effort.
- **[CoinCap](https://github.com/QuantGeekDev/coincap-mcp)** - A MCP server that provides real-time cryptocurrency market data through CoinCap's public API without requiring authentication
- **[Search1API](https://github.com/fatwang2/search1api-mcp)** - Search and crawl in one API
- **[mcp-framework](https://github.com/QuantGeekDev/mcp-framework)** -  ⚡️Fast and elegant Typescript framework for building MCP servers

## Clients

- **[mcp-cli](https://github.com/wong2/mcp-cli)** a cli inspector for MCP servers
- **[MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge)** 🐍 an openAI middleware proxy to use mcp in any existing openAI compatible client
- **[MCP-Chatbot](https://github.com/3choff/mcp-chatbot)** A simple yet powerful ⭐ CLI chatbot that integrates tool servers with any OpenAI-compatible LLM API.
- **[Zed](https://github.com/zed-industries/zed)** multiplayer code editor from the creators of atom
- **[genkit](https://github.com/firebase/genkit)** agent and data transformation framework
- **[Continue](https://github.com/continuedev/continue)** vscode auto complete and chat tool (full feature support)
- **[gpt-computer-assistant](https://github.com/Upsonic/gpt-computer-assistant)** dockerized mcp client with Anthropic, OpenAI and Langchain.
---

Curated by [ChatHub](https://chathub.gg/?utm_source=mcp)
