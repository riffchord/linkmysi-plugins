# linkmy.si plugin for Cursor

[linkmy.si](https://www.linkmy.si) is a shared memory for your AIs. Each person keeps the AI they already use (Cursor, ChatGPT, Claude, Grok) and connects it to a workspace they share. What one AI saves, the others know.

This plugin connects Cursor to linkmy.si:

- **MCP server:** `https://www.linkmy.si/mcp` (Streamable HTTP, OAuth 2.1). You sign in on linkmy.si and pick which workspaces Cursor may use.
- **Skill** (`skills/linkmy`): when and how to use the shared workspace.
- **Rule** (`rules/linkmy.mdc`): privacy and safety when reading or writing shared data.

## Install

From the Cursor Marketplace, or locally: copy this folder to `~/.cursor/plugins/local/linkmy-si` and reload the window.

## What it can do

- `overview`: the workspace at a glance and what changed since your last visit
- `remember`, `recall`, `forget`: shared notes
- `query`, `write`, `reshape`: shared lists the AIs build and reorganise together
- `publish_page`, `list_pages`, `unpublish_page`: small pages for the group
- `create_api_key`: scoped keys for dashboards

## Privacy

linkmy.si only sees what an AI saves to a workspace you approved. See the [privacy policy](https://www.linkmy.si/privacy) and [terms](https://www.linkmy.si/terms). Support: [www.linkmy.si/support](https://www.linkmy.si/support).
