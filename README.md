# farm_media_manifests

Machine-generated JSON manifests indexing **farm media** — YouTube videos (via `yt_id`) + plot/coverage metadata — for TrueSight DAO farms.

**Data repo** — daemon/automation-owned writes via the Contents API (never cloned / branch-edited; same pattern as `farm-media-raw`).

## Layout
- `<farm_id>.json` — per-farm manifest: `farm_id`, `plots`, `gps_coverage`, `items[]` (each = video with `yt_id` → watch URL)
- `index.json` — directory across all farms

## Related
- Raw media (HEIC/JPG photos): [`farm-media-raw`](https://github.com/TrueSightDAO/farm-media-raw)
- Upload daemon: [`farm-media-daemon`](https://github.com/TrueSightDAO/farm-media-daemon)

_Moved from `agentic_ai_context/FARM_MEDIA_MANIFESTS/` (2026-09-01) — see that repo for history._
