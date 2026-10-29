# Tavelo Home Shopify Theme

Custom Shopify Online Store 2.0 theme for `tavelohome.myshopify.com`, using Liquid, JSON templates, CSS and JavaScript.

## Theme features
- Responsive homepage sales journey: hero, steps/benefits, featured product, FAQs and opt-in newsletter signup.
- Product page with Shopify-native variant selection, add-to-cart and accelerated checkout button, shipping/returns links and FAQs.
- Collection, cart, search, standard page, contact and 404 templates.
- Footer links to Shopify policy routes for shipping, returns/refunds, privacy and terms.
- Brand settings for logo, colour palette and announcement bar.

## Connect to Shopify
In Shopify Admin, go to **Online Store → Themes → Add theme → Connect from GitHub** and select repository `Vishal091/travelo`, branch `shopify-theme`. Keep it unpublished until the preview and checkout have been tested.

## Store content that must be completed in Shopify Admin
1. **Products:** verify exact SKU, dimensions, weight, material, compatible drain types, imagery, inventory syncing and variant prices.
2. **Settings → Policies:** add and review shipping, refund/return, privacy and terms policies. Use the drafts in `docs/POLICY-COPY-AND-LAUNCH-CHECKLIST.md`; fill every bracketed item before publishing.
3. **Settings → Store details:** configure a monitored support email and accurate business details.
4. **Content → Menus:** configure the main menu. The theme adds an FAQs link when the selected main menu doesn't already contain one.
5. **Pages:** create a Contact page using the `contact` page template; the footer links to `/pages/contact`.
6. **Markets, currency, shipping and tax:** enable only destinations and rates you can fulfil. Ensure the checkout currency and product prices are correct.
7. **Meta Ads:** connect the official Facebook & Instagram by Meta sales channel, configure the pixel/data-sharing level and verify events. Do not add a second pixel manually if Shopify's channel already handles it.

## Policy notes
Shopify's policy pages live in Shopify Admin, not in the theme repository. This theme provides links to Shopify's built-in policy routes; the actual policy content must be entered and reviewed in Admin. Shopify's official guide: https://help.shopify.com/en/manual/checkout-settings/refund-privacy-tos.

## Pre-launch quality checks
- Run Shopify Theme Check and preview desktop/mobile.
- Test variant selection, add-to-cart, cart quantity updates, checkout, newsletter consent and contact form routing.
- Verify every policy/contact link, contact email, shipping rates and return instructions.
- Place a test order before publishing.
- Never use unverified stock, customer reviews, delivery promises, product claims or fake discounts.
