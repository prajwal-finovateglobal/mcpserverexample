# MCP3 - Model Context Protocol Server

A simple MCP server with an `add` tool for adding two numbers.

## Installation

### Using uvx (Recommended)

```json
{"mcpServers":
    {
    "test": {
        "command": "/Users/prajwalp/.local/bin/uvx",
        "args": [
        "--from",
        "git+https://github.com/prajwal-finovateglobal/mcpserverexample.git",
        "mcp-server"
        ]
    }
    }
}
```

### Local Development

```bash
# Clone and install
git clone <repository-url>
cd mcp3
uv pip install -e .

# Run the server
uv run mcp-server
```

## Available Tools

- **add**: Add two numbers (parameters: `a`, `b`)

## Usage

The server provides a simple `add` tool that takes two integers and returns their sum.