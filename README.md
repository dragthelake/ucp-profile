# ucp-profile

Public UCP (Universal Commerce Protocol) agent-profile for **DRAG THE LAKE**.

`dragthelake.json` is fetched by Shopify's Catalog API when the app makes
requests (passed as `params.arguments.meta["ucp-agent"].profile`). It must be
served as `application/json` — GitHub Pages does this by file extension.

Live URL: https://dragthelake.github.io/ucp-profile/dragthelake.json
