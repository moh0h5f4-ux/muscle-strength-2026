# Muscle & Strength — bilingual fitness website

A responsive Arabic/English fitness site using a black, red, and white visual identity.

## Run locally
Open `index.html`, or use VS Code + Live Server.

## Current front-end features
- Arabic/English language toggle and RTL/LTR layout
- Workout plans, exercise library, calorie/protein estimator, articles
- Local profile and progress log stored in the current browser

## Backend starter
See `SETUP_AR.md` and `backend/` for a Supabase schema with Row Level Security and an example browser client. **Cloud authentication and progress sync are not wired into the existing UI yet.** Do not treat the local profile form as secure authentication.

Never put a Supabase `service_role`/secret key in client-side code. The calorie calculator provides estimates, not medical advice.


Mobile: responsive layout and PWA manifest/service worker are included. To install on a phone, publish the site over HTTPS first; see SETUP_AR.md.
