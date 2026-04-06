# Leukanote Support Website

Support website for Leukanote iOS App, hosted on GitHub Pages.

## About Leukanote

**Leukanote** — from Greek *"leukos"* (λευκός), meaning **white & clear**. 

A blank canvas for your health records. Leukanote helps you scan, recognize, and track your health metrics over time.

## Website URLs

| Page | URL |
|------|-----|
| Support | https://www.leukanote.cn |
| Privacy Policy | https://www.leukanote.cn/privacy.html |
| Terms of Use | https://www.leukanote.cn/terms.html |

## App Store Connect

When submitting to App Store Connect, use these URLs:

| Field | URL |
|-------|-----|
| Support URL | `https://www.leukanote.cn` |
| Privacy Policy URL | `https://www.leukanote.cn/privacy.html` |

## Local Preview

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080

## Deployment

1. Enable GitHub Pages (Settings → Pages → Source: Deploy from a branch → main / root)
2. Add DNS records at your domain provider:
   - CNAME: www → wang-h.github.io
3. Enable "Enforce HTTPS" in GitHub Pages settings
4. Wait 5-10 minutes for DNS propagation

## Files

- `index.html` - Support homepage (FAQ, contact)
- `privacy.html` - Privacy Policy (bilingual)
- `terms.html` - Terms of Use (bilingual)
- `CNAME` - Custom domain config

## Contact

- Email: leukanote@icloud.com
