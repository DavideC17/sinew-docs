---
title: Images and video
parent: Sections
nav_order: 1
---

# Images and video
{: .no_toc }

1. TOC
{:toc}

## Hero

A large image or video with a heading and buttons, usually the first section of the home page.

| Setting | What it does |
| --- | --- |
| Image | The background image. |
| Mobile image | Optional. Shown on screens narrower than 750 px instead of the image, for example a portrait crop. |
| Background video | Plays muted and on a loop, with a pause button. Replaces the image. |
| Overlay opacity | 0 to 90 %. Tints the image with the background color so the text stays readable. |
| Image position | Four sliders: horizontal and vertical on desktop, horizontal and vertical on mobile. See below. |
| Height | Small, Medium, Large or Full screen. |
| Content position | Vertical (top, middle, bottom) and horizontal (left, center, right) position of the text, and its maximum width. |
| Enable parallax effect | The image moves slightly slower than the page while scrolling. |
| Show scroll hint | Shows an arrow inviting visitors to scroll. |

**Blocks:** add headings, text, buttons, icons and other theme blocks to build the content. The **Background text** block shows a large word behind the content, outlined or solid, which can slide while scrolling.

### Image position

When the screen crops the image or video, the sliders choose the part that stays in view: 0 % is the left or top edge, 100 % the right or bottom edge. For example, on a tall phone screen a landscape photo is cropped at the sides: move **Horizontal on mobile** toward the athlete to keep them in view.

When the sliders for a screen size are both at 50 %, the image's [focal point](../getting-started.md#focal-points-and-image-position) is used instead.

## Slideshow

Up to 6 slides, each with its own image, text and buttons.

| Setting | What it does |
| --- | --- |
| Accessible name | Describes the slideshow to screen reader users, for example "Spring collection". |
| Height | Small, Medium or Large. |
| Autoplay slides | Changes the slide every 4 to 10 seconds. Visitors can pause it. |

**Slide blocks:** image, optional mobile image, subheading, heading, text, two buttons, content position, overlay opacity and color scheme.

## Mosaic

A grid of large tiles that link to collections or any page. Each tile can show an image or a looping video.

| Setting | What it does |
| --- | --- |
| Subheading, Heading | Optional, above the grid. |
| Row height | 160 to 400 px. Tall and Large tiles span two rows. |
| Spacing | 0 to 32 px between tiles. |

**Blocks** (up to 8): **Collection** (uses the collection's title and image unless you replace them), **Image** and **Video**. Each tile has a subheading, heading, button label, link, color scheme and **Tile size**: Standard, Wide, Tall or Large. The whole tile is clickable.

{: .tip }
Mix sizes to build the grid: for example one Large tile next to two Standard tiles, then a Wide tile.

## Video

A YouTube or Vimeo video, or a video uploaded to your Shopify files, with a cover image and a play button.

| Setting | What it does |
| --- | --- |
| Video link | A YouTube or Vimeo link. |
| Video | A video from **Content > Files**, used instead of the link. |
| Cover image | Shown until visitors press play. The video loads only then, which keeps the page fast. |
| Video description | Describes the video for screen reader users. |
| Full width | Spans the full width of the screen. |

## Zoom reveal

A large word with an image, video or 3D model showing through its letters. As visitors scroll, the word zooms in until the media fills the screen, then a heading and a button appear.

| Setting | What it does |
| --- | --- |
| Word | One short word works best, for example `MOVE`. |
| Text size | 10 to 40 % of the screen width. Lower it for longer words. |
| Zoom focus | The horizontal point the zoom flies into. Place it on a letter to pass through it. |
| Scroll length | Short, Medium or Long: how far visitors scroll while the word zooms in. |
| Image, Background video | The media inside the word. |
| 3D model | A product with a 3D model takes the place of the image. Visitors can turn it at the end of the scroll. See [3D models](../product-page.md#3d-models). |
| 3D background | Shows behind the 3D model and inside the word. |
| Heading, Button label, Button link | Shown after the zoom. |

With reduced motion, or in browsers without scroll animations, the word stays still and the content shows normally.

## Shoppable image

A lifestyle photo with dots on the products it shows. Visitors select a dot to see the product and add it to the cart.

| Setting | What it does |
| --- | --- |
| Image | The photo. |
| Subheading, Heading, Text, Button | The text next to the image. |
| Show product list | Lists the products of the dots under the text, with an add to cart button for products with one variant. |
| Layout | Image on the right, on the left, or below the heading. On mobile the image is always below the text. |
| Image ratio | Adapt to image, Square, Portrait, Landscape or Wide. |
| Image position | When the ratio crops the photo, two sliders choose the part that stays in view, on every screen. At 50 % and 50 % the image's focal point is used. |
| Maximum image height | 300 to 1000 px. The width shrinks to match, so the image is never stretched. |
| Card color scheme | Colors of the product card that opens from a dot. |

**Hotspot blocks** (up to 8): choose a product, then move the dot with the **Horizontal position** and **Vertical position** sliders (distance from the left and top edges of the image).

{: .note }
Dots are placed on the image as you see it in the editor. After changing the image ratio or the image position, check that each dot still sits on its product.
