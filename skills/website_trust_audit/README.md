# Website Trust Audit

A Claude skill that runs the exact 5-point trust check 37degree uses before redesigning a client's site.

Give it any URL. It fetches the homepage and delivers a scored audit covering:

1. **Proof First** — Does the hero lead with evidence, or just describe what you do?
2. **Trust Placement** — Are trust signals where decisions happen, or buried in the footer?
3. **Clarity** — Can a stranger explain what you do after 5 seconds?
4. **CTA Focus** — One clear action, or five competing buttons?
5. **Visual-Positioning Alignment** — Does the site look like what you're charging?

Each check gets a **PASS**, **NEEDS WORK**, or **FAIL** verdict with a specific fix.

## Install

```bash
npx skills add 37degree/website-trust-audit
```

## Usage

Just say:

> "Run a website trust audit on https://example.com"

Or any of these triggers: `website audit`, `trust audit`, `site audit`, `homepage review`, `audit my site`, `check my website`

## Who built this

[37degree](https://37degr.ee) — an AI UX and product design studio. We run this audit on every client site before we touch a single pixel.

## License

MIT
