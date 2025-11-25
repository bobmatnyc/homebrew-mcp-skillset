# Homebrew Tap for mcp-skillset

This is a Homebrew tap for [mcp-skillset](https://github.com/bobmatnyc/mcp-skillset), an MCP server for managing and executing AI skills with dataset support.

## Installation

```bash
brew tap bobmatnyc/mcp-skillset
brew install mcp-skillset
```

## Usage

After installation, you can run:

```bash
mcp-skillset --version
```

For more information, see the [main repository](https://github.com/bobmatnyc/mcp-skillset).

## Updating the Formula

When a new version is released:

1. Update the `version` and `sha256` in `Formula/mcp-skillset.rb`
2. Commit and push the changes
3. Users can update with `brew upgrade mcp-skillset`
