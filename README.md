# Travel.pk mobile journey demo

A mobile-first, installable-feeling static web app prototype for Travel.pk. It combines sample flight search with a clearer trip-status journey, destination planning, package ideas, price-alert states, and support records.

## Run it locally

No build step, account, API key, or package installation is required.

```bash
cd travelpk-mobile-app
python3 -m http.server 4173
```

Open `http://localhost:4173` in a browser. The app is also a static PWA: on a secure origin it can be installed by the browser and its app shell plus local images are cached for offline demo use.

## What you can try

- Search one-way, return, and multi-city sample routes.
- Filter to nonstop or flexible sample fares and sort the illustrative results.
- Open sample fare rules, select a fare, review the no-personal-data confirmation, and create a synthetic trip status.
- Browse sample trips covering supplier processing, ticket issued, a refund request, and refund settled; open each timeline and its sample support record.
- Check off a lightweight planner list, explore fictional package concepts, add/pause/remove local fare alerts, preview a simulated alert, and create a local demo support reference.

## Demo boundary

The persistent notice in the app is intentional. All routes, flight schedules, fares, allowances, booking IDs, events, and support cases are synthetic examples. Amounts are explicitly fictional demo amounts. Airline names are placeholders; no live route inventory is represented. The prototype has no backend, account creation, Travel.pk API, live airline or supplier access, payment, checkout, booking/ticket issuance, cancellations/refunds, notifications, or outgoing support messages. User-entered route preferences and checklist state remain in browser memory only and are not submitted or stored by a server. Do not enter personal, passport, or payment details.

This is a design/flow prototype, not an official Travel.pk product release.

## Visual assets and inspiration

The brand treatment follows publicly visible Travel.pk homepage text and styling (`https://travel.pk/`). Destination photography included in `assets/` was copied from Travel.pk's publicly served media paths:

- `hunza.jpg`, `skardu.jpg`, `lahore.jpg`, `istanbul.jpg`, `cappadocia.jpg`, and `dubai.jpg` — `https://supabase.travel.pk/storage/v1/object/public/media/destinations/<name>.jpg`

The files are local copies for this prototype, so the demo makes no runtime request to Travel.pk or other services.
