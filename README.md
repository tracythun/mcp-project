# Project Setup and Run Instructions

## Overview

This project requires Python and several dependencies including `uv`, `Claude`, and `mcp`. Follow the steps below to set up your environment and run the server.

---

## Prerequisites

1. **Python**  
   Download and install Python from the official site:  
   [https://www.python.org/downloads/](https://www.python.org/downloads/)  
   Make sure Python is added to your system environment variables (PATH).

2. **uv**  
   Install `uv` by following the instructions here:  
   [Installation | uv](https://github.com/your-uv-link)  
   *(Replace this link with the actual URL to the uv installation guide.)*

3. **Claude**  
   Download and install Claude from the official source.  

4. **mcp**  
   Install `mcp` using pip:  
   ```bash
   pip install mcp
   
For more information and detailed setup steps, visit the [mcp PyPI page.](https://pypi.org/project/mcp/)

## Running the Server

After installing all prerequisites, you can install and run the server with Claude Desktop:
uv run mcp install server.py

To start the development server, run:
uv run mcp dev server.py

Notes
Ensure all environment variables are properly set, especially Python in your PATH.
The server.py script is the main entry point to start the server.
Use Claude Desktop to interact with the server seamlessly.
