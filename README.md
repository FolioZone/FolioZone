# FolioZone

FolioZone is a bilingual (English/Arabic) portfolio service site where users request a professional portfolio page and CV services.

- Live site: [https://folio-zone.com](https://folio-zone.com)

## What is currently implemented

- Responsive static site built with HTML, Tailwind (CDN), and vanilla JavaScript.
- English/Arabic language toggle with RTL handling.
- Portfolio request form powered by Web3Forms.
- FAQ accordion, contact section, and social links.
- Basic SEO setup:
  - meta description
  - Open Graph/Twitter meta
  - JSON-LD (`Organization`, `Service`, `FAQPage`)

## Pricing (current, USD)

### Portfolio Packages

| Plan | Price | Includes |
|------|-------|----------|
| Starter | 10 USD | Core portfolio sections, hosted URL, 48h turnaround |
| Basic | 20 USD | Starter + profile image + CV download + 3 updates / 6 months |
| Premium | 30 USD | Basic + custom layout + contact form + 10 updates / year |

### CV Services

| Plan | Price | Includes |
|------|-------|----------|
| CV Basic | 10 USD | ATS formatting, clean design, 1 revision |
| CV Premium | 20 USD | Basic + custom design + 3 revisions + cover letter template |

## Request Flow

1. User fills `#portfolioRequestForm` in `index.html`.
2. Form posts to Web3Forms endpoint.
3. On success, user is redirected to `thank-you.html`.

## Contact (current)

- Email: `foliozonejo@gmail.com`
- WhatsApp: `+962797473575`
- Website: [https://folio-zone.com](https://folio-zone.com)

## License

Commercial project. All rights reserved © FolioZone.
