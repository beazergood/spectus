# Spectus Energy Ltd — Website

## Project Overview

Single-page website for **Spectus Energy Ltd**, a combustion engineering company founded in 1957 in Reading, Berkshire, UK. The company is winding down and primarily provides parts and technical support to longstanding customers. This site is a minimal web presence — not a sales tool.

## Tech Stack

- Single `index.html` with all CSS embedded (no external stylesheets)
- No JavaScript, no frameworks, no build tools
- Fonts loaded from Google Fonts
- Deployed to **Vercel** (production)
- Repo: https://github.com/beazergood/spectus

## Design

- **Aesthetic**: Dark industrial, clean, minimal — understated confidence
- **Palette**: Deep charcoal (`#0f1114`), steel grays, warm amber/copper accent (`#c4883a`) evoking combustion
- **Typography**: DM Serif Display (headings), IBM Plex Sans (body), IBM Plex Mono (labels/tags)
- **Layout**: Two-column grid with monospaced section labels on the left, content on the right. Stacks to single column on mobile.
- **Tone**: Established, professional, not trying to sell. The company has decades of heritage and doesn't need to prove anything.

## Content Structure

1. **Hero** — Company name, tagline ("The inventors of self cooling liquid fuel oil systems"), established date
2. **Legacy** — Brief company history, key achievements, "innovators lead, imitators follow" quote
3. **What We Supply** — Three product cards (Burners, Flame Monitoring, Gas Igniters) framed as parts/support
4. **Contact** — Email, phone, address
5. **Footer** — Copyright, ISO certification

## Company Context

- Founded 1957, Reading, Berkshire
- Specialists in liquid fuel oil burners, flame monitoring systems, gas igniters
- Equipment in power stations worldwide: Drax, Tarong, Callide, Stanwell, Marchwood, Drakelow
- Partners: Babcock, Doosan, Foster Wheeler, Hitachi
- Key products: FM10a2, TrueScan, ISFM (flame monitoring); self-cooling tip shut-off fuel injectors
- Pioneered suspended flame technology (1969)
- Over 3,000 flame monitoring units deployed
- Contact: sales@spectus.org / +44 (0) 1491 875789
- Address: 35 Wallingford Road, Reading, Berkshire, RG8 0HL
- BS EN ISO 9001 certified
- The owner/director Trevor Beazer is David's (the developer) father

## Content Source

Original website content was retrieved from the Wayback Machine:
https://web.archive.org/web/20141218092737/http://spectusenergy.com/

We have artistic freedom on design and content. Not all original content needs to be preserved — the site is deliberately pared back.

## Deployment

- `vercel --prod` to deploy
- Can add custom domain (e.g. spectusenergy.com) via Vercel dashboard > Settings > Domains
