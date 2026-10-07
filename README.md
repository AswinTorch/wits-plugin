# wits plugin

Connect your [wits](https://witsnotes.com) account to Claude, Codex, or
ChatGPT. Save, find, and organize the same notes, lists, and reminders you
capture on your iPhone, Apple Watch, or the web. Every result links back to
the wits app, where you can see and edit it yourself.

You need a wits account. You sign in with it once when you connect, and choose
whether the assistant can only read your library or can also make changes.

## Install

**Claude Code**

```
/plugin marketplace add AswinTorch/wits-plugin
/plugin install wits@witsnotes
```

Then run `/mcp`, choose `plugin:wits:wits`, and sign in.

**claude.ai, Claude Desktop, and the Claude mobile app**

Go to **Customize → Plugins → Add → Add marketplace**, enter
`AswinTorch/wits-plugin`, and install **wits**. Connect it from the plugin's
**Connectors** tab.

**Codex**

```
codex plugin marketplace add AswinTorch/wits-plugin
codex plugin add wits@witsnotes
```

Or open `/plugins` in Codex and install **wits** there. In the ChatGPT
desktop app, find it under **Plugins**.

## Updates

In Claude Code, turn on auto-update for the `witsnotes` marketplace under
`/plugin` → **Marketplaces**, or update by hand with
`claude plugin update wits@witsnotes`. In Codex, run
`codex plugin marketplace upgrade witsnotes`.

Changes to what the tools can do reach you without an update, because they
run on the wits server.

## Privacy and support

- Privacy policy: https://witsnotes.com/privacy
- Terms: https://witsnotes.com/terms
- Support: hi@witsnotes.com

This repository is generated from the wits source and published on each
release. Please send issues to hi@witsnotes.com.
