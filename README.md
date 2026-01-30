# Clean Watermark

Raycast extension to remove watermarks, formatting, and junk from clipboard text.

## Features

- Remove zero-width characters and unicode watermarks
- Strip RTF markup, font declarations, HTML tags
- Clean Markdown formatting and GUIDs
- Collapse excess whitespace
- All processing is local (no external calls)

## Commands

| Command | Description |
|---------|-------------|
| Clean Watermark | Clean clipboard text of watermarks and formatting |

## Install

```bash
bun install
bun run build
bun run dev
```

## License

MIT
