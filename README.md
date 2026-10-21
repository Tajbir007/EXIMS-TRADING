# EXIMS TRADING | FINAL REVIEW BUILD

A mobile-first static corporate website for Exims Trading, with 7 main pages, 13 product detail pages, seven language choices and company-profile PDF. No payment, login, database or backend is required.

## Viewing the site

Extract the ZIP, open a terminal in this directory and run:

    python -m http.server 8000

Then visit http://localhost:8000 in a browser. The files can also be deployed to a static hosting provider.

## Pages

- Home (`index.html`)
- Products (`products/index.html`)
- Our Brands (`brands/index.html`)
- Sourcing & Supply (`sourcing/index.html`)
- About Us (`about/index.html`)
- Global Partnerships (`global-opportunities/index.html`)
- Contact Us (`contact/index.html`)
- Thirteen individual pages under `products/`

## Contact details and behavior

Company contact: info.eximstrading@gmail.com
General phone / WeChat: +880 1716-420469
WhatsApp: +880 1818-413544
Location: 217 Mitford Road, Ahsan Market, Dhaka, Bangladesh

- Direct WhatsApp links have editable English introductory messages appropriate to the page or product.
- Sourcing and global partnership forms generate **editable** email or WhatsApp drafts including the entered information. Messages are **not sent automatically**.
- Multi-product inquiry generates a message with selected products.
- WeChat is displayed only on the Contact page and all page footers, with the original QR. WeChat is **not** offered as a form submission method; the site cannot automatically start or prefill a WeChat conversation.

## Downloadable company profile

The approved **10-page International Partnership Profile** is at `assets/docs/Exims-Trading-Company-Profile.pdf`. Existing About Us and footer download links use this PDF. A new introductory panel at the start of the Global Partnerships page offers both Read and Download, with a preview of the actual PDF cover. The new panel is translated in the seven-language frontend.

## Image, brand and copyright rules

- Original Exims Trading ET mark and supplied product posters are used as provided.
- Safety and Surgifit are Exims Trading own brands.
- **ASP, JMS and Tynor are selected imported products, not Exims Trading's own brands. Their external brand logos are never used separately; logos appear only where they are part of the original product posters or packaging.**
- All product posters remain fully visible in the website; original ratio is retained, with optional full-view zoom for small print.
- TR Trade and Aromel are separate family ventures, not subsidiaries; only their logo images may be circular-cropped.
- Contact page Exims Trading seal has only the *outer rectangular white backing* made transparent; the original circular artwork remains intact.

## Final verification before public launch

- Confirm medical label claims, certificates, specifications and availability with source packaging and up-to-date business records.
- Validate translations with native speakers when used for binding commercial decisions; the English version remains the original reference.
- Test the final hosting URL, custom domain, actual WhatsApp/WeChat accounts and email app handoff on representative iOS/Android devices.
- The linked fonts are fetched from Google Fonts when internet is available, falling back to system fonts otherwise.

## What is not included

No CRM backend, payment processing, automatic email submission, real-time inventory, supplier credentials, or universal WeChat deep-link.
