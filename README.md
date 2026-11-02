# gsearch

A simple bash script to search the web from the terminal.

## Features

- Uses `xdg-open` by default to open results in your default browser
- Supports Google (default) and DuckDuckGo (`-D`)
- Supports Firefox (`-F`) instead of default browser
- Properly URL-encodes search queries using Python

## Usage

```bash
gsearch "search query"
gsearch -F "search with firefox"
gsearch -D "search with duckduckgo"
gsearch -F -D "firefox + duckduckgo"
```

## Installation

Add `~/.local/bin/` to your PATH and put the script there (or anywhere in PATH):

```bash
cp gsearch ~/.local/bin/
chmod +x ~/.local/bin/gsearch
```

## Source

Based on the script in `~/.local/bin/gsearch`
