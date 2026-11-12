---
title: Product page
nav_order: 6
---

# Product page
{: .no_toc }

To edit the product page, open the theme editor and choose **Products > Default product** in the page selector at the top. Changes apply to every product that uses the template.

1. TOC
{:toc}

## Product information

The main section of the page: photos on one side, product details on the other.

| Setting | What it does |
| --- | --- |
| Media position | Photos on the Left or Right. |
| Media width | Medium, Large or Extra large share of the page. |
| Enable sticky product information | The details stay in view while visitors scroll through the photos. |
| Sticky add to cart bar | **Mobile and desktop**, **Mobile only** or **Off**. The bar appears at the bottom of the screen once the add to cart button scrolls out of view, and adds the product with the options chosen on the page. |
| Space between blocks | 8 to 48 px. |

### Media gallery

| Setting | What it does |
| --- | --- |
| Desktop layout | **Grid** shows all photos in two columns, the first one large. **Carousel with thumbnails** shows one photo at a time. On mobile, both become a swipeable carousel. |
| Image ratio | Adapt to image, Square or Portrait. |
| Enable image zoom | Photos open full screen, where visitors can zoom in. |
| Loop videos | Product videos play on a loop. |

When visitors choose a variant, its photo moves to the front. Videos and 3D models load only when visitors play them, so they don't slow down the page.

## Product blocks

Add, remove and reorder these blocks in the **Product information** section.

