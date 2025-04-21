# MCP First

This project serves as a foundational implementation of a Model Context Protocol (MCP) server using Python. It is designed to expose simple tools and resources to Large Language Models (LLMs), facilitating structured interactions and data access.

## 🚀 Overview

The MCP server in this repository provides:

- **Tools**: Functions that can be invoked by LLMs to perform specific tasks.
- **Resources**: Data endpoints that LLMs can query to retrieve information.

This setup is ideal for experimenting with MCP concepts and understanding how LLMs can interact with external tools and data sources.

## 📁 Project Structure

```
mcp_first/
├── app.py               # Main application file initializing the MCP server
├── main.py              # Entry point to start the server
├── browser_mcp.json     # Configuration for MCP client integration
├── pyproject.toml       # Project metadata and dependencies
├── uv.lock              # Lock file for dependency management
├── .python-version      # Specifies the Python version used
├── .gitignore           # Git ignore file
└── README.md            # Project documentation
```

## 🛠️ Prerequisites

Ensure you have the following installed:

- Python 3.10 or higher
- [uv](https://astral.sh/uv/) package manager

## ⚙️ Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/anand23124/mcp_first.git
   cd mcp_first
   ```

2. **Set up the environment:**

   ```bash
   uv venv
   uv pip install -r requirements.txt
   ```

## 🚀 Running the Server

To start the MCP server:

```bash
python main.py
```

The server will initialize and be ready to handle requests from MCP-compatible clients.

## 🧪 Testing the Server

You can test the server using MCP clients or tools that support the protocol. Ensure that your client is configured to communicate with the server's endpoint.

## 📄 Configuration

The `browser_mcp.json` file contains configurations for integrating the MCP server with browser-based clients. Ensure that this file is correctly set up to match your client's requirements.

## 🤝 Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

## 📄 License

This project is licensed under the MIT License.
