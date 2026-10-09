# What Did I Miss? 🔍

A fast, fully local, in-browser AI chat catch-up micro-app. It summarizes long conversations, extracts decisions and action items, and prioritizes what you missed—all without your data ever leaving your device.

## Features
- **100% On-Device:** No network requests for analysis. Your chat logs stay strictly in your browser.
- **Smart Summarization:** Get a quick TL;DR of hundreds of messages.
- **Priority Ranking:** See high, medium, and low priority messages based on urgency, deadlines, and mentions.
- **Action Items & Decisions:** Easily track assigned tasks and finalized decisions.

## Setup & Run
1. Install dependencies: `npm install`
2. Run the dev server: `npm run dev`
3. Open the provided localhost URL in your browser.

## Testing
Run the test suite with: `npm test`

## Project Structure
- `/src/components` - React UI components
- `/src/lib` - Core logic (parser, analyzer, scorer, summarizer)
- `/src/types` - TypeScript definitions
- `/src/config` - Centralized heuristics and limits
