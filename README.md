# Grace Points · 恩之果積分

An interactive bilingual prototype for a Hong Kong primary-school reward system.

## Demo pages

- **Student page (`index.html`):** use the public class-number login (`P.5 愛 12`) to view a balance and transaction history.
- **Teacher portal (`teacher.html`):** browse by class or cross-class subject group, search students by class, award points with an optional reason, review activity, and reverse a transaction.
- **Admin portal:** open it from the teacher header with demo PIN `2026`, then compare participation, add allowance, export a CSV report, and preview annual rollover.

This is a front-end demonstration using in-memory sample data. Refresh the page to reset it. It does not yet connect to Cloudflare D1 or Google authentication.

## Run locally

Open `index.html`, or serve the directory with any static web server:

```sh
python3 -m http.server 4173
```
