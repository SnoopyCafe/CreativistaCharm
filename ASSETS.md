# Asset provenance

Every raster shipped by the prototypes, where it came from, and what still needs clearing.
No image in this project was generated; all are pre-existing files pulled from the live
WordPress site at https://creativistacharm.com on 2026-08-17.

Originals are kept unmodified in `assets/images/`, **on disk only — they are gitignored**
because they total roughly 44 MB. The repository ships only the optimized derivatives in
`assets/images/opt/` (WebP, resized), about 864 KB in total. The table below records what
each original was, so a lost original can be re-sourced.

| Shipped file | Origin | Status |
|---|---|---|
| `opt/logo-900.webp` | `image.jpg` — Creativista Charm logo, square | Owned by Creativista Charm LLC |
| `opt/logo-wide-1400.webp` | `cropped-creativista-charm-logo.jpg` — logo, wide crop | Owned by Creativista Charm LLC |
| `opt/tia-900.webp` | `me-photo-995-c397-720-px.png` — Tia S. Miller portrait | Owned / subject is the owner |
| `opt/media-kit-1600.webp` | `media-kit-5760-x-3840.png` — media kit graphic | Owned by Creativista Charm LLC |
| `opt/students-1800.webp`, `opt/students-900.webp` | `adobestock_455007359.jpeg` — five students in a classroom | **AdobeStock. License must be confirmed.** |
| `opt/hands-1600.webp` | `adobestock_331061271.jpeg` — children's hands stacked | **AdobeStock. License must be confirmed.** |

## Not shipped

- `adobestock_288069459.jpeg` — a whiteboard diagram of client-service words. Dated stock,
  weak for this audience, and it duplicates copy the pages already carry. Left in
  `assets/images/` but referenced by nothing.
- `img_7790.jpg` — a JPEG collage of eight press logos. The outlets are named as text in all
  three prototypes instead. Reproducing third-party broadcast and newspaper logos is a
  separate permission question, and the text treatment reads better at every width.

## Before launch

1. **Confirm the AdobeStock license carries to this project.** Three photographs were
   licensed for the original site; that license belongs to whoever purchased it and does not
   automatically extend to a new build or a new domain. If it does not carry, replace
   `students-*` and `hands-*` with owned photography of real programs, which would be
   stronger material anyway.
2. Replace the placeholder social links in every footer with the real Facebook and Instagram
   URLs. They currently point at the platform roots.
