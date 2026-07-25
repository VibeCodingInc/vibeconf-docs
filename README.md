# Vibeconferencing docs — Mintlify source

A complete, ready-to-deploy Mintlify docs set. Drop-in the moment the Mintlify project exists.

## Pages
- `docs.json` — config + navigation + theme (Spirit Blue #6B8FFF, dark)
- `index.mdx` — Talk to your work (home / overview)
- `quickstart.mdx` — download → wizard → /join-call
- `agent.mdx` — **for your coding agent** (the bot-legible self-onboard — the strategic page)
- `in-a-call.mdx` — what you can do (speak/listen/whiteboard/chat/screen)
- `identity.mdx` — naming & identity (session-derived)
- `troubleshooting.mdx` — the real gotchas
- `network.mdx` — where it's going (one MCP, the doorbell, the honest moat)

## To go live
1. Create a docs project on the [Mintlify dashboard](https://dashboard.mintlify.com) and connect this repo,
   with the docs directory set to `mintlify/` (or move these files to the location Mintlify expects).
2. Set the custom domain to `docs.vibeconf.app` (Mintlify → Settings → Custom domain), and repoint the DNS
   from the current Vercel `public/docs` to Mintlify.
3. Once connected, this content can also be edited live via the Mintlify MCP (checkout → edit → save).

Written to the latest positioning: voices + emoji, session-derived identity, the two doors, the honest moat.
No valuation or deal content — this is the product/onboarding surface.
