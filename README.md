# Ollie / Edit

A responsive portfolio and client-enquiry website for Ollie’s video-editing services.

## Current features

- Responsive, mobile-friendly one-page portfolio
- Services, work placeholders, workflow and about sections
- Quote/enquiry form layout with client-side validation
- No client details are sent or stored yet: the form needs a secure backend or form provider before launch

## Preview locally

Open `index.html` in a browser, or use VS Code’s Live Server extension.

## Deploy on Cloudflare Pages

1. In Cloudflare, open **Workers & Pages** and choose **Create application** → **Pages** → **Connect to Git**.
2. Authorise GitHub and choose this repository.
3. Use these settings for the current plain HTML site:
   - Production branch: `main`
   - Framework preset: `None`
   - Build command: leave blank
   - Build output directory: `.`
4. Deploy. Future pushes to `main` will automatically redeploy the site.

## Before launch checklist

- Replace `your-email@example.com` in `index.html` with Ollie’s professional email address.
- Replace the coloured project placeholders with actual video thumbnails, embedded reels or links.
- Update services and availability so they match what Ollie offers.
- Connect the quote form to a secure backend (for example, a Cloudflare Pages Function that validates the request and sends it via an email provider) or a trusted form service. Never add email-provider keys directly to `script.js` or `index.html`.
- Add a privacy notice if you collect client contact details.
