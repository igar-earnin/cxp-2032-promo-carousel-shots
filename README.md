# CXP-2032 promo carousel before/after screenshots

Android emulator captures of production `PromotionCarouselContent` / `PromotionCarouselV2Content` for https://github.com/activehours/android/pull/27095

Each row image is **Legacy | DSV2 before | DSV2 after**.

Pagination, peek, and gutters match production Compose (not the earlier HTML leftover that left-aligned DSV2 ticks):

- Both carousels center the indicator group in the carousel width (`Alignment.CenterHorizontally`).
- Legacy uses `img_promotion_indicator_*` dashes (19dp / 5dp, 4dp gap, black 68% / 24%).
- DSV2 uses the same visual dash sizes with `fg.secondary` / `fg.disabled` and 8dp layout gap.
- Multi-card peek: 16dp gutter, 4dp page gap, 20dp adjacent peek, first card = viewport − 40dp.
