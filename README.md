# Claude Token Mastery

A high-converting digital-product website for the **Claude Token Mastery Guide**. The site presents the guide, routes visitors through a dedicated checkout-style access page, and delivers the PDF instantly without collecting payment details.

**Live site:** [claude-token-mastery-site.vercel.app](https://claude-token-mastery-site.vercel.app/)

## Visitor flow

1. A visitor arrives on the landing page.
2. Any call-to-action opens the checkout-style access page.
3. The checkout page presents a direct download button for the guide PDF.
4. The PDF downloads immediately; there is no payment gateway, form submission, or customer data collection.

## Included pages

- Landing page and sales copy
- Checkout-style instant-access page
- Claude Token Mastery PDF guide
- Privacy Policy
- Terms of Use
- Refund Policy
- Contact Support

## Technical setup

This is a static HTML website. The deployable site is in the `public/` directory and is configured through `vercel.json`.

- `public/index.html` - landing and sales page
- `public/checkout.html` - checkout-style access page with direct PDF download
- `public/Claude_Token_Mastery_Product.pdf` - downloadable guide
- `public/*.html` - legal and support pages
- `vercel.json` - Vercel output directory and PDF download headers

## Deployment

The repository is connected to Vercel. Pushes to the `main` branch automatically deploy the latest version to production.

## Important note

The guide is intentionally delivered as a direct download with no payment gateway. Anyone with the guide's direct URL can download or share it.
