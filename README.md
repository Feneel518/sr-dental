# SR Dental — client pitch demo

A responsive React + Vite website in calm blue and white, based on the supplied visual reference and the clinic’s Google Business and Instagram profiles.

## Run locally

```sh
npm install
npm run dev
```

On Windows PowerShell with script execution disabled, use `npm.cmd install` and `npm.cmd run dev`.

## Production build

```sh
npm run build
npm run preview
```

Deploy the generated `dist/` folder to a static host when ready. No environment variables or backend are required.

## Verify

With the dev server running at port 5173:

```sh
npx playwright install chromium
npm test
```

Checks five responsive widths, images, appointment validation and editing, clipboard, treatment details, gallery navigation, FAQ, reviews and the mobile menu. Screenshots are saved in `artifacts/`.

## Features

- Responsive layouts and mobile navigation
- Real clinic and doctor photography, locally hosted fonts and images
- Treatment detail dialogs and a clinic photo gallery with keyboard controls
- Appointment request planner, validation and copy-to-clipboard, followed by click-to-call confirmation
- Patient review excerpts, FAQs, Google Maps, phone and Instagram links
- Keyboard focus, native accessible dialogs and reduced-motion support

This is a pitch demo: the appointment form does not send data or book visits. Source details and production considerations are in `CONTENT-SOURCES.md`. Visual direction is in `DESIGN.md`.
