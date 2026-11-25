# HSMJ Public Releases

Each product has **its own folder**. Do not mix app files at the repo root.

## Apps

| Folder | Product | Tag prefix |
|--------|---------|------------|
| `bab-erp/` | Bab ERP | `bab-v*` |
| `souq-al-agha/` | Souq Al Agha | `souq-v*` |
| `bab-al-agha-hr/` | باب الاغا HR (privacy page only; Android is Play Store only) | - |

## Rules

1. Every new program gets a dedicated folder: `{app-id}/`
2. Put that app's `version.json` (and optional README) only inside its folder
3. GitHub **Releases/tags** stay separate per product via tag prefixes
4. Never upload another app's installer into the wrong product release

## Souq Al Agha notes

- Windows builds are published to Releases with tags `souq-vX.Y`
- Android is **Play Store only** and is never uploaded here