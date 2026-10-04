# OpenMRS Testing
QA artifacts for [OpenMRS](https://o3.openmrs.org)

## Files

- `test-cases.csv` / `.xlsx` — 8 manual test cases (login, patient search, registration, vitals)
- `bug-reports.csv` / `.xlsx` — 3 bugs, linked to their test case IDs

## Results
5 passed, 3 failed:
- **BUG-001** (TC-006) — Names accept symbols like `#` and `@` · Medium
- **BUG-002** (TC-007) — Vague error when saving invalid vitals · Low
- **BUG-003** (TC-008) — Phone numbers accept letters · Low

## Notes
- Tested against `o3.openmrs.org` as `admin`
- Browser used: Mozilla Firefox 140.16.0
