# LLM Code Extractor

A simple, browser-based tool to parse Markdown responses from LLMs (Gemini, ChatGPT, Claude) and download the generated code as a ZIP file with the correct directory structure.

## How to Use

- Just open the GitHub page in your browser: 

## Features

- **No Server Required**: Runs entirely in your browser, fully privacy-preserving.
- **Directory Support**: Automatically builds folder structures (e.g., `app/core/config.py`).
- **Smart Parsing**: Detects filenames in code blocks, headers, and list items.
- **Empty File Support**: Recognizes instructions to create empty files (like `__init__.py`).

## Requirements

- An internet connection (to load the `JSZip` and `FileSaver` libraries via CDN).
