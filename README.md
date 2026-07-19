# media

Media assets — rendered videos, audio, images, transcripts, text sources, and presentations.

## Repository structure

| Folder | Contents | Index |
|---|---|---|
| [`text/`](text/) | Research briefs + narration scripts | [text/README.md](text/README.md) |
| [`transcripts/`](transcripts/) | Verbatim spoken transcripts of videos | [transcripts/README.md](transcripts/README.md) |
| [`audio/`](audio/) | Standalone TTS narration (`.mp3`) | [audio/README.md](audio/README.md) |
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
- Suffixes by folder: `_narration` / `_transcript` (text), `_thumb` / `_chart` / `_poster` (images).
- Presentations are one folder per deck (narration + chart spec + slides).

Each folder's `README.md` carries an index table of its contents.

---

## Featured: All of Us — Professor Briefing

A professor-narrated video on the NIH *All of Us Research Program* (purpose & 2026 status). Charts and timeline generated from hard stats: **747,000+ participants**, world's largest integrated genomics + health database.

▶️ **[Click here to play / download the video](https://github.com/comdevopsai/media/releases/download/v1.0/all_of_us_professor.mp4)** (opens the MP4 in your browser's player).

[![Watch the video](images/2026-07-19_all-of-us-professor-briefing_thumb.png)](https://github.com/comdevopsai/media/releases/download/v1.0/all_of_us_professor.mp4)

### Asset set (same `2026-07-19_all-of-us-professor-briefing` slug)
- **Video:** [`videos/2026-07-19_all-of-us-professor-briefing.mp4`](videos/2026-07-19_all-of-us-professor-briefing.mp4) — also on [release v1.0](https://github.com/comdevopsai/media/releases/tag/v1.0) (direct `video/mp4` play link).
- **Audio:** [`audio/2026-07-19_all-of-us-professor-briefing.mp3`](audio/2026-07-19_all-of-us-professor-briefing.mp3) — standalone TTS narration.
- **Transcript:** [`transcripts/2026-07-19_all-of-us-professor-briefing_transcript.txt`](transcripts/2026-07-19_all-of-us-professor-briefing_transcript.txt)
- **Narration script:** [`text/2026-07-19_all-of-us-professor-briefing_narration.md`](text/2026-07-19_all-of-us-professor-briefing_narration.md)
- **Source brief:** [`text/2026-07-19_all-of-us-research-program.md`](text/2026-07-19_all-of-us-research-program.md)
- **Thumbnail:** [`images/2026-07-19_all-of-us-professor-briefing_thumb.png`](images/2026-07-19_all-of-us-professor-briefing_thumb.png)
