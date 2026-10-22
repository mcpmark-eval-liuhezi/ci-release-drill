# Tooling

This drill demonstrates the basic release flow around a minimal CI setup: a GitHub Actions workflow is added on a feature branch, opened as a draft pull request, reviewed, squash-merged into the default branch, and then the workflow triggered by that merge is watched to completion before its run logs are cleaned up. It is intentionally tiny — a single echoing job — so the focus stays on the process (branching, PR review, squash merge, and post-merge housekeeping) rather than on the checks themselves.
