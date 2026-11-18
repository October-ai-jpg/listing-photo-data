---
license: cc-by-4.0
language:
- en
pretty_name: US Real Estate Listing Photo Data (prices, MLS rules, platform requirements)
size_categories:
- n<1K
task_categories:
- table-question-answering
tags:
- real-estate
- real-estate-photography
- listing-photos
- virtual-staging
- mls
- airbnb
- proptech
- pricing
- open-data
configs:
- config_name: real_estate_video_app_prices
  data_files: data/real-estate-video-app-prices.csv
- config_name: floor_plan_prices
  data_files: data/floor-plan-prices.csv
- config_name: listing_photo_tools
  data_files: data/listing-photo-tools.csv
- config_name: mls_photo_rules
  data_files: data/mls-photo-rules.csv
- config_name: photographer_prices
  data_files: data/photographer-prices.csv
- config_name: platform_photo_requirements
  data_files: data/platform-photo-requirements.csv
- config_name: real_estate_photo_editing_prices
  data_files: data/real-estate-photo-editing-prices.csv
- config_name: real_estate_video_prices
  data_files: data/real-estate-video-prices.csv
- config_name: vacation_rental_photography_prices
  data_files: data/vacation-rental-photography-prices.csv
- config_name: virtual_staging_prices
  data_files: data/virtual-staging-prices.csv
- config_name: virtual_tour_software_prices
  data_files: data/virtual-tour-software-prices.csv
---

# Listing photo data

