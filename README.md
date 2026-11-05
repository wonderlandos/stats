# Stats

CPU and memory in the menu bar, a desktop card, and a Top shortcut: the WolOS reference plugin (ADR 0031).

Listed on WolOS Hub as `wonderlandos.stats`: https://hub.wolos.org (published by wonderlandos).

The source of truth is `plugins/shell/org.wolos.stats` in [wonderlandos/wolos](https://github.com/wonderlandos/wolos); this repository is that folder with its history
(`git subtree split`), plus `hub/` and `.github/workflows/hub-release.yml`, which turn a pushed tag into the release the hub
checks and lists. Tags: `v<plugin.toml version>` (e.g. `v1.0`); the release packs the folder with the id `wonderlandos.stats`.
Here `plugin.toml` says `id = "wonderlandos.stats"` (the hub refuses ids under `org.wolos.` from a publisher, and its
organisation connect reads this file); the copy that ships inside WolOS keeps `org.wolos.stats`.

Licence: GPL-2.0-or-later.
