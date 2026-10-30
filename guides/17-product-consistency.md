# Product consistency techniques

[← Back to library](../README.md)

**Purpose:** Practical reference for product consistency techniques in AI video advertising.

## 1. Reference sheet

**How to use:** Collect front, back, left, right, top and macro views of the exact product.

**Example:** Lock logo, button count, materials, color and silhouette.

## 2. First and last frame

**How to use:** Specify opening and ending compositions where tool supports it.

**Example:** Begin front-facing and end at three-quarter angle.

## 3. Shot continuity

**How to use:** Record camera direction, product orientation and lighting for each shot.

**Example:** All product shots use key light from upper left.

## 4. Identity lock

**How to use:** Describe fixed features separately from actions.

**Example:** Fixed: silver lid, green label, cylindrical bottle; motion: slow 30-degree rotation.

## 5. Continuity log

**How to use:** Track approved source asset, model, prompt, seed if available and output.

**Example:** Log each clip ID, aspect ratio and approval status.

## 6. Compositing

**How to use:** Replace inaccurate labels and interfaces with verified source artwork.

**Example:** Overlay authentic product label in post-production.

## Reusable prompt pattern

```text
Create a product advertisement for [EXACT PRODUCT] using reference sheet.
Scene: [SETTING]. Action: [ONE PHYSICAL ACTION]. Camera: [ONE MOVEMENT].
Lighting: [LIGHTING]. Duration: [SECONDS]. Aspect ratio: [RATIO].
Preserve product geometry, packaging and approved brand identity.
Use only verified product claims. Add text and logos in post-production.
```

**Production check:** Review the final video frame by frame for geometry, physics, continuity, claims and licensing.
