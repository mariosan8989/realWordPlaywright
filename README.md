# realWordPlaywright
# RealWorld Symfony+HTMX - Playwright 

This project contains an adapted Playwright automation framework to test the **RealWorld / Conduit** app running locally at `http://localhost`.

## Prerequisites
- Node.js 18+
- Docker Desktop running
- The app is up at **https://localhost** (containers healthy)
- cd realworld-symfony-htmx
- docker compose up -d


## Install
```bash
npm install
npx playwright install
```

## Run tests (Playwright Test Runner)
```bash
cd ..\realWordPlaywright
npm install
npx playwright test
npm test
# or visual debug
npm run test:ui
```

## Report
```bash
npm run report
```

## Environment
Copy `.env.example` to `.env` and adjust if needed:
- `BASE_URL` (default: https://localhost)
