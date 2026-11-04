# Dockito for AI tools

[Dockito](https://dockito.ai) is one home for docs, live sheets, Slides, boards, API docs and database designs, made by Humans and AI. Your AI publishes and edits them through Dockito's MCP server; your team works in them in the browser, live.

This repo holds the install files for AI tools. Dockito's source is not here.

## Claude Code

```
/plugin marketplace add dockito-ai/dockito-plugins
/plugin install dockito@dockito
```

The plugin connects Dockito's MCP server and adds the Dockito skill, which also uses the `dockito` CLI when it's installed (`brew install dockito-ai/tap/dockito`).

## Gemini CLI

```
gemini extensions install https://github.com/dockito-ai/dockito-plugins
```

## Anything else

Add the MCP server `https://dockito.ai/mcp` (streamable HTTP; sign in with your Dockito account). Steps for Claude, ChatGPT, Cursor, VS Code, Codex and others: https://dockito.ai/help/agents/connect

Support: hello@dockito.ai · [Privacy](https://dockito.ai/legal/privacy) · [Terms](https://dockito.ai/legal/terms)
