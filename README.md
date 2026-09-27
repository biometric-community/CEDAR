# CEDAR

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FCEDAR-181717?logo=github)](https://github.com/biometric-community/CEDAR)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://cedar.buffalo.edu/NIJ/data/)

**CEDAR** — tbiom catalog packaging for `cedar` (signature; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/CEDAR
- **Upstream source**: https://cedar.buffalo.edu/NIJ/data/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `cedar` |
| Category | `signature` |
| Access | `register` |
| Upstream homepage | https://cedar.buffalo.edu/NIJ/data/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: CEDAR signature dataset.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/CEDAR.git
cd CEDAR
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_cedar.sh
```

Place licensed archives under `projects/datasets/cedar/` (gitignored).

## Dataset structure

```text
CEDAR/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://cedar.buffalo.edu/NIJ/data/
- Packaging: https://github.com/biometric-community/CEDAR/issues
