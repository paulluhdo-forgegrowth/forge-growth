# Forge Growth

Cloudflare Workers Static Assets deployment with a Worker-powered contact form.

## Cloudflare build settings

- Build command: leave blank
- Deploy command: `npx wrangler deploy`
- Root directory: repository root

## Required secrets and variables

- `RESEND_API_KEY`
- `CONTACT_TO_EMAIL`
- `CONTACT_FROM_EMAIL`

The public website is in `/public`. The contact endpoint is handled by
`/src/index.js` at `/api/contact`.
