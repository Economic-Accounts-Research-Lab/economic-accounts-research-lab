# EARL — Economic Accounts Research Lab

Economic Accounts Research Lab (EARL) constructs business-style economic accounts from
U.S. economic data, with an emphasis on transparent definitions, provenance,
harmonization, and reproducible public data.

This repository is the public data and publication repository for EARL.

## Public data package

The canonical public data package is under `data/public/`. It contains 18 CSV
files covering National Income Statements, Corporate Income Statements, and
Industry Income Statements at annual and quarterly frequencies, together with
their metadata, statement layouts, source vintages, entity metadata, public
schema, and build metadata.

The files in `data/public/` are the canonical public data artifacts. Provenance
and vintage information should be read together with the corresponding
metadata files.

## Repository and website

- Repository: https://github.com/AguilarMike/economic-accounts-research-lab
- Canonical website: https://aguilarmike.github.io/economic-accounts-research-lab

The website, Statistical Releases, Technical Notes, and any public source code
are governed by separate publication gates and are added only after their
respective approval and validation procedures are complete.

## Data license

EARL-created rights in the material under `data/public/**` are made available
under the Creative Commons Attribution 4.0 International license
(CC BY 4.0), to the extent EARL holds the relevant copyright or similar rights.

The license does not assert or create rights in facts, public-domain material,
third-party material, or other elements for which EARL does not hold rights.
Underlying source materials retain their applicable legal status and terms.

See [`LICENSE-DATA.md`](LICENSE-DATA.md) for the scoped licensing notice.

## Citation

Please cite the public EARL data package as:

> Economic Accounts Research Lab (EARL). (2026). *Economic Accounts Research Lab* [Data set]. https://github.com/AguilarMike/economic-accounts-research-lab

Machine-readable citation metadata are provided in [`CITATION.cff`](CITATION.cff).

## Provenance

The public export is produced through a fail-closed allowlist from EARL's
private development repository. Private Git history, credentials, internal QA
records, prototypes, and unapproved publication payloads are not part of the
public repository.
