# RM Sky Consultancy website

One-page website for RM Sky Consultancy, visit visa consultants in Islamabad. Built with [Astro](https://astro.build).

## Run it locally

```bash
npm install
npm run dev
```

Then open http://localhost:4321.

## Edit the content

All business details and text live in **`src/data/site.ts`**:

- `site` – name, phone, WhatsApp number, email, address, office hours
- `destinations` – the countries and visa types shown on the page
- `steps` – the "How your application works" section
- `documents` – the document checklist
- `faqs` – questions and answers

Values marked `PLACEHOLDER` (phone, WhatsApp, email, address, hours) must be replaced with the client's real details before going live. The WhatsApp number is used by every WhatsApp button and by the enquiry form.

## Deploy to Vercel

1. Push this repo to GitHub.
2. On [vercel.com](https://vercel.com), choose **Add New → Project** and import the repo.
3. Vercel detects Astro automatically. Click **Deploy**.

Every push to `main` redeploys the site.
