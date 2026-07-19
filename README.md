# media

Media assets — rendered videos, images, and presentations.

## Repository structure

| Folder | Contents | Index |
|---|---|---|
| [`videos/`](videos/) | Rendered video files (`.mp4`) | [videos/README.md](videos/README.md) |
| [`images/`](images/) | Images, poster frames, thumbnails, charts | [images/README.md](images/README.md) |
| [`presentations/`](presentations/) | Slide decks & presentation sources | [presentations/README.md](presentations/README.md) |

## Naming convention

All assets use a date-prefixed, kebab-case slug so they sort chronologically and read clearly:

```
YYYY-MM-DD_topic-in-kebab-case[.ext | /]
```

- **`YYYY-MM-DD`** — creation/render date (ISO 8601).
- **`topic-in-kebab-case`** — short descriptive slug, lowercase, hyphen-separated.
- Images may add a role suffix: `_thumb`, `_chart`, `_poster`.
- Presentations are one folder per deck (narration + chart spec + slides).

Each folder's `README.md` carries an index table of its contents.

---

## Featured: All of Us — Professor Briefing

A professor-narrated video on the NIH *All of Us Research Program* (purpose & 2026 status). Charts and timeline generated from hard stats: **747,000+ participants**, world's largest integrated genomics + health database.

▶️ **[Click here to play / download the video](https://github.com/comdevopsai/media/releases/download/v1.0/all_of_us_professor.mp4)** (opens the MP4 in your browser's player).

[![Watch the video](images/2026-07-19_all-of-us-professor-briefing_thumb.png)](https://github.com/comdevopsai/media/releases/download/v1.0/all_of_us_professor.mp4)

- Video file: [`videos/2026-07-19_all-of-us-professor-briefing.mp4`](videos/2026-07-19_all-of-us-professor-briefing.mp4) — also on [release v1.0](https://github.com/comdevopsai/media/releases/tag/v1.0) (direct `video/mp4` play link).
- Thumbnail: [`images/2026-07-19_all-of-us-professor-briefing_thumb.png`](images/2026-07-19_all-of-us-professor-briefing_thumb.png)
