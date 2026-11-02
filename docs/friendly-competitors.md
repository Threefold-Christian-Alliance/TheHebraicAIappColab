# Friendly competitors

Other Bible-study and Bible-tech services we watch, learn from, and may work with. Updated 2026-11-02.

| Service | What it is | Relationship |
|---|---|---|
| **ERF Bibleserver** (bibleserver.com, ERF Medien, Germany) | Free website with many Bible translations, including Bulgarian (`BGV` Верен, `CBT` Съвременен български превод). See details below. | Friendly, complementary |
| **SHEMA** | Bible-study app we track in the weekly brief. | Watch |
| **Ligonier Grow** | Bible-study product from Ligonier Ministries. | Watch |
| **Logos** | Logos Bible Software (Faithlife). Paid library and study platform for pastors and scholars. | Watch |
| **Velora** | Faith app we track in the weekly brief. | Watch |

## ERF Bibleserver: webmaster tools
Source: https://www.bibleserver.com/webmasters
- **Deep links:** `bibleserver.com/{TRL}/{ref}`, e.g. `/ESV/John3:16`. Comparison: `/ESV.KJV/John3:16`. Search: `/search/{TRL}/{term}`.
- **Parser API:** server side at `https://www.bibleserver.com/api/parser` (params `key`, `text`, `lang`, `trl`, `cssignore`), plus a client-side `parser.js`. It finds verse references in text and links them. Supports 23 languages, including `bg`.
- **WordPress plugin:** "Link to Bible".
- **No verse-text API**, for licence reasons.
- **API key:** free and tied to one domain. Daily request limits apply, so parse when text is saved.
- **Integration idea:** link the verse references in Hebraic.ai answers to Bibleserver in the user's language. Use `CBT` or `BGV` for Bulgarian users and `ESV` for English.
