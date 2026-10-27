# Listing photo data

Open data about real estate listing photos, published by [October](https://www.october-ai.com) under [CC BY 4.0](LICENSE).

| Dataset | Files | Rows | What it holds |
|---|---|---|---|
| **MLS photo rules by MLS** | [`mls-photo-rules.csv`](data/mls-photo-rules.csv) · [`mls-photo-rules.json`](data/mls-photo-rules.json) | 22 MLSs | Photo limits, required shots, branding bans, virtual-staging labels, AI rules, original-photo requirements and fines at CRMLS, SDMLS, Bright MLS, Stellar MLS, NWMLS, Metro MLS, MLS Now, Unlock MLS, ARMLS, MLSListings, SFARMLS, RMLS, REcolorado, HAR MLS, MRED, NorthstarMLS, Canopy MLS, Doorify MLS, BeachesMLS, Southeast Florida MLS, OneKey MLS and MLS PIN. Every row is read from the MLS's own published rules, FAQ or support page, with the source URL and the date it was checked. |
| **Listing photo apps and services compared** | [`listing-photo-tools.csv`](data/listing-photo-tools.csv) · [`listing-photo-tools.json`](data/listing-photo-tools.json) | 58 tools | Capture apps, AI editors, human editing services, virtual staging, 3D tour and video tools for listing photos (Ovvy, Exposio, BoxBrownie, PhotoUp, Autoenhance.ai, Imagen, Virtual Staging AI, Collov AI, Matterport, October and more): who does the work, platforms, price basis, lowest published US-dollar price, the price in the vendor's words, turnaround, video, staging and labelling of altered photos. Every row is read from the vendor's own pages (two from dated captures), with the source URL and the date it was checked. |
| **Professional listing photo benchmarks** | [`listing-photo-benchmarks.json`](data/listing-photo-benchmarks.json) | 26 figures | What professional interior listing photos measure: lean of vertical lines (median 0.00° across 392 photos), focal length (median 18 mm full-frame equivalent), the brightness profile (L* percentiles), near-white share, wall colour, saturation, fine detail, styling faults and delivered size. Each figure has its sample size and method. |

Read them as pages:

- MLS photo rules: <https://www.october-ai.com/guides/mls-photo-rules-by-mls>
- Listing photo tools compared: <https://www.october-ai.com/guides/real-estate-photo-apps-compared>
- The study behind the benchmarks: <https://www.october-ai.com/guides/what-makes-listing-photos-look-professional>
- All open data, with changelog: <https://www.october-ai.com/data>

## Fields

Each JSON file carries its own field list (`fields`), licence, attribution line, date modified and changelog, so it can be used without this README.

**mls-photo-rules:** `mls`, `region`, `rules_cited`, `photo_limit`, `photo_requirements`, `min_size`, `branding_rule`, `virtual_staging_rule`, `ai_alteration_rule`, `originals_rule`, `fines`, `source_url`, `more_source_urls`, `checked`. An empty value means the rule was not stated on the pages we read. It does not mean the MLS has no such rule.

**listing-photo-tools:** `name`, `url`, `category`, `who_does_the_work`, `platforms`, `price_basis`, `price_from_usd`, `price_text`, `turnaround`, `makes_video`, `virtual_staging`, `labels_altered_photos`, `source_url`, `checked`, `guide_slug`. An empty value means the vendor's pages we read did not state it. Prices change often: check `source_url` before you rely on a row.

**listing-photo-benchmarks:** `id`, `marker`, `statistic`, `value`, `unit`, `sample_size`, `sample`, `method`, plus `section` and `as_published`, which give the study section and the figure exactly as the page prints it.

## How to cite

> Source: October, october-ai.com/data

For example: *"Across 392 professional interior listing photos, the median lean of vertical lines was 0.00° (October, october-ai.com/data)."*

## Caveats

- MLS rules change. Check the `checked` date, and confirm with the MLS before you rely on a row for a listing. This is not legal advice.
- The benchmark reference set is 392 professional interior photos from listings by Danish real estate brokerages, measured in September 2026. As a check, 120 photos from US agent listings had the same centre on all twelve markers, with a wider spread. Sample sizes differ per figure; each figure states its own sample and method.

## Updates

These files are exported from the same records that render the pages on october-ai.com, so the repo and the site always say the same thing. Corrections and new MLSs are welcome: open an issue with the MLS's own page as the source.

---

October turns a guided iPhone walk into professional listing photos and a walkthrough video, the same day. See <https://www.october-ai.com>.
