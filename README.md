# PHOENIX SHOP

A lightweight, mobile-friendly static storefront for PHOENIX SHOP.

## Current features
- Responsive product catalogue
- Product search and category filter
- Add items to an order list
- Build an order message for Telegram
- No database, server, API key, or paid dependency required

## Add your shop details
Open `index.html` and edit the `STORE` object near the bottom:
- `name`, `headline`, and `about`
- `telegramUsername` (username only, without @)
- Add products to `products`, for example:

```js
{ id: "p001", name: "Product name", category: "General", price: 5000, description: "Description", image: "https://example.com/image.jpg" }
```

Use a unique `id` for every product. Prices are numeric and shown in MMK.

## Publish with GitHub Pages
In the repository, open **Settings → Pages**. Choose **Deploy from a branch**, select **main** and **/(root)**, then Save. GitHub will provide the public Pages URL after deployment.

## Important limitations
This is a static storefront. It does not create customer accounts, process payments, or save incoming orders to a shared server. Customers send the prepared order message to the shop's Telegram account; the shop owner confirms availability, delivery, and payment separately.
