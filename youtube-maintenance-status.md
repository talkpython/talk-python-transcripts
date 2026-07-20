# Talk Python YouTube Maintenance Status

This is the living tracker for Talk Python episode metadata and transcript maintenance. Update it after each episode is processed or a replacement transcript is added.

## Episodes 440–449 work log

- [x] 440 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 441 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 442 — title updated; description updated; no managed transcript; existing captions unchanged; verified
- [ ] 443 — blocked: authoritative description contains forbidden `<` and `>` characters; no YouTube writes
- [ ] 444 — replacement needed: `444-young-success-blueprint.vtt` cue 1125 has a non-positive duration
- [ ] 445 — no mapped YouTube video
- [ ] 446 — no mapped YouTube video
- [x] 447 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 448 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 449 — title updated; description updated; existing manual English subtitles preserved; verified; later no-op observer reconciled

## Episodes 450–459 work log

- [x] 450 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 451 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 452 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 453 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 454 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 455 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 456 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 457 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 458 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 459 — title updated; description updated; existing manual English subtitles preserved; verified

## Episodes 460–480 work log

- [x] 460 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 461 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 462 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 463 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 464 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 465 — title unchanged; description updated; existing manual English subtitles preserved; verified
- [x] 466 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 467 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 468 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 469 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 470 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 471 — title updated; description updated; existing manual English subtitles preserved; verified
- [ ] 472 — blocked: authoritative podcast description contains a forbidden `<` character; no YouTube writes
- [ ] 473 — replacement needed: `473-adhd-devs.vtt` cue 809 has a non-positive duration
- [x] 474 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 475 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 476 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 477 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 478 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 479 — title updated; description updated; existing manual English subtitles preserved; verified
- [x] 480 — title and description updated; existing manual English subtitles preserved; verified

## Completed and verified

- [x] Episodes 440–449 processed where valid
  - Completed and verified: 440–442, 447–449
  - Titles and descriptions updated: all 6 completed episodes
  - Existing manual English subtitles preserved: 440–441, 447–449
  - Metadata-only because no managed transcript exists: 442
  - Blocked or unmapped: 443–446

- [x] Episodes 450–459 fully processed
  - Titles updated: 450–459
  - Descriptions updated: 450–459
  - Existing manual English subtitles preserved for all 10 episodes
  - No blocked episodes

- [x] Episodes 460–480 processed where valid
  - Completed and verified: 460–471, 474–480
  - Titles updated: 460–464, 466–471, 474–480
  - Descriptions updated: all 19 completed episodes
  - Existing manual English subtitles preserved for all 19 completed episodes
  - Blocked: 472 canonical description and 473 malformed transcript

- [x] Episodes 520–529 fully processed
  - Title updated: 521
  - Descriptions updated: 520–526
  - Already matched: 527–529

- [x] Episodes 500–519 processed where valid
  - Descriptions updated: 501–503, 505, 507–519
  - Titles already matched for all 17 completed episodes
  - Episode 503’s earlier update was verified after the API quota reset

- [x] Episodes 480–499 processed where valid
  - Titles and descriptions updated: 480, 484, 485
  - Description updated, title already matched: 489

- [x] All completed changes passed YouTube API readback and idempotency verification
- [x] All direct writes were correlated with yta’s operation log and backup files
- [x] Existing manual English subtitles were preserved
- [x] No autogenerated subtitle tracks or unmanaged metadata were modified
- [x] No subtitle uploads were required
- [x] No existing YouTube chapter blocks needed preservation

## Missing managed transcripts

- [ ] Episode 442 needs a raw-recording YouTube VTT; metadata is complete and existing captions were left unchanged

## Replacement transcripts needed

Each file below has a cue with a non-positive duration:

- [ ] `444-young-success-blueprint.vtt` — cue 1125
- [ ] `473-adhd-devs.vtt` — cue 809
- [ ] `481-python-opinions-and-zeitgeist-with-hynek.vtt` — cue 2806
- [ ] `482-pre-commit-hooks-for-python-devs.vtt` — cue 665
- [ ] `483-reflex-framework-frontend-backend-pure-python.vtt` — cue 961
- [ ] `486-csnakes-embed-python-code-in-.net.vtt` — cue 593
- [ ] `487-building-rust-extensions-for-python.vtt` — cue 322
- [ ] `488-lancedb.vtt` — cue 114
- [ ] `491-duckdb-and-python-ducks-and-snakes-living-together.vtt` — cue 66
- [ ] `492-great-tables.vtt` — cue 266
- [ ] `493-quarto.vtt` — cue 585
- [ ] `494-update-on-flet-python-flutter-uis.vtt` — cue 171
- [ ] `498-high-performance-terminal-apps.vtt` — cue 117
- [ ] `499-beeware-and-the-state-of-python-on-mobile.vtt` — cue 682
- [ ] `500-django-simple-deploy-and-other-devops things.vtt` — cue 203
- [ ] `504-developer-trends.vtt` — cue 619
- [ ] `506-ty-aka-red-knot-type-checker.vtt` — cue 761

## Transcript choice or cleanup needed

- [ ] Episode 495 has two candidates:
  - `495-osmnx-python-and-openstreetmap-yt.vtt`
  - `495-osmnx-python-and-openstreetmap.vtt`

- [ ] Episode 496 has two candidates:
  - `496-scaf-deploys-yt.vtt`
  - `496-scaf-deploys.vtt`

## Canonical metadata help needed

- [ ] Episode 443 authoritative description contains literal `<` and `>` characters rejected by YouTube
- [ ] Episode 472 authoritative description contains a literal `<` character rejected by YouTube

## YouTube mapping help needed

- [ ] Episode 445 has no mapped YouTube video
- [ ] Episode 446 has no mapped YouTube video
- [ ] Episode 490 has no mapped YouTube video
- [ ] Episode 497 has no mapped YouTube video

## Next steps

- [ ] Replace the malformed transcripts and resolve episodes 495/496
- [ ] Create a managed raw-recording VTT for episode 442
- [ ] Remove or rewrite forbidden angle brackets in episodes 443 and 472 authoritative descriptions
- [ ] Confirm or add YouTube mappings for episodes 445, 446, 490, and 497
- [ ] Rerun blocked episodes to update metadata and verify subtitle state
