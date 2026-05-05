# SynthForce Platform

**HR for AI agents.** A governance layer for managing AI agent workforces.

## Repository Structure

```
/
├── api/                  # Vercel serverless functions
│   └── sitemap.js        # Dynamic sitemap
├── blog/
│   └── the-agent-explosion-how-to-prepare.html
├── src/
│   ├── assets/           # Images, SVGs, favicon, integration logos
│   ├── pages/            # HTML pages (to be migrated to TypeScript)
│   │   ├── index.html          # Landing page
│   │   ├── about.html          # About / team
│   │   ├── product.html        # Product overview
│   │   ├── demo.html           # Interactive demo
│   │   ├── blog.html           # Blog listing
│   │   └── waitlistsignup.html # Waitlist
│   ├── components/       # Reusable UI components (future)
│   └── styles/           # CSS styles (future)
├── docs/                 # Architecture specs, design docs
├── scripts/              # Build and deployment scripts
├── .gitignore
├── package.json
├── vercel.json           # Vercel deployment config
└── CNAME                 # Custom domain (synthforceai.com)
```

## Tech Stack (Current)

- **Frontend:** Pure HTML + Tailwind CSS (CDN)
- **Deployment:** Vercel
- **Domain:** synthforceai.com
- **Analytics:** Vercel Analytics

## Migration Plan

The current HTML pages in `src/pages/` will be migrated to TypeScript/React. The backend architecture (PostgreSQL, API, auth, policy engine) will be built in parallel.

## Access

- **Owner:** Samarth Kambli (samarth@synthforceai.com)
- **Founding Full-Stack Engineer:** Matthew Gomez-Morales (matthew@synthforceai.com)
- All code is proprietary and owned by SynthForce AI Inc.
