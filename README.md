# ⚠️ DEPRECATED - This tap has been consolidated

This tap has been deprecated and consolidated into **[bobmatnyc/homebrew-tools](https://github.com/bobmatnyc/homebrew-tools)**.

## Please use the new tap instead:

```bash
# Remove old tap (if installed)
brew untap bobmatnyc/mcp-skillset

# Add new consolidated tap
brew tap bobmatnyc/tools

# Install mcp-skillset
brew install mcp-skillset
```

## Why the change?

All bobmatnyc tools are now available in a single tap:
- claude-mpm
- mcp-vector-search
- mcp-ticketer
- mcp-skillset
- ai-trackdown-pytools

This makes it easier to discover and install all tools.

## Migration

The formula is identical, just run:

```bash
brew uninstall mcp-skillset  # If installed from old tap
brew tap bobmatnyc/tools
brew install mcp-skillset
```

---

**New tap**: https://github.com/bobmatnyc/homebrew-tools
