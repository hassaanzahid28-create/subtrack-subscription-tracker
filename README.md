# SubTrack — Subscription Tracker

A responsive subscription-tracking dashboard built with HTML, CSS, and vanilla JavaScript.

## Features
- Dashboard showing monthly spending, active subscriptions, yearly projection, and renewals due within 7 days
- Add subscriptions with price, currency, billing cycle, next bill date, and category
- Search subscriptions and filter by category or status
- Pause/reactivate or delete subscriptions
- Upcoming renewal list and spending snapshot chart
- Export subscription data to CSV
- Saves data in browser `localStorage`

## Run locally
1. Download or clone this repository.
2. Open `index.html` in your browser.

No build step or dependencies are required.

## Notes
- This is a frontend prototype; it does not include a backend or user authentication.
- Data is stored locally in the browser where the app is opened.
- Currency totals in the dashboard are illustrative if subscriptions use different currencies; the app does not perform exchange-rate conversion.

## Tech stack
- HTML5
- CSS3
- JavaScript
- Browser localStorage
