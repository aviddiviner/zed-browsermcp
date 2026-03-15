## BrowserMCP Setup Instructions

BrowserMCP allows AI to automate your browser using the Model Context Protocol.

### Prerequisites

1. **Install the BrowserMCP Chrome Extension**

   Visit [browsermcp.io](https://browsermcp.io) and install the Chrome extension in your Chromium-based browser (Chrome, Brave, Arc, Edge, etc.).

2. **Ensure the extension is enabled**

   After installation, make sure the BrowserMCP extension is active in your browser. The extension handles the connection between the MCP server and your browser — no API keys or tokens are required.

### How It Works

- This Zed extension runs the `@browsermcp/mcp` npm package as an MCP server.
- The server communicates with the BrowserMCP Chrome extension via a local WebSocket connection.
- All automation happens locally on your machine — your browser activity stays private.

### No Settings Required

BrowserMCP does not require any configuration settings. Just install the Chrome extension and you're good to go.

### Troubleshooting

- **Tools not working?** Make sure the BrowserMCP Chrome extension is installed and enabled in your browser.
- **Browser not responding?** Try refreshing the page or restarting your browser, then restart the MCP server in Zed.
- For more help, visit the [BrowserMCP documentation](https://docs.browsermcp.io).
