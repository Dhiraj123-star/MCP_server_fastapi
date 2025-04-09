# MCP_server_fastapi
---

## 🚀 Getting Started

Follow the steps below to install dependencies, run the server, and debug your tools locally.

---

### 📦 Install Dependencies

Use [`uv`](https://github.com/astral-sh/uv) (a faster Python package manager) to install project dependencies:

```bash
uv pip install -r pyproject.toml
```

---

### ▶️ Start the Server

You can run the server using one of the following options:

**Option 1: Using Python**
```bash
python src/server.py
```

**Option 2: Using `uv`**
```bash
uv run start
```

---

### 🧪 Debug and Test

You can test your tool locally using [MCP Inspector](https://mcp.tools/):

```bash
mcp dev ./src/weather.py
```

---

### 🛠 Requirements

- Python 3.12+
- [`uv`](https://github.com/astral-sh/uv) installed
- [`mcp`](https://pypi.org/project/mcp/) CLI installed

---
