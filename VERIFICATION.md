# Verification

Checked on 7 October 2026 with Chromium.

## Browser checks

- All five main pages loaded successfully at 1440px desktop, 1280px laptop, 768px tablet, 390px mobile and 320px small-mobile widths: 25 page/viewport combinations.
- No document overflow, overflowing content blocks or broken images in those combinations.
- All five navbar destinations opened by clicking their links at every tested size. Mobile profile expansion and collapse worked.
- All four themes applied, restored between pages and loaded their corresponding developer animations. The animations loaded and advanced frames.
- Project filters and all three local project-detail dialogs worked on desktop and mobile.
- The portrait lightbox opened, closed with Escape and returned focus to the trigger.
- The resume viewer requested the local PDF, its bytes were confirmed as a valid PDF, and the download used Anisha_More_Resume.pdf.
- Contact-form validation rejected an invalid email address. Valid input opened an email draft for the supplied recipient. No email was sent.
- Music playback, pause, volume and persistence of the stopped preference between pages worked.
- Card hover/parallax effects worked.
- The arcade grid fit at 1440px, 768px, 390px and 320px widths. Mouse/touch firing hit blocks, restart worked and the return link opened the portfolio.
- No page JavaScript errors or failed local asset requests in the completed checks.

## Content and package checks

- Recursively audited HTML, CSS, JavaScript, Markdown, filenames, SVGs, PDF text and the JSON content inside the animation archives. No earlier-owner names or personal information were found.
- Confirmed all 175 statically referenced local assets, module imports and page destinations exist.
- Removed empty placeholder links, unsupported awards and social profiles, old project assets and numerical skill ratings.
- The bundled resume and portrait are byte-identical to the supplied files.
- The ZIP contains the complete site folder and passes its integrity check.

## External services

The social links use the supplied GitHub screenshot and LinkedIn profile export. The GitHub profile responded with HTTP 200. LinkedIn blocks automated requests with HTTP 999, so its public reachability could not be independently confirmed; the exact supplied profile URL is retained. The Google Maps embed requires internet access and was excluded from the local-only browser checks. Opening email drafts requires a configured email application. These external services are not bundled with the website.
