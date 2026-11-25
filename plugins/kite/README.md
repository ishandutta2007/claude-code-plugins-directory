# Kite

Kite is a design tool your AI agents and your team share. The Kite plugin adds Kite's hosted MCP server (`https://kite.new/api/mcp`) and the Kite design skill, so Claude Code can draw banners, social posts, ads, logos and app screens as real, editable layers (frames, text, components, auto layout) in a design file your team opens, edits and comments on.

Repository: https://github.com/kitedotnew/kite-agent-plugins
Website: https://kite.new

## Why it is useful

- Claude works in a real design file instead of producing screenshots or one-off HTML
- Your team edits the same file live in the browser or the Mac and Windows apps
- Copy any frame to Figma, or as HTML, React or Tailwind
- Sign in once with OAuth in the browser; there is no API key to copy

## Install

Run these commands in Claude Code:

```text
/plugin marketplace add kitedotnew/kite-agent-plugins
/plugin install kite@kite
```

Then run `/mcp`, choose `kite` and sign in.

## Notes

- Kite free plan: unlimited editors, 3 files, 100 agent actions a day, no AI credits
- The same repository also packages the plugin for Codex and Cursor
