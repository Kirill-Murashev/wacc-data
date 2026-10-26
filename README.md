# WACC research data

Data accompanying a series of research papers on the cost of capital (WACC) and its components — the equity risk premium, the risk-free rate, country risk and industry betas — across national equity markets.

**Status:** the repository structure is in place; datasets will be added as each paper is prepared for publication.

## Layout

```
articles/
  01-wacc-usa/        Paper 1 — long-run equity risk premia: is the US market unique? (33 markets, 2001–2025)
  02-wacc-markets/    Paper 2 — which market to use for which WACC component
common/               reference data shared across papers (market lists, classifications, FX, etc.)
```

Each folder has the same two subfolders:

| Folder | Contents |
|---|---|
| `data/` | datasets used in the paper's calculations, in open formats (CSV, JSON) |
| `metadata/` | provenance: source, URL, retrieval date, checksums, processing notes |

A paper folder may also have `appendices/`: the paper's electronic appendices (PDF and Word), linked from the paper's text.

## Principles

- **Open sources only.** Every dataset is traceable to a publicly available source recorded in `metadata/`.
- **Provenance and integrity.** Each file is listed with its source URL, retrieval date (UTC) and checksum.
- **Third-party terms respected.** Where a provider's terms of use do not permit redistribution (e.g. vendor price series), only derived series needed to reproduce the published results are included, not the raw data. The source and how to obtain it are documented.
- **No interpretation in the data.** Methods and conclusions are in the papers and their electronic appendices (`appendices/`); `data/` and `metadata/` hold data and its documentation only.

## Papers

| # | Working title | Folder |
|---|---|---|
| 1 | Long-run equity risk premia: is the US market unique? Evidence from 33 markets, 2001–2025 | [`articles/01-wacc-usa`](articles/01-wacc-usa) |
| 2 | Which market for which WACC component | [`articles/02-wacc-markets`](articles/02-wacc-markets) |

Titles are provisional and will be updated upon publication.

## License

To be determined. Until a license is added, please contact the author before reusing the data.

## Contact

Kirill Murashev — kirill.murashev@gmail.com
