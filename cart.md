---
title: Cart
nav_order: 8
---

# Cart
{: .no_toc }

1. TOC
{:toc}

## Cart settings

In the theme editor, open **Theme settings > Cart**.

| Setting | What it does |
| --- | --- |
| Cart type | **Drawer** opens the cart from the side of the screen when visitors add a product, so they can keep shopping. **Page** takes them to the cart page. |
| Show vendor | Shows each product's vendor in the cart. |
| Show cart note | Lets customers add a note to their order, for example delivery instructions. |
| Empty cart collection | Products from this collection are suggested when the cart is empty. |
| Free shipping threshold | The order amount for free shipping, in your store currency, for example `50`. Leave it empty to hide the progress bar. |

## Free shipping progress

When you set a **Free shipping threshold**, the cart shows how much is left to reach free shipping, and a message when the order qualifies.

- The bar only shows a message: it doesn't change your shipping rates. Set up the free shipping rate itself in your Shopify admin, under **Settings > Shipping and delivery**, with the same amount.
- The bar shows when customers shop in your store's default currency. With other currencies it is hidden, because the converted amount might not match your shipping rates.

## Cart drawer

With **Cart type** set to Drawer, open the drawer in the theme editor preview with the cart icon, then click inside it: its settings open in the sidebar.

| Setting | What it does |
| --- | --- |
| Show product suggestions | Suggests the complementary products of the first item in the cart, or related products when it has none. See [Complementary products](product-page.md#complementary-products). |
| Heading | The title above the suggestions, for example "Complete your kit". |

## Cart page

The cart page, at `/cart`, is used when **Cart type** is Page, and when visitors open the cart link directly. In the theme editor, choose **Cart** in the page selector. Its settings are the color schemes of the page and of the order summary.

## What the cart shows

- Each product with its image, options, price and quantity, which customers can change or remove.
- Discounts on single products and on the whole order, with the amount saved.
- The subtotal, with a note about taxes and shipping.
- Dynamic checkout buttons, such as Shop Pay, PayPal or Apple Pay, depending on the payment methods your store offers. Their branded colors can't be changed.
