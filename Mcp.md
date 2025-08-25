<img width="1592" height="976" alt="image" src="https://github.com/user-attachments/assets/aef9b67d-9d87-42e6-bfd5-1a81712a0aa6" />

- [Source](https://www.youtube.com/watch?v=yC_u4fkPutg&list=PL4cUxeGkcC9joeiiVaLExvfSgmdtBbSPM&index=9)
- Allows agents to communicate with external services and APIs.
- MCP provides list of tools available.

---

mcp-postgres-client -> mcp-postgres-server -> postgres-db

- MCP Server → provides access to some resource or tool (e.g., Postgres DB, GitHub, Google Drive). It “serves” capabilities.
- MCP Client → connects to those servers, requests lists of tools/resources, calls tools, and fetches results.

---

- If you want to expose your own API or service via MCP → you implement an MCP Server.
- If you want to use existing MCP servers in your AI agent/app → you implement an MCP Client.
