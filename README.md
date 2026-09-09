# lilka-catalog-e2e

Lilka catalog end-to-end test packages; synthetic fixtures only.

This repository retains the resource payloads used for the September 9, 2026 lifecycle validation. The Lilka catalog contains only metadata and immutable references; resource prompts, skill files, plugin files and tool definitions live here.

Validated package types: agent, agency, skill, theme, icon theme, native plugin, tool and tool pack. Theme version 1.0.1 also exercises publication and installation updates.

Catalog registration PRs: [8](https://github.com/Lilka-Tech/lilka-marketplace/pull/8), [9](https://github.com/Lilka-Tech/lilka-marketplace/pull/9), [11](https://github.com/Lilka-Tech/lilka-marketplace/pull/11), [17](https://github.com/Lilka-Tech/lilka-marketplace/pull/17), [18](https://github.com/Lilka-Tech/lilka-marketplace/pull/18), [19](https://github.com/Lilka-Tech/lilka-marketplace/pull/19), [20](https://github.com/Lilka-Tech/lilka-marketplace/pull/20), [21](https://github.com/Lilka-Tech/lilka-marketplace/pull/21), [22](https://github.com/Lilka-Tech/lilka-marketplace/pull/22).

After validation, synthetic catalog entries are removed through a normal cleanup PR. The immutable payload history and merged PRs remain available for audit. These fixtures are not recommended production packages and contain no credentials.
