# GEP: GitHub Events Preservation

GEP keeps a continuous record of GitHub's public events feed. Every hour it publishes the events it received together with a measurement of how complete that hour is.

- Documentation: https://alanhuang99.github.io/gep-archive/
- BigQuery: dataset `gep-archive.gep` (location `US`), updated hourly
- Cloud Storage: `gs://gep-archive` (Requester Pays)

Queries, downloads and other operations are billed to the user's own Google Cloud project.

This repository holds the documentation site (`docs/`). Questions, corrections and removal requests: open an issue.

GEP's documentation and its compilation of the data are released under CC BY 4.0 (`LICENSE`). The events themselves are GitHub's public data and remain subject to GitHub's terms.
