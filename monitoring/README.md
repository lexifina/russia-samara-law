<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Samara Oblast only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-26 05:58 UTC, Samara Oblast: Official Internet Portal of Legal Information (region63): 12 addresses read; 3 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Samara Oblast: Official Internet Portal of Legal Information (region63)](http://publication.pravo.gov.ru/documents/block/region63) | `zakony-<year>/` | daily | 2026-11-26 05:58 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-26 05:57](checks/2026-11.md#ru-pravo-samara-20261126t055730z) | pravo-samara | 12 | 3 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-samara-law/compare/2833a77b65d6...82c36c8643cf) |
| [2026-11-25 06:32](checks/2026-11.md#ru-pravo-samara-20261125t063249z) | pravo-samara | 12 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 14:46](checks/2026-11.md#ru-pravo-samara-20261124t144629z) | pravo-samara | 12 | 9 | 0 | 0 | 0 (0) | changes found | [4](https://github.com/lexifina/russia-samara-law/compare/00d12865c74b...3f8eab4f82ef) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
