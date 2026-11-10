# ci-smoke-lab
Scratch repo for the quarterly CI smoke test. Safe to delete after the audit.

## Build artifact

The CI pipeline in `.github/workflows/smoke.yml` writes `demo-build.txt` and uploads it as a build artifact named **demo-build**. Verified end to end via a manually dispatched workflow run.
