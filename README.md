# fletcher.github.io

Thin deployment repository for publishing the Fletcher docs at:

- https://fletcher-package.github.io/

This repository intentionally does not contain `fletcher` package source code.
It only deploys static docs from `fletcher-package/fletcher` via:

- `.github/workflows/deploy-from-fletcher.yml`

## Triggering deploys

- Manual: run the workflow from the Actions tab (`workflow_dispatch`).
- Automatic: send `repository_dispatch` with event type `fletcher-docs-updated`.
