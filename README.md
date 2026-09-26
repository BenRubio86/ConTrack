# ConTrack V2.3

## New: optional pain intensity per contraction
- Optional 0–10 pain intensity rating.
- Never required to save a contraction.
- Quick post-contraction rating with one-tap 0–10 buttons and a “Later” option.
- Rating can be added, changed, or removed later in History/Edit.
- Latest pain rating shown near the latest timing facts.
- History shows pain rating per contraction.
- Optional pain-rating strip below the unified timing chart, aligned to the same contraction timestamps.
- Summary includes latest pain rating, rated-count, and recorded pain range.
- CSV adds `pain_intensity` and `pain_rated_at_iso`.
- JSON naturally preserves the new fields.
- Existing V1/V2/V2.1/V2.2 data remain compatible and receive `painIntensity: null` until rated.

Pain ratings remain subjective user-entered values and do not affect labor pattern calculations or medical guidance.

## Existing features preserved
- 11-language flag dropdown
- RTL Farsi / Arabic
- 5-design Design Studio
- chart near the top
- local/offline storage
- editable history and notes
- factual summaries and exports
- Dark/Light/Auto, large text, reduced motion and haptics
