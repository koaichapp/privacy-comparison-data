# Encrypted Workspace & Messaging — Privacy Comparison Data

An **open dataset** comparing encrypted-workspace and secure-messaging vendors across privacy-architecture attributes: end-to-end encryption surface, key custody, metadata posture, recovery model, and more.

**10 vendors × 16 attributes.** Compiled from public vendor documentation.

- 📊 **Human-readable matrix:** https://koaich.com/compare/matrix-2026
- 🔌 **Live JSON endpoint:** https://koaich.com/data/competitor-matrix.json
- 📚 **Methodology + 49 source URLs:** https://koaich.com/methodology

## Files

| File | What |
|---|---|
| [`competitor-matrix.json`](./competitor-matrix.json) | Full structured dataset — values **and** a privacy-favorability flag per cell, plus vendor metadata. |
| [`competitor-matrix.csv`](./competitor-matrix.csv) | Flat values matrix (one row per attribute, one column per vendor) — drops straight into a spreadsheet. |

## Vendors covered

Slack · Notion · Google Workspace · Microsoft Teams · Discord · Signal · SMS · Facebook Messenger · LinkedIn · WhatsApp — compared against Koaich.

## Attributes

End-to-end encryption (messages / documents / files), key custody, who can read content, metadata exposure, recovery model, group-encryption protocol, distribution model, and more. See the JSON `attributes[].attribute` list or the CSV header for the full set.

## License — CC-BY 4.0 (reuse freely, with attribution)

This dataset is licensed under [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/). You may share and adapt it for any purpose, including commercially, **provided you give attribution**:

> Source: Koaich encrypted-workspace & messaging comparison matrix — https://koaich.com/compare/matrix-2026 — licensed CC-BY 4.0.

## A note on neutrality

This dataset is published by [Koaich](https://koaich.com), which is itself one of the compared products. The `favorable` flags in the JSON reflect a **privacy-architecture lens** (does a vendor's posture on an attribute favor the user's privacy?). The raw `value` fields are factual statements drawn from public documentation — check them against the [methodology sources](https://koaich.com/methodology), and **if a cell is wrong, [open an issue](https://github.com/koaichapp/privacy-comparison-data/issues)** or email hello@koaich.com. Corrections update the canonical source and propagate here.

## Citing

```
Koaich. "Encrypted Workspace & Messaging Comparison Matrix (2026)."
koaich.com, https://koaich.com/compare/matrix-2026. Licensed CC-BY 4.0.
```
