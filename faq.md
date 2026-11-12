---
title: FAQ
nav_order: 11
---

# Frequently asked questions
{: .no_toc }

1. TOC
{:toc}

## Setup

### Can I try Sinew before buying it?

Yes. In the Shopify Theme Store, choose **Try theme**: Sinew is added to your theme library, where you can customize it with your own products. You buy it only when you want to publish it.

### How do I change a text such as "Add to cart"?

In your Shopify admin, go to **Online Store > Themes**, open the **...** menu next to Sinew and choose **Edit default theme content**. Search for the text and type your own.

### Which languages does Sinew support?

The storefront text is translated into English, French, German, Italian, Portuguese (Brazil) and Spanish, and the theme editor into the same languages. To sell in several languages, add them in **Settings > Languages**, and turn on the language selector in the header or footer.

### Why doesn't the country/region or language selector show?

The selectors show only when you sell in more than one country or region (**Settings > Markets**) or have more than one published language (**Settings > Languages**), and when they are turned on in the header or footer settings.

### Does Sinew work with apps?

Yes. Apps add their own blocks to sections, such as review stars or subscription options on the product page, and some add app embeds, which you turn on in the theme editor under **App embeds**.

## Products and collections

### Why don't color swatches show?

Swatches need the color option to be connected to the Color category metafield, with a color or image for each value. See [Color swatches](product-page.md#color-swatches). Then check that **Show swatches** is on in the Variant picker block and **Show color swatches** in **Theme settings > Product cards**.

### Why don't filters show on my collection?

Check that **Enable filtering** is on in the Product grid section, and that the filters are set up in the Shopify Search & Discovery app. A filter shows only when the products of the collection have values for it.

### Why don't star ratings show?

Ratings come from your review app. Check that the app saves ratings to Shopify's standard product rating metafields, then turn on the **Product rating** block, or **Show product rating** in **Theme settings > Product cards**. See [Product rating](product-page.md#product-rating).

### How do I add a size chart?

Build it once in a page that uses the size-guide template, then link it from the Size guide block. See [Size guide](product-page.md#size-guide).

### Where do I get 3D models of my products?

See [Getting a 3D model](product-page.md#getting-a-3d-model).

### Infinite scroll stops after a few pages. Is that normal?

Yes. Infinite scroll loads more products up to 4 times in a row, then shows a button, so visitors can still reach the footer and its links.

### The dots of my shoppable image moved. Why?

Dots are placed on the image as you see it in the editor. Changing the image, its ratio or its position changes the crop, so move the dots again with their position sliders.

## Cart and checkout

### Why does the free shipping bar disappear for some customers?

The bar shows only when customers shop in your store's default currency, because a converted amount might not match your shipping rates. See [Free shipping progress](cart.md#free-shipping-progress).

### Can I change the colors of the Shop Pay or PayPal buttons?

No. Dynamic checkout buttons keep the colors of their brand, as required by the payment providers and Shopify.

## Design and behavior

### The newsletter popup doesn't show. Why?

The popup opens once per visitor, after the delay you set, and then stays hidden for the number of days you choose. To see it again, open your store in a private browser window. In the theme editor it opens only when you select its section.

### Some animations don't play on my device. Why?

Your device probably has reduced motion turned on, in its accessibility settings. Sinew then shows the content without movement, as these visitors expect.

### Is Sinew accessible?

Sinew is built for keyboard and screen reader users: visible focus, labelled controls, a skip link, headings in order, pause buttons on moving content and support for reduced motion. The colors of the default presets meet contrast guidelines. When you change colors, check that text stays readable.

### Which browsers does Sinew support?

The latest versions of Chrome, Safari, Firefox and Edge on desktop; Safari, Chrome and Samsung Internet on mobile; and the in-app browsers of Instagram, Facebook and Pinterest.

## Updates and code

### How do I update Sinew?

When a new version is released, Shopify shows it in **Online Store > Themes**. Updating adds the new version to your theme library with your theme editor settings and content, so you can check it before publishing. Code you edited yourself is not carried over.

### Can I edit the theme code?

Yes, but code edits are not covered by support and are lost when you update the theme.

{: .warning }
Always duplicate your theme before you edit its code: in **Online Store > Themes**, open the **...** menu next to Sinew and choose **Duplicate**. Make your changes on the copy and publish it only when everything works.
