# Cutline

Turn card text into print and play sheets at true card size, as a PDF.

It's a hosted MCP server, so there's nothing to install. This repo is just the listing. The server code isn't here.

## Add it

Connector URL: `https://cards.rowhousesoftware.com/mcp`

In Claude: open Settings, then Connectors, then Add custom connector. Paste the URL.

In Claude Code:

```
claude mcp add -t http cutline https://cards.rowhousesoftware.com/mcp
```

## Tools

- `make_card_sheet`: Lays out your cards as a PDF with crop marks.
- `make_token_sheet`: Lays out tokens or standees as a PDF, with cut lines.
- `list_card_sizes`: Lists the card sizes and templates, and which are free.
- `pro_status`: Says what Pro adds and checks a Pro code.

## Free and paid

Free: card sheets with the free templates. Pro is $12 one time. It adds unlimited cards and all 7 templates. You also get any color, plus tokens and standees.

## Sign in

None. It's open. No key and no sign in.

## Help

- Site: https://cards.rowhousesoftware.com
- Email: support@rowhousesoftware.com

Made by [Rowhouse Software](https://rowhousesoftware.com).
