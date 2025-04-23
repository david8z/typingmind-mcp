# TypingMind MCP Server

A simple Node.js project to run the TypingMind MCP server.

## Setup

1. Install dependencies:

```bash
npm install
```

2. Create a `.env` file in the root directory with your MCP key:

```bash
MCP_KEY=your_mcp_key_here
PORT=8080
```

## Usage

To start the MCP server:

```bash
npm start
```

The server will use the environment variables from your `.env` file. Make sure to never commit your `.env` file to version control!
