# Coffee Haven

A modern, responsive multi-page website for a cozy coffee shop. Built with Tailwind CSS utility classes and Roboto font.

## Files
- `index.html` — Home page with hero, specialties (filterable), testimonials, and subscribe modal.
- `about.html` — Story, sourcing, and team information.
- `contact.html` — Contact form, hours, and location.

## Notes & Features
- All pages are fully fluid and designed to fill the full width of the viewport. Main wrappers use `w-full` and avoid fixed max-width containers.
- Tailwind CSS is loaded via CDN (`https://cdn.tailwindcss.com`) and classes are used directly in the HTML.
- Google Font Roboto is linked on each page. The font is declared with the special comment format required by the asset pipeline: `{{font: Roboto}}`.
- Images use special placeholders that an automated system will replace. Example: `https://pixabay.com/get/g608ce8f98f8b5cc6d1d52099bd6de89693659381953c99302aeb37dbf4ac65afbdc032bcf3876c0f73d9a9da7bfd84f028393b276db907264bb716ee1b8439cc_640.jpg`.
- Interactive elements:
  - Mobile menu toggle on the home page.
  - Filterable specialties on the home page.
  - Subscribe modal with basic validation.
  - Contact form with simulated submission.

## How to use
1. Unzip (if zipped) and open `index.html` in a browser.
2. The image placeholders will be automatically fetched and replaced by the hosting system.

## Customization
- Colors use an earthy palette — modify the hex values (e.g., `#4b2e2b`) inline if you want different tones.
- Add or edit specialties in the `index.html` specialties array to change cards.

Enjoy building your coffee brand with this starter site!