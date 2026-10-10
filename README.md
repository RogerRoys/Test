# House of Flair · Homepage sections

Two Shopify theme sections built by Roys Studio for house-of-flair.com.

| File | Section name in theme editor | What it is |
|---|---|---|
| `sections/hof-hero-split.liquid` | HOF · Split hero | Text panel left, image right. Image stacks on top on mobile. |
| `sections/hof-press-logos.liquid` | HOF · As seen in | "As seen in" label plus a row of logos. 2×2 grid on mobile. |
| `assets/hof-hero-founders.jpg` | | Founders portrait (1000 × 1000), the chosen hero image. |
| `assets/hof-hero-table.jpg` | | Table photo, alternative hero image. |
| `assets/hof-logo-*.png` | | Marie Claire, What's On, AD, Mojeh cut from the current site. Low resolution: ask the client for vector or 2× logos when possible. |

## Install

1. Shopify admin → Online Store → Themes → the live theme (or a duplicate) → **Edit code**.
2. Under **Sections**, click *Add a new section*, name it `hof-hero-split`, paste the contents of `sections/hof-hero-split.liquid`, save.
3. Repeat for `hof-press-logos`.
4. Open the theme editor (**Customize**) → Home page → *Add section* → pick **HOF · Split hero**, then **HOF · As seen in** directly below it.
5. Hero: upload `assets/hof-hero-founders.jpg` as the image and set the button link. Copy is pre-filled.
6. As seen in: the preset creates four logo blocks. Upload one `hof-logo-*.png` per block (Files are under Content → Files, or pick directly in the block).
7. Drag both sections to the top of the page, above anything else.

Works with any Online Store 2.0 theme (Dawn, Sense, Craft, Impulse etc.). No other theme files need changes.

## Settings

**Hero**: eyebrow, two heading lines (line 1 accent colour, line 2 ink colour), rich text, button label and link, chip text on the image, desktop and optional mobile image, image side, focal point, text panel width, min height, heading sizes for desktop and mobile, all colours. Bebas Neue is loaded from Google Fonts for the heading; untick *Use Bebas Neue* to use the theme heading font instead.

**As seen in**: label, padding, max width, logo opacity, hairlines on/off, colours. Each logo block has image, name (alt text), optional article link and its own height so logos can be optically matched.
