# call-me

A Claude Code plugin that lets your agent ring your real phone, read its question out loud and get your spoken answer back as text. It can also text the phone, and you can text or leave a voicemail back.

Website: https://callmemcp.com
Repository: https://github.com/radres/call-me

## Install

1. Get the /call-me app (iPhone or Android) from callmemcp.com. It gives you a 10-digit number.
2. Install the plugin:

```
claude plugin marketplace add radres/call-me
claude plugin install call-me@call-me
claude plugin enable call-me@call-me
```

3. Restart Claude Code and ask it to pair with your number.

## Use

Ask Claude to call you when it needs a decision, or to text you when a long task is done. The line can stay open for a back-and-forth conversation.

The same service also works from other agents through the remote MCP server `https://callmemcp.com/mcp`.
