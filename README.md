# FitLinks Mini Site

Tiny static site for App Store Connect requirements.

## Routes

- `/`
- `/support`
- `/privacy`

## Quick Local Preview

From this folder:

```bash
python3 -m http.server 8080
```

Then open:

- `http://localhost:8080/`
- `http://localhost:8080/support/`
- `http://localhost:8080/privacy/`

## Deploy in Minutes (Vercel)

```bash
npm create vercel@latest . --yes
vercel --prod
```

When prompted, keep defaults for a static site.

## App Store URLs

After deployment, plug in your domain:

- Support URL: `https://<domain>/support`
- Privacy Policy URL: `https://<domain>/privacy`

## Post-Deploy SEO Update

Replace `https://your-domain.com` in:

- `index.html`
- `support/index.html`
- `privacy/index.html`

Then redeploy once.
