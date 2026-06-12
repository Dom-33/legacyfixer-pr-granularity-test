# LegacyFixer PR granularity test

Controlled repository for validating whether LegacyFixer creates a small, focused pull request when fixing a vulnerable dependency.

Expected fix:

- `urllib3==1.25.8` should be upgraded by `pip-audit --fix`
- only `requirements.txt` should change
- expected diff: one line changed
