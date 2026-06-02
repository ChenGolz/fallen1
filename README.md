# NEON_HEARTBEAT_DESIGN_SAME_FUNCTIONALITY_V1

This version keeps the attached neon heartbeat visual design, while using the latest functionality/data from the final art-deco version:

- latest 85-person dataset
- family-group data and group photos
- focus mode: dim unrelated people and illuminate direct family/connected people
- full story modal with relatives section and candles
- search / next / previous / pause
- mobile 3+3 responsive layout, enlarged for readability
- local `START_SITE.bat` launcher


V3 custom appearance order applied.


V4 synced final:
- Same content/data/order/functionality as the matching version.
- Removed story filter UI.
- Mobile search is between poem and people cards; controls are at the bottom.
- Mobile portrait grid spacing fixed to avoid overlapping cards/names.
- Images folder omitted by request.


V5 mobile polish:
- Search stays between poem and portraits but no longer overlaps portraits.
- Portrait rows have more vertical breathing room.
- Portrait/text scale refined for mobile readability.
- Poem decorative badge no longer covers first line.
- Images folder omitted by request.


V6 mobile rechecked:
- Better mobile vertical composition.
- Search no longer touches top portraits.
- More spacing between top-row labels and lower-row portraits.
- Portrait size tuned for 320px and larger phones.
- Modal/story mobile protection improved.


Excel summaries update:
- Integrated 85 not-too-short summaries from the uploaded Excel-derived summary JSON.
- Matched every person to their Excel row and wrote summary_match_report.csv.
- Updated data.json and data.js.
- Added cache-busting query strings in index.html.
- images/ folder omitted.


Long Excel summaries + relatives update:
- Rebuilt storySummary/storySummaryClean from the full Excel row content, with longer descriptions.
- Updated first-degree family fields and relativesLines.
- Added excel_long_summaries_and_relatives_report.csv for checking each row match.
- Added cache busting version long-excel-relatives-v4.
- images/ folder omitted.


V11 polish: cleaned generic attack boilerplate from summaries and fixed several relation/summary edge cases.
