# routr.shop — Landing Page

Coming soon page for Routr, a CNC woodworking app.

## Deploy

Static HTML — deploy anywhere:
- **Cloudflare Pages**: Connect repo, build command = (none), output dir = `/`
- **Vercel**: Same deal
- **GitHub Pages**: Push to `gh-pages` branch

## Email Capture

Currently stores to `localStorage` (placeholder). Before launch, wire up one of:
- Cloudflare Worker + KV (free, keeps data close)
- Buttondown (free tier, nice for newsletters)
- Mailchimp (free up to 500 contacts)

## TODO
- [ ] Wire up real email capture backend
- [ ] Add OG image (screenshot of app or hero graphic)
- [ ] Favicon
- [ ] Analytics (Plausible or Cloudflare Web Analytics — both privacy-friendly)
