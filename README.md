# Paris Taxi Connect — clean static starter

This is an EN/FR airport-transfer **prototype**, not a live booking system. It contains no server, database, authentication or payment collection. The quote request opens the visitor's email client with a draft and no preset recipient. Configure a real booking backend and verified business email before accepting actual bookings.

## Deploy without terminal
1. Create a **new** GitHub repository and upload the *contents* of this folder (not the ZIP).
2. In Render choose **New → Static Site**, connect the new repository.
3. Build command: leave blank. Publish directory: `.` (dot).
4. Deploy. Do not create a Web Service for this static prototype.

## Before production
- Add secure booking API and database with backups, spam protection and GDPR/privacy disclosures.
- Add verified customer/admin/driver authentication and role-based authorization.
- Integrate Stripe Checkout and signed webhook verification on a server, plus Stripe Connect driver onboarding and compliant payouts.
- Validate French taxi/VTC licensing, transport intermediary rules, insurance, terms, pricing and cancellation policies.
- Add real PWA icons and accessibility/operational tests.
