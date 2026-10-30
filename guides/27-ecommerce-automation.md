# E-commerce video automation

[← Back to library](../README.md)

**Purpose:** Practical reference for e-commerce video automation in AI video advertising.

## 1. Catalog ingestion

**How to use:** Read approved SKU, product name, images and verified features.

**Example:** CSV columns: sku, title, image_path, feature_1, claim_source.

## 2. Template selection

**How to use:** Map each SKU to a shot sequence.

**Example:** Beauty macro vs electronics demo.

## 3. Prompt assembly

**How to use:** Insert approved fields into a reusable prompt template.

**Example:** Never invent missing attributes.

## 4. Generation queue

**How to use:** Track status and retries for each clip.

**Example:** queued, generated, review, approved, rejected.

## 5. Quality gate

**How to use:** Check product match, text, claims and motion.

**Example:** Manual review before release.

## 6. Localization and export

**How to use:** Create market-specific captions and formats.

**Example:** 9:16, 4:5 and 16:9 versions.

## Reusable prompt pattern

```text
Create a product advertisement for [EXACT PRODUCT] using catalog ingestion.
Scene: [SETTING]. Action: [ONE PHYSICAL ACTION]. Camera: [ONE MOVEMENT].
Lighting: [LIGHTING]. Duration: [SECONDS]. Aspect ratio: [RATIO].
Preserve product geometry, packaging and approved brand identity.
Use only verified product claims. Add text and logos in post-production.
```

**Production check:** Review the final video frame by frame for geometry, physics, continuity, claims and licensing.
