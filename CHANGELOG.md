## [unreleased]

### 💼 Other

- Initial plan
- Fix Renovate configuration by removing conflicting matchUpdateTypes

Co-authored-by: sm-moshi <12695314+sm-moshi@users.noreply.github.com>
- Merge pull request #3 from sm-moshi/copilot/fix-renovate-configuration-error

Fix Renovate configuration: remove conflicting matchUpdateTypes
- Update tooling configs for helm-charts

  - add git-cliff and rumdl configs for consistent changelog/markdown linting
  - update mise tool/tasks and pre-commit/yamllint settings
  - adjust CI workflow defaults and ignore patterns
  - touch contributing guidance to match tooling
- Add CyberChef chart
- Add Gitea runner chart
- Add WUD chart
## [argus-0.4.0] - 2025-12-30

### 💼 Other

- Argus helm 0.4.0
## [argus-0.3.0] - 2025-12-30

### 💼 Other

- Bump: argus 0.3.0
## [it-tools-0.1.0] - 2025-12-30

### 💼 Other

- Add Argus Helm chart

  - Add Argus chart using bjw-s/common
  - Provide config/secret helpers and ArgoCD example
  - Include chart lock and vendored dependency
- Added IT-Tools Helm chart
## [homepage-0.2.0] - 2025-12-30

### ⚙️ Miscellaneous Tasks

- Chore(ci): streamline ct config, hooks, docs, and Artifact Hub metadata

  - enable version bump checks and install tests
  - add pre-commit hook wrapper
  - add artifacthub-repo.yml + badges
  - refresh contributing guide and Renovate config
- Chore: implemented testing for homepage chart
## [homepage-0.1.2] - 2025-12-30

### 💼 Other

- Initial commit
- Initial plan
- Set up Helm charts repository structure with example chart and ArgoCD integration

Co-authored-by: sm-moshi <12695314+sm-moshi@users.noreply.github.com>
- Add quick start guide, templates guide, and ArgoCD validation workflow

Co-authored-by: sm-moshi <12695314+sm-moshi@users.noreply.github.com>
- Fix code review issues: containerPort, HTTPRoute path, and App of Apps reference

Co-authored-by: sm-moshi <12695314+sm-moshi@users.noreply.github.com>
- Add permissions blocks to GitHub Actions workflows for security

Co-authored-by: sm-moshi <12695314+sm-moshi@users.noreply.github.com>
- Merge branch 'main' into copilot/add-helm-charts-for-deployment
- Merge pull request #1 from sm-moshi/copilot/add-helm-charts-for-deployment

Set up Helm charts repository with ArgoCD integration
- Create CNAME
- Merge remote-tracking branch 'origin/main'
- Delete CNAME
- Disable Pages build; ensure gh-pages exists for chart releases
- Implemented CI + release flow and pre‑commit hooks
- Bump: homepage chart
- Remove example-app

### ⚙️ Miscellaneous Tasks

- Chore: workflows setup
- Chore: renovate setup
- Chore: Homepage v1.8.0 Helm chart
- Chore: Helm repo setup
- Chore: Helm repo setup + v0.1.1 Homepage Chart
- Chore: cleanup
- Chore: Helm chart repo setup part 321321412
- Chore: workflows
