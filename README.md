# Zeitdex resources

The community-maintained **data** behind the [Zeitdex](https://zeitdex.github.io/) specialist and software directories. A fork of [sleepdiary/resources](https://github.com/sleepdiary/resources).

## Entities

`entities.json` is compiled from individual JSON files and drives the [specialist directory](https://zeitdex.github.io/find-a-specialist/) and [software directory](https://zeitdex.github.io/create/software/) on the Zeitdex site.

- [Get the JSON file](entities.json) (built on the `built` branch)
- [Raw specialist data](https://github.com/zeitdex/resources/blob/main/entities/specialist)
- [Raw software data](https://github.com/zeitdex/resources/blob/main/entities/software)

To add an entry, use the issue templates or add a JSON file — the directories regenerate on the next Zeitdex build.

### See also

- [The Consensus Sleep Diary](https://academic.oup.com/sleep/article/35/2/287/2558899) — a questionnaire-style diary based on work by many researchers
- [The Circadian Sleep Disorders Network's list of doctors](https://www.circadiansleepdisorders.org/doctors.php) — includes many specialists who do not yet have an entry here

## Project map

Zeitlog (the tracker) and Zeitdex (docs & resources) for circadian rhythm disorders span a few repos across two GitHub orgs and one account:

**Zeitlog — tracker** · [@zeitlog](https://github.com/zeitlog) · <https://zeitlog.github.io/>

| Repo | Role |
|---|---|
| [zeitlog.github.io](https://github.com/zeitlog/zeitlog.github.io) | The tracker web app |
| [core](https://github.com/zeitlog/core) | Sleep-diary format engines (parsing) |
| [report](https://github.com/zeitlog/report) | Sleep-doctor report bundle |
| [info](https://github.com/zeitlog/info) | Analysis & charts bundle |

**Zeitdex — docs & resources** · [@zeitdex](https://github.com/zeitdex) · <https://zeitdex.github.io/>

| Repo | Role |
|---|---|
| [zeitdex.github.io](https://github.com/zeitdex/zeitdex.github.io) | Docs & resources site (MkDocs) |
| [docs](https://github.com/zeitdex/docs) | Documentation source |
| [resources](https://github.com/zeitdex/resources) | Specialist & software directory data |

**Pre-production** · [@wellivea1](https://github.com/wellivea1)

| Repo | Role |
|---|---|
| [dashboard-vibecode](https://github.com/wellivea1/dashboard-vibecode) | Pre-prod tracker · <https://wellivea1.github.io/dashboard-vibecode/> |
| [core-vibecode](https://github.com/wellivea1/core-vibecode) | Pre-prod core |

Forked from the [Sleep Diary Project](https://github.com/sleepdiary).
