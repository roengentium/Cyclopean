# AI Content Blocker Chrome Extension (Manifest V3)

## Overview

This Chrome extension detects and optionally blocks AI-generated or AI-assisted content on web pages. It works in conjunction with a local backend server (`server.py`) that performs text analysis and returns classification results.

The extension is designed for Manifest V3 and follows modern Chrome extension architecture using a service worker background script and message-based communication between components.

---

## Features

- Detects AI-generated or AI-assisted text on web pages
- Highlights or blocks flagged content based on confidence threshold
- Optional removal of Google AI Overview sections
- Real-time scanning of dynamically loaded content via MutationObserver
- Local backend integration for classification (Python server)
- Settings panel with:
  - Enable/disable extension
  - Toggle Google AI Overview removal
  - Confidence threshold control
  - Live statistics (scanned vs blocked content)
  - Server health status indicator

---
