# RL Reliability--Cost Evaluation Materials

This repository contains the formal v3 study and its later, separately
reported extensions through the V7 new-seed validation. The primary inference
remains limited to the preregistered five-task panel and stated evaluation
budget. V7 is a post-hoc prospective validation on new seeds; it does not
establish unknown-distribution coverage, task-population generalization,
realized compute savings, or independent-team replication.

## Current release: v3.0.5

The Machine Learning submission is **Resolution and Cost in Sequential Evaluation
of Reinforcement Learning Algorithms: A Design Audit**. The current English
submission and supplement have clickable resource references. The full package
also retains historical manuscript variants; use the files named
`MANUSCRIPT_MACHINE_LEARNING_SUBMISSION_EN` and `SUPPLEMENTARY_MACHINE_LEARNING_EN`
for the current English submission, and `MANUSCRIPT_FORMAL_ZH` and
`SUPPLEMENTARY_FORMAL_ZH` for the current Chinese manuscripts.

Download the [versioned release](https://github.com/upcmill/rl-reliability-cost-frontiers/releases/tag/v3.0.5).
The archive series is identified by [10.5281/zenodo.23949004](https://doi.org/10.5281/zenodo.23949004).
The fixed GitHub release identifies this revision even when the concept DOI moves to a later version.

| Resource | Download |
|---|---|
| 1. Supplementary narrative | [PDF](https://github.com/upcmill/rl-reliability-cost-frontiers/releases/download/v3.0.5/Online_Resource_1_Supplement.pdf) |
| 2. Primary v3 evidence | [ZIP](https://github.com/upcmill/rl-reliability-cost-frontiers/releases/download/v3.0.5/Online_Resource_2_Primary_v3.zip) |
| 3. Supplementary experiments and seventh-round diagnostics | [ZIP](https://github.com/upcmill/rl-reliability-cost-frontiers/releases/download/v3.0.5/Online_Resource_3_Supplementary_Experiments.zip) |
| 4. Dependence diagnostics | [ZIP](https://github.com/upcmill/rl-reliability-cost-frontiers/releases/download/v3.0.5/Online_Resource_4_Dependence_Diagnostics.zip) |
| 5. Full code, data, manuscripts and provenance | [TAR.GZ](https://github.com/upcmill/rl-reliability-cost-frontiers/releases/download/v3.0.5/submission_bundle_v3.tar.gz) |
| 6. Different-machine Windows rerun | [ZIP](https://github.com/upcmill/rl-reliability-cost-frontiers/releases/download/v3.0.5/Online_Resource_6_External_Rerun.zip) |

The full package is at repository root; resources 1–4 and 6 are under
`online_resources/`, so the GitHub–Zenodo source snapshot includes every resource.
Release assets have the same bytes. `SHA256SUMS.txt` lists all six release payloads;
ZIP resources also contain per-member SHA-256 manifests. Extract the full package
to preserve relative paths when running scripts; the individual ZIPs are focused
views of the same evidence. The environment locks are `requirements-rl-lock.txt`
and `requirements-sequential.txt`; document generation additionally requires
python-docx and PyMuPDF.

Validation for this release: 85 unit tests passed in the recorded RL environment
with SciPy 1.15.3; Markdown/Word full-text and table parity passed; PDF links and
all archive member hashes were checked. These are packaging and repeatability
checks, not new experimental evidence. Author-related submission fields remain
pending, and this release does not claim submission acceptance.

## Contents

- `submission_bundle_v3.tar.gz`: source, manuscripts, raw data, analyses, and
  reproduction materials, including current Chinese and English Word papers,
  third-round review materials, and V7 artifacts.
- `submission_bundle_v3.tar.gz.sha256`: SHA-256 for the package.
- `PUBLIC_DEPOSITION_README.md`: scope and evidence limits.
- `CITATION_CFF_TEMPLATE.yml`: citation metadata template.

The project concept DOI is `10.5281/zenodo.23949004`. The concept DOI is stable
across versions; each published release also receives a version-specific DOI.
See the concept DOI landing page for the latest deposited version.

The V7 plan, frozen lock, raw seed-level metrics, analysis outputs, and audit
are included. The Windows AMD64 rerun is reported separately from independent
team replication. Earlier pilots and extensions are not pooled with the v3
primary estimand.

Author details not confirmed in the project records, including English
romanization, email, ORCID, contributions, funding, and competing interests,
remain placeholders and are not inferred here.
