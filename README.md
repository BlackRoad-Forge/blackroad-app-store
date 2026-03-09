# BlackRoad App Store

Web-based app marketplace for the BlackRoad OS ecosystem. Built with Next.js 15.

## Quick Start

```bash
cd web && npm install && npm run dev
```

Open [http://localhost:3100](http://localhost:3100).

## Stack

- **Framework:** Next.js 15 (React 18)
- **Deploy:** Cloudflare Pages
- **Distribution:** PWA, direct download, sideload

## Features

- Instant app publishing (no review gate)
- Developer-first: 5% platform fee (vs 30% industry standard)
- Progressive Web App support for cross-platform install
- Dark theme UI with BlackRoad branding

## Project Structure

```
web/
  app/
    layout.js    # Root layout
    page.js      # Store homepage
  package.json   # Dependencies
  next.config.js # Next.js config
  wrangler.toml  # Cloudflare Pages deployment
```

## License

Copyright 2026 BlackRoad OS, Inc. All rights reserved.
