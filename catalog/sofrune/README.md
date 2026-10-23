# Sofrune open recipe catalogue

Recipe text adaptations and translations: © Wikibooks Cookbook contributors and basilbase, CC BY-SA 4.0. https://creativecommons.org/licenses/by-sa/4.0/

v1.json is the public downloadable catalogue (schema 1). Sources and exact upstream revision text are in sources.json. Each recipe includes its original revision, contributor history, licence and changes/weight assumptions in all nine supported languages. Source title is present in the linked original revision and sources.json. No photos are copied. This content licence does not license the separate application code. USDA SR Legacy 2018 nutrient facts: CC0, https://fdc.nal.usda.gov/.

This first edition has eight adaptations from four source recipes and four additional foods. Nutrition estimates use ingredient weights, not measured finished meals. Water is included separately; cooking losses are not modelled. Editorial gram conversions, ingredient substitutions and omissions are disclosed per recipe. Read source and product labels for individual dietary requirements.

Publishing: run scripts/build_online_catalog.py locally in the Sofrune app repository. Review ingredient state, quantities, allergens, nutrition mapping, licences and nine-language copy before publishing. An existing record is immutable: assign a new id for edits and increment the edition revision. The Android app rejects conflicting records and retains previous editions locally for existing plans. Copy v1.json and sources.json here and publish this static site. No Android or recipe build runs in GitHub Actions. No per-user queries, accounts or personal food records exist on this service.
