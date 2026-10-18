# Researchurgy · The Engineering of Research

> Term Registration Claim · Registered: 2026-10-15
> System: Lifecycle Governance Doctrine (LGD) · LGD Meta-Layer Creation Family (-urgy)

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache--2.0-yellow.svg)](LICENSE)
[![DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.23385209-0078d4.svg)](https://doi.org/10.5281/zenodo.23385209)

**Researchurgy** is the engineering of research as a reproducible method rather than ad-hoc effort. It registers the term and the method spine so that the ceiling of research output quality equals the quality of the research method itself.

The method spine: **problem definition → hypothesis → channels → evidence grading → cross-validation → synthesis → replication → meta-review.**

## When to use

Use when performing reproducible research or investigation: evidence grading, cross-validation, replication.

## Definition

Researchurgy turns one-off investigation into an engineering method: every step produces a record that can be reviewed, re-run, and cross-checked. Evidence is graded by source tier, conclusions are triangulated across at least two independent channels, and a final meta-review audits the method itself.

## Verification

Multi-round full-dimension prior-art search: zero conflicts (R1+R2, 2026-10-14).

## Quick Start

```bash
git clone https://github.com/zhaoxinghua09-cell/researchurgy.git
cd researchurgy
# read machine-readable metadata (YAML frontmatter, lines 1-12)
sed -n '1,12p' README.md
```

## Examples

Apply the spine as a checklist:

```markdown
- [ ] Problem definition: what this does and does not answer
- [ ] Hypothesis: a claim written so evidence can falsify it
- [ ] Channels: at least two independent information channels
- [ ] Evidence grading: tier each item (primary / secondary / hearsay)
- [ ] Cross-validation: do two channels converge on the same conclusion
- [ ] Synthesis: state the conclusion and mark uncertainties
- [ ] Replication: could someone else re-run this and reach it
- [ ] Meta-review: where the method itself failed
```

## Repository layout

```text
researchurgy/
├── README.md / README.en.md   # bilingual term-registration document
├── llms.txt / llms-full.txt   # machine-readable index for AI agents
├── AGENTS.md                  # guidance for AI coding agents
├── SECURITY.md                # security policy
├── CONTRIBUTING.md            # errata / contribution guide
├── CITATION.cff               # citation metadata
├── codemeta.json              # schema.org software metadata
└── LICENSE                    # Apache-2.0 (covers future code examples)
```

## Rights / License

The root [LICENSE](LICENSE) is **Apache-2.0** and covers future code examples and tooling. Per the repository's rights statement, the theory / term text claims **ARR (All Rights Reserved)** with attribution-based citation and linking permitted. Cite via `CITATION.cff` and DOI `10.5281/zenodo.23385209`. Contact: zhaoxinghua09@gmail.com ｜ ORCID `0009-0001-0512-1237`.

## Links

- GitHub: https://github.com/zhaoxinghua09-cell/researchurgy
- DOI: https://doi.org/10.5281/zenodo.23385209
- Registry index: https://github.com/zhaoxinghua09-cell/placeholdurgy

## Disclaimer

This repository is a term-registration and methodology exploration. It is not a claim of certification or commercial delivery. External standards and literature are paraphrased from public sources; verify independently before formal citation.
