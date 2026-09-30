# kp-remember · Capture It

> **KP Pure Tools**: runs standalone — not part of the Knowledge Palace mounted system.
> Member ① of the lightweight **“X yixia”** skill family — save text, schedules and files as-is, zero AI processing.
> Version 1.0 · 2026-09-30 · Author: 王亚宁 (kp-wyn)

## Family Navigation

| Command | Skill | Status | What it does |
| --- | --- | --- | --- |
| 记一下 (Capture) | kp-remember | Released (this skill) | Stores content as-is, zero processing |
| 收拾一下 (Tidy up) | kp-tidy-up | Released | Batch-organizes a backlog of old notes |
| 消化一下 (Digest) | kp-digest | Mounted version ready; standalone coming soon | Distills fresh fragments on the spot |
| 理一下 (Sum up) | kp-sum-up | Released | Turns records into a summary and plan |

## Features

- **Capture-only**: once triggered it only archives — no reply, summary, polish or rewrite; a one-line receipt when done;
- **Four-level folders**: `KP-ST-library/project/year/month`, filed by time;
- **No hardcoded path**: set a root on first use; otherwise it creates `KP-ST-library` in the working directory;
- **Standalone**: no Knowledge Palace needed.

## Quick Start

Just say “remember this: ...” and it is saved as-is to your designated folder. No summarizing, no rewriting, no processing — pure storage.

## Installation

1. On the repo page click **Code → Download ZIP**;
2. Unzip; copy the skill folder (drop any `-main` suffix, name it `kp-remember`) into your AI’s `.user_skills/` directory;
3. Restart your AI — it is ready to use.

## Storage Structure

```
KP-ST-library/
└── Project Name/
    └── 2026/
        └── 09/
            ├── record_0730_20260920.txt      # text record
            ├── record_0730_20260920_2.txt    # 2nd in the same minute
            └── attachment.pdf                 # attachment kept as-is
```

- Text records: `record_HHMM_YYYYMMDD.txt`; add `_2` / `_3` within the same minute;
- Attachments keep the original name; a date suffix is added on a clash.

## Daily Reminder (7:33 AM)

> Remember to capture key information, schedules, and work plans.
> First-time setup: please designate a dedicated folder for your records.
> Crafted by 王亚宁 (kp-wyn), MIT License.

## Notes

- A **KP Pure Tool** — not part of the Knowledge Palace mounted system;
- kp-remember only stores, never processes or comments on content;
- Local read/write; no network, no API key.

## Relation to the Knowledge Palace

Capture is the very front of the information chain. With Knowledge Palace KP-4+1 you can classify, distill, review and ship outputs.

- Knowledge Palace KP-4+1 white paper and full methodology: <https://github.com/kp-wyn/knowledge-palace>

## License

MIT License — Author: 王亚宁 (kp-wyn). See [LICENSE](LICENSE).
