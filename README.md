# Karman plugin

Ask [Karman](https://karman.si) which small Solar System bodies move in ways gravity does not explain, why, and how sure it is.

Karman is an anomaly tracker for everything above the Kármán line. This repository holds only the Claude Code plugin and the agent skill. Both talk to the read-only MCP server at `https://karman.si/mcp`; no account or key is needed.

## Claude Code

```
/plugin marketplace add samshapley/karman-plugin
/plugin install karman@karman-si
```

## Any other MCP client

Add `https://karman.si/mcp` as an HTTP MCP server.

## ClawHub

```
clawhub install karman
```

## Care with words

Karman reports nothing to anyone and is not an official warning service. A label is the most likely cause on the evidence, not an identification. "Unexplained" objects are only ever a count.
