### What's changed in v0.1.0

* feat: helm chart xrd (by @patrickleet)

* fix: standardize GitHub workflows (by @patrickleet)

* fix(e2e): add ClusterRoleBinding for Helm provider permissions (by @patrickleet)

  Add cluster-admin permissions to crossplane-system service accounts
  to allow the Helm provider to create namespaces and install charts.
  Also updates the e2e test configuration to match the cert-manager
  pattern that is proven to work.

  Co-Authored-By: Claude Opus 4.5 <noreply@anthropic.com>


