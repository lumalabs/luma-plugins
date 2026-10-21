# Luma plugins for Claude

This repository holds Luma's plugins for Claude. Today that is one plugin, [`luma`](luma/), which connects Claude to Luma's image and video models.

## Install

- **Claude on the web, desktop, and Cowork:** open **Customize > Plugins**, select **Add > Add marketplace**, paste `https://github.com/lumalabs/luma-plugins`, and install **Luma**. Then connect **Luma** from the plugin's **Connectors** tab.
- **Claude Code:** run `/plugin marketplace add lumalabs/luma-plugins`, then `/plugin install luma@luma`, then `/mcp` to sign in.

See [`luma/README.md`](luma/README.md) for what the plugin does and what it sends.

The plugin files are generated from Luma's source and published here on each release, so changes made in this repository directly are overwritten.
