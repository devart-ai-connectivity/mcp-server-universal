# Devart MCP Server Universal

Self-hosted MCP server for secure AI access to databases and cloud applications through ODBC.

Devart MCP Server Universal helps connect AI tools to a wide range of databases and cloud applications through one MCP layer, without custom development for each source.

With self-hosted and on-premises deployment, it helps keep data inside your infrastructure and reduces the risk of exposing sensitive information through third-party SaaS services.

## Why Universal

Use one MCP layer for multiple data sources instead of deploying and maintaining a separate integration for every system.

Devart MCP Server Universal is designed for teams that need practical, secure AI-to-data access with a simpler setup and a focused product scope.

## Key benefits

- One MCP layer for multiple data sources
- Works with ODBC drivers
- Self-hosted and on-premises by design
- Keeps data inside your infrastructure
- Fast setup with a practical GUI-based configuration flow
- Easy integration with popular AI tools

## How it works

Devart MCP Server Universal sits between your AI tool and your data source.

1. An AI tool sends a natural-language request to the MCP server.
2. The MCP server processes the request and generates SQL.
3. The ODBC driver translates and sends the request to the target data source.
4. The data source returns the data.
5. The MCP server transforms the result into output suitable for AI processing.

## Connection modes

Universal MCP Server supports two connection setup modes.

### Use existing DSN

Use an existing ODBC DSN that is already configured on the machine.

### Config custom connection

Configure a custom ODBC connection directly in the product UI.

## Supported AI tools

- Claude Desktop
- GitHub Copilot
- JetBrains IDEs
- Other AI IDEs

## Typical use cases

- AI-assisted analysis across multiple databases or cloud systems
- SQL-free data access for analysts and BI teams
- Secure internal AI copilots for support, operations, and reporting workflows
- On-premises AI adoption where data should stay inside company infrastructure

## Prerequisites

- Windows environment
- A compatible ODBC driver for the target data source
- Activated driver license where required
- A supported AI tool

## Quick start

1. Install Devart MCP Server Universal
2. Prepare the required ODBC driver or DSN
3. Choose a connection mode
4. Connect your AI tool
5. Run your first query

## Documentation

- [Overview](./docs/overview.md)
- [Requirements and compatibility](./docs/requirements-and-compatibility.md)
- [Installation](./docs/installation.md)
- [Licensing](./docs/licensing-and-activation/licensing.md)
- [Activate Devart MCP Server](./docs/licensing-and-activation/activate-devart-mcp-server.md)
- [Connection configuration](./docs/connection-configuration.md)
- [AI integration](./docs/ai-integration/README.md)
- [Integrate with Claude Desktop](./docs/ai-integration/integrate-with-claude-desktop.md)
- [Integrate with GitHub Copilot](./docs/ai-integration/integrate-with-github-copilot.md)
- [Integrate with JetBrains IDE](./docs/ai-integration/integrate-with-jetbrains-ide.md)
- [Support](./docs/support.md)
- [Release notes](./docs/release-notes.md)

## Support

You can find answers to your questions and share feedback or suggestions about the product.

- [Documentation](https://docs.devart.com/)
- [Submit a Request](https://www.devart.com/company/contactform.html)
- [Suggest a Feature](https://devart.uservoice.com/)
- [Join Our Forum](https://support.devart.com/portal/en/community)
- [Trust Center](https://www.devart.com/data-connectivity/trust-center.html)

## Pricing

Universal MCP Server is planned as a paid product.

- Subscription license
- Perpetual license

## Release status

This repository is being prepared as the product shell for Devart MCP Server Universal. Code and installation artifacts may be added separately.
