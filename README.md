# ci-smoke-lab
Scratch repo for the quarterly CI smoke test. Safe to delete after the audit.

## Smoke test runbook

1. Confirm the workflow file exists at `.github/workflows/smoke.yml` on the default branch.
2. Open the **Actions** tab and select the **Smoke** workflow.
3. Click **Run workflow** to trigger a manual `workflow_dispatch` run.
4. Watch the run's log output — it echoes two smoke status lines.
5. Use the run result as the smoke signal for the rest of the pipeline.
