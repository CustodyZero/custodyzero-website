![CustodyZero](./custodyzero-wordmark-dark.svg)

# custodyzero.com

Static site for [custodyzero.com](https://custodyzero.com). Deployed to Cloudflare Workers on push to `main`.

---

## Structure

```
custodyzero-website/
├── public/
│   └── index.html                  # Landing page
├── .github/
│   └── workflows/
│       └── deploy.yaml             # CI/CD → Cloudflare Workers
├── _headers                        # Cloudflare response headers
├── custodyzero-wordmark-dark.svg   # Brand asset (not covered by Apache 2.0 — see LICENSE)
├── wrangler.toml                   # Cloudflare Workers configuration
└── README.md
```

---

## Local Development

No build step. Edit `public/index.html` directly and open in a browser.

For a local Cloudflare Workers preview:

```bash
npx wrangler dev --port 8787
```

---

## Deployment

Push to `main` triggers automatic deployment via GitHub Actions to Cloudflare Workers.

**Required GitHub Secrets:**

| Secret | Description |
|--------|-------------|
| `CLOUDFLARE_API_TOKEN` | Cloudflare API token with Workers Scripts edit permission |
| `CLOUDFLARE_ACCOUNT_ID` | Your Cloudflare account ID |

---

## Email Capture

Form submissions POST to the AWS Lambda function at `https://api.custodyzero.com/`. The function validates input, applies bot detection, and writes to DynamoDB. Source lives in [CustodyZero/cz-capture](https://github.com/CustodyZero/cz-capture).

---

## Headers & Security

Security headers are defined in `_headers` and applied by Cloudflare Workers on all responses. CSP is intentionally strict — if you add external resources, update the policy.

---

## License

Apache 2.0 — see [LICENSE](./LICENSE).

CustodyZero brand assets — including all wordmarks, logomarks, product names, and taglines — are all rights reserved and explicitly excluded from the Apache 2.0 license. See [LICENSE](./LICENSE) for the full brand reservation notice.

---

*Built for people who shouldn't have to choose.*
