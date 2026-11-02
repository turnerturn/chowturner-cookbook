# Gluten-Free Cooklang Collection

48 one-serving recipes converted from the attached Markdown, with three editable example menus.

## Start

Install CookCLI, open a terminal in this directory, then run:

```bash
cook doctor validate
cook recipe recipes/tom-kha-gai-soup.cook
cook recipe plans/sample-week-one.menu
cook shopping-list plans/sample-week-for-two.menu
cook server
```

Recipe metadata declares one serving. Menus use explicit `%servings` references relative to this directory. Ingredient tokens appear once in an initial gathering step so generic editorial instructions do not duplicate shopping quantities. Optional ingredients use `@?` and may require opting in within your app.

## Review before use

Read `docs/conversion-review.md`. This is a converted notes archive, not a collection of verified cooking instructions. Recipe-specific editorial steps were supplied where the listed ingredients made the method clear; other source outlines were retained. No exact cooking times were invented. Missing main ingredients are unquantified and flagged; missing amounts were not invented. These omissions make shopping lists incomplete until reviewed.

Repeated divisions such as `1/5 /4` become `1/20`. Mixed numbers become exact fractions. Leading quantities are already per serving and were not rescaled again. Parenthetical weights and package descriptions are not added as separate ingredients. Range upper bounds are selected and recorded. Alternatives remain descriptive ingredient names unless a clear GF substitution was needed. Combined alternatives may require manual shopping-list consolidation. No original-source ratings were invented or copied to recipe metadata.

Public image URLs are retained as links; placeholders are omitted. Images were not downloaded. Source and comparable links are distinct. The original uploaded Markdown is preserved unchanged in `source/`.

All recipes carry `needs-review`. Keep the archive private until you review completeness, permissions, and recipe quality. No pantry inventory or publication registration has been invented.

Official specifications: https://cooklang.org/docs/spec/ and https://cooklang.org/docs/conventions/
