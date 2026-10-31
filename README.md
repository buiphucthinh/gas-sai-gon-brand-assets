# Gas Sài Gòn — brand assets (public)

Home banners for the Gas Sài Gòn Zalo Mini App, served through jsDelivr:
`https://cdn.jsdelivr.net/gh/buiphucthinh/gas-sai-gon-brand-assets@v1/banners/v1/<category>/<id>.webp`

`banners/v1/manifest.json` lists every banner and its category (`gas`, `stoves`, `equipment`, `all`).
Images are approved marketing artwork (1080×720 WebP). Do not overwrite files under a published tag; add `v2`.

## Product photos (tag v2)

The 50 original catalogue photos for the 49 Gas Sài Gòn products, byte-identical to the Mini App source
(no logo or frame — the app adds the stage and stacked logo at runtime):
`https://cdn.jsdelivr.net/gh/buiphucthinh/gas-sai-gon-brand-assets@v2/products/v2/<imageId>.webp`

`products/v2/manifest.json` lists each image with its size, SHA-256 and the products that use it.
Tag `v2` also keeps every `banners/v1` file unchanged.

## Finished product artwork (v3)

`products/v3/` contains 50 finished 1080×1080 WebP images for the same 49
products. Each file already includes the real product photograph, the approved
white/navy/red Gas Sài Gòn studio background and the original **stacked** logo
(flame above GAS SAI GON / Natural Power).

After the operator publishes an immutable `v3` tag, the image route is:
`https://cdn.jsdelivr.net/gh/buiphucthinh/gas-sai-gon-brand-assets@v3/products/v3/<imageId>.webp`

**Render v3 directly as one IMG. Do not apply the v2 source-photo mask, another
product stage or another logo.** The image IDs and product IDs are unchanged.
`products/v3/manifest.json` maps each file to its products and `main`/`gallery`
role, with exact bytes and SHA-256. The extra image is the gallery view of
`web-2666` (VT-GAS 45 kg), not an additional SKU.

The background and logo are the merchant-approved Gas Sài Gòn brand assets.
The product's real structure, labels, colour and source photographic pose are
preserved; no replacement product details were generated. Small source photos
are enlarged at most 2×. In particular the brass regulator's original product
region is only about 244×120 pixels and remains optically soft. Tiny source JPEG
colour fringes and baked-in source marks may remain rather than deleting real
metal or printed detail. 1080×1080 is the artwork canvas, not a claim of recovered
high-resolution source detail.

All v2 original-photo files and published tags remain unchanged. This public
manifest contains only public product names, identifiers, website links and
image checksums; no internal reports, customer data or credentials.
