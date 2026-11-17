# AVENLO — The Room

Static website built with HTML, CSS and JavaScript. No paid libraries, product feed, affiliate link or checkout are included. The category pages show clearly labelled collection placeholders until genuine product details and approved retailer links are supplied.

## Preview

Open `index.html` in a browser. The category and legal pages are separate HTML files. The category search and filter, and mobile menu, run in `app.js`.

## Updating the edit

The category names, page copy and placeholder cards are currently configured in `app.js` near the top in the `categories` object. When adding a real recommendation, use a genuine product image you have permission to publish, a verified current price (or omit the price), retailer name, short factual description, and the affiliate URL supplied by the retailer. Add the required disclosure close to affiliate links. Do not describe AVENLO as an Amazon Associate until Amazon has approved the account.

## Before launch

- Replace the inactive newsletter preview with an email service and add its privacy/consent details.
- Configure the contact channel with a business email or form service.
- Review the draft legal policies for the actual services, business details and data handling.
- Add social links only when the accounts exist.
- Add products and affiliate links only after programme acceptance and retailer terms are confirmed.
- Add custom-domain DNS only if a domain is already owned; no domain is included.

## Free hosting

Cloudflare Pages supports static HTML deployment and allows custom domains. A Cloudflare account and an authenticated dashboard/CLI session are required to publish. The account owner must complete sign-in and authorize the site upload; never put passwords or API tokens in chat. For this plain site, use no build command and set `AVENLO` as the output directory (or upload the folder's contents). See the [Cloudflare Pages static HTML guide](https://developers.cloudflare.com/pages/framework-guides/deploy-anything/) and [plan limits](https://developers.cloudflare.com/pages/platform/limits/).

The site has not been published. No hosting account was connected during this build, so there is no verified live URL yet.
