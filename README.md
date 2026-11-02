# MKPANE Website — WEDE 5020 Part 3

## Project overview
A responsive five-page website for MKPANE, presenting agricultural information, services, enquiries and contact details.

## Pages
- `public_html/index.html` — Home
- `public_html/about.html` — About, mission/values and FAQ accordion
- `public_html/services.html` — Services with live text filtering
- `public_html/enquiry.html` — Enquiry form with client-side validation
- `public_html/contact.html` — Contact form with client-side validation

## Run locally
Open `public_html/index.html` in a browser. For deployment, publish the contents of `public_html` using GitHub Pages (or another static hosting platform).

## Part 3 functionality and SEO
- JavaScript client-side form validation and accessible error messages. Successful validation opens a pre-filled email draft; a static website cannot deliver form submissions on its own.
- Live service search/filter.
- Interactive map search on the Contact page (visitor enters a location; replace this with confirmed MKPANE addresses for the final version).
- FAQ accordion using native HTML `details` elements.
- Scroll reveal transitions and a back-to-top button, with reduced-motion support.
- Per-page metadata, descriptive titles, semantic headings, internal navigation, responsive layout, and focus styles.
- `robots.txt` and `sitemap.xml` included. Replace `YOUR-GITHUB-USERNAME` and `YOUR-REPOSITORY` in both files with the actual GitHub Pages address before final deployment.

## Testing checklist
1. Open every page and test all navigation links.
2. On Services, search for a word such as `farming`; verify cards filter and reset when the field is cleared.
3. Submit each form empty, with an invalid email, and with valid information. Confirm validation messages and the pre-filled email draft.
4. Check layout at desktop and mobile widths.
5. Check browser console for errors.
6. Replace the sitemap/robots placeholders, deploy, and test the live URL.

## Changelog
See `CHANGELOG.md` for the Part 3 change log.