| Block | What it does |
| --- | --- |
| Vendor | The product vendor, optionally linking to the vendor's products. |
| Title | The product name. Keep it as the page's only H1. |
| Product rating | Stars and, optionally, the number of ratings. See [Product rating](#product-rating). |
| Price | The price, with the compare-at price when on sale. Options: sale badge, tax and shipping note, and the Shop Pay Installments banner when your store offers it. |
| Variant picker | One selector per option, as buttons or a dropdown, with color swatches. Choosing a color shows which sizes exist in that color. |
| Size guide | A link that opens your size guide in a side drawer. See [Size guide](#size-guide). |
| Buy buttons | Add to cart, optional quantity selector, and dynamic checkout buttons such as Shop Pay. For gift card products, a form to send the gift card to someone else on a chosen date, with a message. |
| Inventory status | In stock, low stock or out of stock. Set the **Low stock threshold** (0 to 20) and choose whether to show the quantity. Only for products whose inventory is tracked. |
| Pickup availability | Whether the product can be picked up in store. Shows when local pickup is turned on in **Settings > Shipping and delivery**. |
| Complementary products | Products that go well with this one. See [Complementary products](#complementary-products). |
| Fit scale | How the product fits, from "Runs small" to "Runs large". See [Fit scale](#fit-scale). |
| Description | The product description. |
| Fit and fabric | A list of details such as fabric, fit and care. See [Fit and fabric](#fit-and-fabric). |
| Collapsible row | A heading that opens to show text, or the content of a page. Choose one of 8 icons or none, and whether it is open by default. Use it for shipping, returns or care instructions. |
| Share | Opens the device's share options, or copies the product link where sharing isn't available. |
| Text, Heading, Icon, Button, Group, Custom Liquid | Any other content. |

Apps that add features to the product page, such as reviews or subscriptions, add their own blocks to this list.

## Color swatches

Swatches show the real color, or a pattern image, of each color option: on the product page and on product cards.

1. In your Shopify admin, open a product and set its **Category**, for example a clothing category.
2. When you add the color option under **Variants**, connect it to the **Color** category metafield and pick its values.
3. Each color value has a swatch color or image. Edit them in **Content > Metaobjects > Color**.

In the theme editor, turn on **Show swatches** in the Variant picker block, and **Show color swatches** in **Theme settings > Product cards**.

## Size guide

The size guide opens in a drawer, so shoppers can check their size without leaving the product page. The charts are kept in one page, and every product links to it.

1. In your Shopify admin, go to **Online Store > Pages** and create a page called, for example, "Size guide". Add your measuring instructions as the page content.
2. Under **Theme template**, choose **size-guide** and save.
3. In the theme editor, open the page and edit its **Table** sections: one per chart, for example tops, bottoms and shoes. See [Table](sections/storytelling.md#table) for the cm / in switch.
4. Open the product page template, choose the **Size guide** block and select your page.

The drawer shows the page text and its tables, in the same order as on the page. With another page template, the drawer shows the page content only.

## Fit scale

The fit scale shows a marker on five steps: 1 means the product runs small, 3 true to size and 5 runs large. The labels under the scale can be changed.

To give each product its own fit:

1. In your Shopify admin, go to **Settings > Custom data > Products** and choose **Add definition**. Name it, for example, "Fit", and choose the **Integer** type, with minimum 1 and maximum 5.
2. Fill in the value on each product page in the admin.
3. In the theme editor, choose the **Fit scale** block, then the **Connect dynamic source** icon next to **Fit value**, and pick your metafield.

Products without a value don't show the scale.

## Fit and fabric

A heading and a list of rows, each with a label and a value, for example "Fabric: 78% recycled polyester, 22% elastane".

Add a **Row** block for each detail. Type the label, then connect the value to a product metafield (single line or multi-line text) with the **Connect dynamic source** icon, so each product shows its own value. Rows without a value are hidden, so products can have different details.

## Product rating

The stars come from Shopify's standard product rating metafields. Review apps usually fill them in: check in your app's settings that it saves ratings to Shopify's product metafields. The rating shows in the **Product rating** block and, when turned on in **Theme settings > Product cards**, on product cards.

## Complementary products

The **Complementary products** block shows products you choose for each product, for example a bottle and a towel for a training top. The cart drawer suggests them too.

Set them in the free **Shopify Search & Discovery** app: open **Product recommendations**, choose a product and add its complementary products. Products without complementary products don't show the block.

## Related products

The **Related products** section, below the product information, shows products similar to the current one, chosen automatically by Shopify. You can also choose them by hand in the Search & Discovery app.

| Setting | What it does |
| --- | --- |
| Heading, Heading size | The title of the section. |
| Products to show | 2 to 10. |
| Columns on desktop | 2 to 5. |

## 3D models

Sinew shows 3D models in the product media gallery and in three sections: [Product in 3D](sections/products.md#product-in-3d), [Feature tour](sections/products.md#feature-tour) and [Zoom reveal](sections/media.md#zoom-reveal). 3D is optional: products without a model show their photos.

To add a model, open the product in your Shopify admin and add the **.glb** file to its media, like a photo.

In the **Product in 3D** section, visitors can switch colors with swatches. To give a color its own model, put the color's name in the file name, for example `shoe-black.glb`, or in the model's alt text.

### Getting a 3D model

If you don't have 3D models yet, there are a few ways to get one:

- **Ask your manufacturer or designer.** Many products are designed in 3D software, and the file can often be exported as .glb.
- **Scan the product with a phone.** 3D scanning apps build a model from photos or from the phone's depth sensor. They work best with solid, matte objects such as shoes, bottles and equipment. Soft garments, shiny or transparent surfaces are harder to scan well.
- **Hire a 3D artist.** Freelancers and studios create accurate models from your photos or samples. You can find Shopify experts in the Shopify Partner Directory.
- **Generate it from a photo.** AI tools can turn a product photo into a 3D model in minutes. Results vary, so check the shape, colors and back of the product before publishing.

For a model that loads fast and looks right:

- Keep the file small, ideally under 10 MB, with textures no larger than 2048 x 2048 px.
- Use the real size of the product, centered, standing upright.
- Check the model in a free viewer, such as the model-viewer editor at [modelviewer.dev/editor](https://modelviewer.dev/editor/), before you upload it.

{: .note }
Sinew displays 3D models but doesn't create them. Support can't help with making or fixing 3D files.
