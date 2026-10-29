from pathlib import Path

content = """# Shirokane Family Website 💗

## Description
Introducing the **Shirokane Family Website** — a cute little home for the Shirokane Family, a family of **14 adorable sisters**! 🌸

## Installation
Run the development server with:

```bash
npm run dev
```

Then open the local URL shown in your terminal.

## Current Status
🟢 **Active**
"""

path = Path("/mnt/data/README.md")
path.write_text(content, encoding="utf-8")
print(f"Created: {path}")
