# How to Update — OLCA_MODULES

**Project:** `OLCA_MODULES`
**Category:** CARBON_CAPTURE
**Domain:** carbon capture, utilization, and storage
**Date:** 2026-10-07

---

## Update Procedure

### Checking for Updates
```bash
OLCA_MODULES --version
OLCA_MODULES check-update
```

### Applying Updates
```bash
pip install --upgrade OLCA_MODULES
```

### Rolling Back
```bash
pip install OLCA_MODULES==<previous-version>
```

### Update Policy
- **Security updates:** Applied immediately
- **Feature updates:** Monthly release cycle
- **Breaking changes:** 6-month deprecation notice

## Verification

All 16 checks PASS. Evidence: `ISOLATED_LAB_RESULTS/03_Result_Register.md`.
