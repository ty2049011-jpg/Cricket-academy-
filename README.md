# Elite Cricket Academy (Demo Website)

React + Vite + Tailwind CSS. Backend: Supabase (auth, database, storage).

## Run locally
```
npm install
npm run dev
```

## Deploy to Netlify
1. Push this folder to GitHub (or drag the `dist` folder after `npm run build`).
2. Netlify: Build command `npm run build`, Publish directory `dist` (already in netlify.toml).

## Supabase setup
1. Supabase Dashboard > SQL Editor: run `supabase.sql`.
2. Authentication > Users > Add user (admin email + password).
3. Authentication > Sign In / Providers: turn OFF "Allow new users to sign up".
4. Project URL and publishable key are set in `src/App.jsx` (or use `.env`, see `.env.example`).

## Admin panel
Open `your-site/#admin` and log in. Manage: gallery photos, site images, programs, coaches,
schedule, fees, hero stats, contact info and enquiries.

## Demo content
Statistics, coaches, achievements, reviews and fees are placeholders. Replace them from the admin panel.
Photos are hot-linked from Pexels (free license) with built-in fallback illustrations.