DOI: [10.5281/zenodo.24324406](https://doi.org/10.5281/zenodo.24324406) · Source repository: [GitHub](https://github.com/October-ai-jpg/listing-photo-data) · Pages: [october-ai.com/data](https://www.october-ai.com/data)

Open data about real estate listing photos, published by [October](https://www.october-ai.com) under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

| Dataset | Files | Rows | What it holds |
|---|---|---|---|
| **Real estate photography prices** | [`photographer-prices.csv`](data/photographer-prices.csv) · [`photographer-prices.json`](data/photographer-prices.json) | 154 price lists | Published prices of 154 US real estate photographers and photo companies in 24 metros, read from each business's own pricing page on 3 November 2026: the base photo package by home size (under 1,500 / 1,500–3,000 / 3,000–4,500 sq ft), photos included, turnaround, and the drone, video, twilight and 3D tour add-ons, with the source URL, the date read and comparability notes. Summary: median $225 for a 1,500–3,000 sq ft home (middle half $195–$264). |
| **Real estate video prices** | [`real-estate-video-prices.csv`](data/real-estate-video-prices.csv) · [`real-estate-video-prices.json`](data/real-estate-video-prices.json) | 125 price lists | Published listing video prices of 125 US real estate videographers, photographers and photo companies in 24 metros, read from each business's own pricing page on 18 November 2026: video on its own and as an add-on, photo-and-video packages, cinematic video, social reels, agent on camera and drone video, with length, turnaround, whether the video is filmed, the source URL and notes. Summary: median $290 for the cheapest filmed listing video (middle half $215–$361). |
| **Vacation rental (Airbnb) photography prices** | [`vacation-rental-photography-prices.csv`](data/vacation-rental-photography-prices.csv) · [`vacation-rental-photography-prices.json`](data/vacation-rental-photography-prices.json) | 63 price lists | Published prices of 63 photographers who shoot vacation rentals in 24 US markets (Smoky Mountains, Destin-30A, Orlando-Kissimmee, Scottsdale, Lake Tahoe, Maui and more), read from each business's own page on 18 November 2026: smallest and large rental packages, whether the package is named for Airbnb or vacation rentals, photos included, twilight, drone, video and 3D tour add-ons, lifestyle or styling. Summary: median $250 for a small rental; $300 for packages named for vacation rentals, $199 for general real estate packages. |
| **Real estate video app prices** | [`real-estate-video-app-prices.csv`](data/real-estate-video-app-prices.csv) · [`real-estate-video-app-prices.json`](data/real-estate-video-app-prices.json) | 27 tools | Published prices of 27 apps and tools that make listing videos (from photos, from a phone recording, AI agent videos, general editors), read from each tool's own page or US App Store listing on 18 November 2026: one video, cheapest monthly plan, what is free, output, voiceover and music, platforms. Summary: the 9 real estate video tools with a monthly plan start at a median of $33 a month. |
| **Floor plan prices** | [`floor-plan-prices.csv`](data/floor-plan-prices.csv) · [`floor-plan-prices.json`](data/floor-plan-prices.json) | 24 providers | Published prices of 24 floor plan providers for property listings (drawing services, scan platforms, DIY apps), read from each provider's own page on 18 November 2026: cheapest 2D and 3D plan, monthly plans, what is free, turnaround, size limit, what you send and what the page says about measurements. Summary: drawing services with a dollar price median $38 for a 2D plan, usually per floor. |
| **Real estate photo editing prices** | [`real-estate-photo-editing-prices.csv`](data/real-estate-photo-editing-prices.csv) · [`real-estate-photo-editing-prices.json`](data/real-estate-photo-editing-prices.json) | 27 providers | Published prices of 27 real estate photo editing providers (human editing services, AI editors, AI with human review), read from each provider's own page on 18 November 2026: one photo, lowest per-photo price through a pack or plan, cheapest monthly plan, turnaround, item removal, virtual twilight and sky replacement. Summary: one photo from a median of $0.99 (human services) and $0.80 (AI), mostly starting-at prices. |
| **Virtual tour software prices** | [`virtual-tour-software-prices.csv`](data/virtual-tour-software-prices.csv) · [`virtual-tour-software-prices.json`](data/virtual-tour-software-prices.json) | 27 products | Published prices of 27 virtual tour products used for real estate listings (360 photo tour software, 3D scan platforms, tour + floor plan services), read from each provider's own page on 18 November 2026: free plan, cheapest plan billed monthly and yearly, what it includes, price per tour, camera, floor plan price, MLS-ready links and what happens to tours when you stop paying. Summary: the 9 360 tour tools with a monthly plan start at a median of $20 a month. |
| **Virtual staging prices** | [`virtual-staging-prices.csv`](data/virtual-staging-prices.csv) · [`virtual-staging-prices.json`](data/virtual-staging-prices.json) | 27 providers | Published virtual staging prices of 27 providers made for listing photos (AI tools, designer services, DIY software), read from each provider's own pricing page on 18 November 2026: one photo, lowest per-photo price through a pack or plan, cheapest monthly plan, free trial, turnaround, revisions, furniture removal, virtual twilight and labelling. Summary: designer staging median $34 for one photo; AI tools' cheapest monthly plans median $27. |
| **MLS photo rules by MLS** | [`mls-photo-rules.csv`](data/mls-photo-rules.csv) · [`mls-photo-rules.json`](data/mls-photo-rules.json) | 22 MLSs | Photo limits, required shots, branding bans, virtual-staging labels, AI rules, original-photo requirements and fines at CRMLS, SDMLS, Bright MLS, Stellar MLS, NWMLS, Metro MLS, MLS Now, Unlock MLS, ARMLS, MLSListings, SFARMLS, RMLS, REcolorado, HAR MLS, MRED, NorthstarMLS, Canopy MLS, Doorify MLS, BeachesMLS, Southeast Florida MLS, OneKey MLS and MLS PIN. Every row is read from the MLS's own published rules, FAQ or support page, with the source URL and the date it was checked. |
| **Listing photo apps and services compared** | [`listing-photo-tools.csv`](data/listing-photo-tools.csv) · [`listing-photo-tools.json`](data/listing-photo-tools.json) | 58 tools | Capture apps, AI editors, human editing services, virtual staging, 3D tour and video tools for listing photos (Ovvy, Exposio, BoxBrownie, PhotoUp, Autoenhance.ai, Imagen, Virtual Staging AI, Collov AI, Matterport, October and more): who does the work, platforms, price basis, lowest published US-dollar price, the price in the vendor's words, turnaround, video, staging and labelling of altered photos. Every row is read from the vendor's own pages (two from dated captures), with the source URL and the date it was checked. |
| **Listing photo requirements by platform** | [`platform-photo-requirements.csv`](data/platform-photo-requirements.csv) · [`platform-photo-requirements.json`](data/platform-photo-requirements.json) | 11 platforms | Minimum and recommended size, file formats, file size cap, photo count, orientation, content rules and cover photo rules at Airbnb, Vrbo, Booking.com, Expedia Group, Zillow Rentals, Apartments.com, Redfin Rental Tools, Furnished Finder, Google Business Profile, Tripadvisor and Peerspace. Every row is read from the platform's own help, partner or developer pages on 17 November 2026, with the source URLs and notes where official pages disagree. |
| **Professional listing photo benchmarks** | [`listing-photo-benchmarks.json`](data/listing-photo-benchmarks.json) | 26 figures | What professional interior listing photos measure: lean of vertical lines (median 0.00° across 392 photos), focal length (median 18 mm full-frame equivalent), the brightness profile (L* percentiles), near-white share, wall colour, saturation, fine detail, styling faults and delivered size. Each figure has its sample size and method. |

Read them as pages:

- Real estate video cost: <https://www.october-ai.com/guides/real-estate-video-cost>
- Airbnb photography cost: <https://www.october-ai.com/guides/airbnb-photography-cost>
- Best virtual tour software: <https://www.october-ai.com/guides/best-virtual-tour-software>
- Cheapest real estate photo editing: <https://www.october-ai.com/guides/cheapest-real-estate-photo-editing>
- Real estate floor plan cost: <https://www.october-ai.com/guides/real-estate-floor-plan-cost>
- Best real estate video apps: <https://www.october-ai.com/guides/best-real-estate-video-apps>
- Cheapest virtual staging: <https://www.october-ai.com/guides/cheapest-virtual-staging>
- MLS photo rules: <https://www.october-ai.com/guides/mls-photo-rules-by-mls>
- Listing photo requirements by platform: <https://www.october-ai.com/guides/listing-photo-requirements-by-platform>
- Listing photo tools compared: <https://www.october-ai.com/guides/real-estate-photo-apps-compared>
- The study behind the benchmarks: <https://www.october-ai.com/guides/what-makes-listing-photos-look-professional>
- All open data, with changelog: <https://www.october-ai.com/data>
- Analysis notebook (package prices by home size, add-ons, metros): [`notebooks/real-estate-photography-prices-2026.ipynb`](https://github.com/October-ai-jpg/listing-photo-data/blob/main/notebooks/real-estate-photography-prices-2026.ipynb)
- Mirror on Kaggle: <https://www.kaggle.com/datasets/octoberai/us-real-estate-listing-photo-data>

## Fields

Each JSON file carries its own field list (`fields`), licence, attribution line, date modified and changelog, so it can be used without this README.

**mls-photo-rules:** `mls`, `region`, `rules_cited`, `photo_limit`, `photo_requirements`, `min_size`, `branding_rule`, `virtual_staging_rule`, `ai_alteration_rule`, `originals_rule`, `fines`, `source_url`, `more_source_urls`, `checked`. An empty value means the rule was not stated on the pages we read. It does not mean the MLS has no such rule.

**photographer-prices:** `metro`, `business`, `url`, `checked`, `pricing_basis`, `photos_small_usd`, `small_tier`, `photos_medium_usd`, `medium_tier`, `photos_large_usd`, `large_tier`, `photos_included`, `turnaround`, `drone_addon_usd`, `video_addon_usd`, `twilight_addon_usd`, `tour_3d_addon_usd`, `photo_only_package`, `notes`. Prices are as published (mostly "starting at") before travel fees and taxes; check `url` before relying on a row. Rows with `photo_only_package: false` bundle drone, video or 3D into the cheapest package and are left out of the medians.

**listing-photo-tools:** `name`, `url`, `category`, `who_does_the_work`, `platforms`, `price_basis`, `price_from_usd`, `price_text`, `turnaround`, `makes_video`, `virtual_staging`, `labels_altered_photos`, `source_url`, `checked`, `guide_slug`. An empty value means the vendor's pages we read did not state it. Prices change often: check `source_url` before you rely on a row.

**real-estate-video-prices:** `metro`, `business`, `url`, `checked`, `pricing_basis`, `filmed_walkthrough`, `video_standalone_usd`, `video_addon_usd`, `photos_and_video_usd`, `cinematic_video_usd`, `social_reel_usd`, `agent_on_camera_usd`, `drone_video_usd`, `video_length`, `turnaround`, `tier_note`, `notes`. Only rows with `filmed_walkthrough: true` count in the medians; slideshows, AI videos, 3D-tour fly-throughs and aerial-only videos are marked false.

**vacation-rental-photography-prices:** `market`, `business`, `url`, `checked`, `pricing_basis`, `str_package`, `photos_small_usd`, `small_tier`, `photos_large_usd`, `large_tier`, `photos_included`, `twilight_usd`, `drone_usd`, `video_usd`, `tour_3d_usd`, `lifestyle_or_staging`, `turnaround`, `notes`. Add-on prices are the cheapest listed and can be a virtual twilight edit or a photo slideshow; `notes` say which.

**real-estate-video-app-prices:** `provider`, `url`, `checked`, `type`, `free_plan`, `price_per_video_usd`, `subscription_from_usd`, `subscription_yearly_per_month_usd`, `output`, `voiceover_or_music`, `turnaround`, `platforms`, `notes`. App Store prices are quoted in `notes` where the period is not named.

**floor-plan-prices:** `provider`, `url`, `checked`, `type`, `floor_plan_from_usd`, `floor_plan_3d_usd`, `subscription_from_usd`, `free_option`, `turnaround`, `size_limit`, `input`, `measurements`, `notes`. Prices are per floor or per property as `notes` say.

**real-estate-photo-editing-prices:** `provider`, `url`, `checked`, `type`, `hdr_per_photo_usd`, `hdr_bulk_per_photo_usd`, `subscription_from_usd`, `free_trial`, `turnaround`, `item_removal_usd`, `day_to_dusk_usd`, `sky_replacement_usd`, `revisions`, `notes`. Many prices are "starting at" prices; `notes` say how each per-photo figure was reached.

**virtual-tour-software-prices:** `provider`, `url`, `checked`, `type`, `free_plan`, `cheapest_plan_usd_month`, `cheapest_plan_usd_month_yearly`, `active_tours_included`, `price_per_tour_usd`, `camera`, `floor_plan_usd`, `unbranded_mls_link`, `hosting_note`, `notes`. Where a site showed only another currency (Matterport among them), the USD fields are empty and `notes` give the amount and currency.

**virtual-staging-prices:** `provider`, `url`, `checked`, `type`, `price_per_photo_usd`, `price_per_photo_bulk_usd`, `subscription_from_usd`, `free_trial`, `turnaround`, `revisions`, `item_removal_usd`, `day_to_dusk_usd`, `labels_or_watermark`, `notes`. AI tools' per-photo figures count generations, usually on the biggest plan billed yearly; `notes` say how each was reached.

**platform-photo-requirements:** `platform`, `category`, `min_resolution`, `recommended_resolution`, `max_file_size`, `file_formats`, `min_photos`, `max_photos`, `orientation_or_aspect`, `content_rules`, `cover_photo_rule`, `source_url`, `more_source_urls`, `checked`, `notes`. An empty value means the platform's pages we read did not state it.

**listing-photo-benchmarks:** `id`, `marker`, `statistic`, `value`, `unit`, `sample_size`, `sample`, `method`, plus `section` and `as_published`, which give the study section and the figure exactly as the page prints it.

## How to cite

> Source: October, october-ai.com/data

With a DOI: October (2026). *Listing photo data: US real estate photography prices, MLS photo rules and listing photo tools* [Data set]. Zenodo. https://doi.org/10.5281/zenodo.24324406

For example: *"Across 392 professional interior listing photos, the median lean of vertical lines was 0.00° (October, october-ai.com/data)."*

## Caveats

- MLS rules change. Check the `checked` date, and confirm with the MLS before you rely on a row for a listing. This is not legal advice.
- The benchmark reference set is 392 professional interior photos from listings by Danish real estate brokerages, measured in September 2026. As a check, 120 photos from US agent listings had the same centre on all twelve markers, with a wider spread. Sample sizes differ per figure; each figure states its own sample and method.

## Updates

These files are exported from the same records that render the pages on october-ai.com, so the repo and the site always say the same thing. Corrections and new MLSs are welcome: open an issue with the MLS's own page as the source.

---

October turns a guided iPhone walk into listing photos and a walkthrough video, made from that capture and usually ready within a few hours. See <https://www.october-ai.com>.
