# Remindly

A simple, responsive personal reminder app built with React, Vite, Lucide React, and date-fns. Create reminders with a date, time, and optional note; search, filter, edit, complete, or delete them. Reminder data is saved in browser LocalStorage.

## Run locally

```sh
npm install
npm run dev
```

Open the local URL printed by Vite. For a production build, run `npm run build`; use `npm run preview` to serve the built app locally. `npm run lint` runs ESLint.

## Deploy to Vercel

Import the repository into Vercel and use the Vite defaults: `npm run build` as the build command and `dist` as the output directory. The included `vercel.json` rewrites app routes to `index.html` so client-side navigation also works on direct visits.

## Data

Reminders are stored in this browser on this device. They are not synced between browsers or devices, and clearing browser storage removes them.
