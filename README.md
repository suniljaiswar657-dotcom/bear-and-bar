# BEAR & BAR

Independent BEAR & BAR online + offline retail platform.

## Current storefront preview
- Responsive, mobile-first premium storefront with editorial art direction
- Four discovery categories: drinks, food, barware and experiences
- Search and category filters
- Product cards with distinct photography and illustrative sample prices
- Functional browser-local demo bag with quantity controls and subtotal
- Store control preview panel
- Age confirmation notice (front-end only; not legal identity verification)

## Important limitations
- Product catalogue, prices and images are sample content and are not verified store inventory.
- Cart state is browser-local and is not persisted to a server.
- No customer accounts, live inventory, staff authentication, order submission, payment, POS transaction records or delivery integration is connected.
- Age-restricted items are displayed as in-store-only category previews and cannot be added to the bag. No alcohol checkout, payment or delivery is enabled.
- Do not use the front-end age notice as legal compliance. Applicable licences, age/identity verification, retail and delivery rules must be confirmed for the operating jurisdiction before any restricted-product sales are enabled.

## Run locally
Open `index.html` in a browser.

## Deploy on Vercel
The repository is connected to Vercel for Git-based deployments. Framework preset: **Other**; no build command is required; output directory: `.`.

## Inputs required before production launch
- Confirmed business address, jurisdiction, licences and operating hours
- Approved product catalogue, actual stock, product images and pricing
- Contact details and customer-service policy
- Approved payment, POS, inventory and order-management architecture
- Legal review of age-restricted product display, sale, fulfilment and delivery
