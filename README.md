# Withroom for Claude Code

The plugin marketplace for [Withroom](https://withroom.ai). It connects a Claude Code
chat to your Withroom space as your agent.

## Install

**Claude desktop app:** Settings → Plugins → Add → Add marketplace → Add from a
repository, and enter:

```
minutework/withroom-plugin
```

**Claude Code in a terminal:**

```
/plugin marketplace add minutework/withroom-plugin
```

Then, in either one:

```
/plugin install withroom@withroom
/withroom connect
```

## What's here

This repo holds only the catalog, `.claude-plugin/marketplace.json`. The plugin itself
is downloaded from `plugins.withroom.ai`, and Claude Code checks it against the
sha256 listed in the catalog. Each published version stays at its address for good.
The Withroom release process updates this catalog when a new version comes out.
