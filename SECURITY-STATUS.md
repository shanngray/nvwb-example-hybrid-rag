# SECURITY STATUS: INACTIVE (classified 2026-11-09)

On 2026-11-09, Shannon Gray classified this repository as **inactive** for his own work. This is Shannon Gray's classification of his own use of the project. It is not an independent assessment of whether the code is maintained.

It **has known, unfixed security vulnerabilities** in its dependencies. The dated inventory in store `inventory/parked-findings.json` and `findings.json` (generated 2026-11-09T07:12:20+11:00; sources OSV, GitHub Advisory Database via OSV, CISA KEV) recorded 152 open advisories against this repository's default branch: 11 critical, 76 high, 44 medium, 4 low, 17 unknown.

Most serious (up to 5):
- GitPython 3.1.41 (PyPI): GHSA-284h-m62q-gf8w / CVE-2026-78676, severity critical; fixed in 3.1.59
- GitPython 3.1.41 (PyPI): PYSEC-2026-2161 / CVE-2026-42284, severity critical; fixed in 3.1.47
- gradio 4.15.0 (PyPI): PYSEC-2024-215 / CVE-2024-47167, severity critical; fixed in 5.0.0
- gradio 4.15.0 (PyPI): PYSEC-2024-274 / CVE-2024-39236, severity critical; fixed in no fix listed
- sentence_transformers 2.7.0 (PyPI): GHSA-jhr6-gm9c-rqjv / CVE-2026-68770, severity critical; fixed in no fix listed

## Retained findings
Known findings for this repository are kept on record (Sentry's parked-findings list) and are not deleted while it is inactive.

## Before work resumes
1. Review the recorded findings and re-scan for newer advisories.
2. Remediate: update affected dependencies to fixed versions.
3. Test the project after the updates.
4. Then update or remove this file.

## Alerts while inactive
While this repository is inactive, Shannon gets a security alert only for **confirmed active exploitation**: a listing in the CISA Known Exploited Vulnerabilities catalog, OR reliable evidence of in-the-wild exploitation from another source (with source, URL and date). A public proof-of-concept or exploit code alone is not enough. Other advisories are kept on record without an alert.

## About this file
This file is a notice only. Placing it here does not guarantee that every person or tool reading the repository will see it. It does not replace or change any existing security policy.
