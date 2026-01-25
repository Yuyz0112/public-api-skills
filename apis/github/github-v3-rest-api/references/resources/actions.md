# actions

Endpoints to manage GitHub Actions using the REST API.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/enterprises/{enterprise}/actions/cache/retention-limit` | Get GitHub Actions cache retention limit for an enterprise | [View](../operations/actions-get-actions-cache-retention-limit-for-enterprise.md) |
| PUT | `/enterprises/{enterprise}/actions/cache/retention-limit` | Set GitHub Actions cache retention limit for an enterprise | [View](../operations/actions-set-actions-cache-retention-limit-for-enterprise.md) |
| GET | `/enterprises/{enterprise}/actions/cache/storage-limit` | Get GitHub Actions cache storage limit for an enterprise | [View](../operations/actions-get-actions-cache-storage-limit-for-enterprise.md) |
| PUT | `/enterprises/{enterprise}/actions/cache/storage-limit` | Set GitHub Actions cache storage limit for an enterprise | [View](../operations/actions-set-actions-cache-storage-limit-for-enterprise.md) |
| GET | `/organizations/{org}/actions/cache/retention-limit` | Get GitHub Actions cache retention limit for an organization | [View](../operations/actions-get-actions-cache-retention-limit-for-organization.md) |
| PUT | `/organizations/{org}/actions/cache/retention-limit` | Set GitHub Actions cache retention limit for an organization | [View](../operations/actions-set-actions-cache-retention-limit-for-organization.md) |
| GET | `/organizations/{org}/actions/cache/storage-limit` | Get GitHub Actions cache storage limit for an organization | [View](../operations/actions-get-actions-cache-storage-limit-for-organization.md) |
| PUT | `/organizations/{org}/actions/cache/storage-limit` | Set GitHub Actions cache storage limit for an organization | [View](../operations/actions-set-actions-cache-storage-limit-for-organization.md) |
| GET | `/orgs/{org}/actions/cache/usage` | Get GitHub Actions cache usage for an organization | [View](../operations/actions-get-actions-cache-usage-for-org.md) |
| GET | `/orgs/{org}/actions/cache/usage-by-repository` | List repositories with GitHub Actions cache usage for an organization | [View](../operations/actions-get-actions-cache-usage-by-repo-for-org.md) |
| GET | `/orgs/{org}/actions/hosted-runners` | List GitHub-hosted runners for an organization | [View](../operations/actions-list-hosted-runners-for-org.md) |
| POST | `/orgs/{org}/actions/hosted-runners` | Create a GitHub-hosted runner for an organization | [View](../operations/actions-create-hosted-runner-for-org.md) |
| GET | `/orgs/{org}/actions/hosted-runners/images/custom` | List custom images for an organization | [View](../operations/actions-list-custom-images-for-org.md) |
| GET | `/orgs/{org}/actions/hosted-runners/images/custom/{image_definition_id}` | Get a custom image definition for GitHub Actions Hosted Runners | [View](../operations/actions-get-custom-image-for-org.md) |
| DELETE | `/orgs/{org}/actions/hosted-runners/images/custom/{image_definition_id}` | Delete a custom image from the organization | [View](../operations/actions-delete-custom-image-from-org.md) |
| GET | `/orgs/{org}/actions/hosted-runners/images/custom/{image_definition_id}/versions` | List image versions of a custom image for an organization | [View](../operations/actions-list-custom-image-versions-for-org.md) |
| GET | `/orgs/{org}/actions/hosted-runners/images/custom/{image_definition_id}/versions/{version}` | Get an image version of a custom image for GitHub Actions Hosted Runners | [View](../operations/actions-get-custom-image-version-for-org.md) |
| DELETE | `/orgs/{org}/actions/hosted-runners/images/custom/{image_definition_id}/versions/{version}` | Delete an image version of custom image from the organization | [View](../operations/actions-delete-custom-image-version-from-org.md) |
| GET | `/orgs/{org}/actions/hosted-runners/images/github-owned` | Get GitHub-owned images for GitHub-hosted runners in an organization | [View](../operations/actions-get-hosted-runners-github-owned-images-for-org.md) |
| GET | `/orgs/{org}/actions/hosted-runners/images/partner` | Get partner images for GitHub-hosted runners in an organization | [View](../operations/actions-get-hosted-runners-partner-images-for-org.md) |
| GET | `/orgs/{org}/actions/hosted-runners/limits` | Get limits on GitHub-hosted runners for an organization | [View](../operations/actions-get-hosted-runners-limits-for-org.md) |
| GET | `/orgs/{org}/actions/hosted-runners/machine-sizes` | Get GitHub-hosted runners machine specs for an organization | [View](../operations/actions-get-hosted-runners-machine-specs-for-org.md) |
| GET | `/orgs/{org}/actions/hosted-runners/platforms` | Get platforms for GitHub-hosted runners in an organization | [View](../operations/actions-get-hosted-runners-platforms-for-org.md) |
| GET | `/orgs/{org}/actions/hosted-runners/{hosted_runner_id}` | Get a GitHub-hosted runner for an organization | [View](../operations/actions-get-hosted-runner-for-org.md) |
| DELETE | `/orgs/{org}/actions/hosted-runners/{hosted_runner_id}` | Delete a GitHub-hosted runner for an organization | [View](../operations/actions-delete-hosted-runner-for-org.md) |
| PATCH | `/orgs/{org}/actions/hosted-runners/{hosted_runner_id}` | Update a GitHub-hosted runner for an organization | [View](../operations/actions-update-hosted-runner-for-org.md) |
| GET | `/orgs/{org}/actions/permissions` | Get GitHub Actions permissions for an organization | [View](../operations/actions-get-github-actions-permissions-organization.md) |
| PUT | `/orgs/{org}/actions/permissions` | Set GitHub Actions permissions for an organization | [View](../operations/actions-set-github-actions-permissions-organization.md) |
| GET | `/orgs/{org}/actions/permissions/artifact-and-log-retention` | Get artifact and log retention settings for an organization | [View](../operations/actions-get-artifact-and-log-retention-settings-organization.md) |
| PUT | `/orgs/{org}/actions/permissions/artifact-and-log-retention` | Set artifact and log retention settings for an organization | [View](../operations/actions-set-artifact-and-log-retention-settings-organization.md) |
| GET | `/orgs/{org}/actions/permissions/fork-pr-contributor-approval` | Get fork PR contributor approval permissions for an organization | [View](../operations/actions-get-fork-pr-contributor-approval-permissions-organization.md) |
| PUT | `/orgs/{org}/actions/permissions/fork-pr-contributor-approval` | Set fork PR contributor approval permissions for an organization | [View](../operations/actions-set-fork-pr-contributor-approval-permissions-organization.md) |
| GET | `/orgs/{org}/actions/permissions/fork-pr-workflows-private-repos` | Get private repo fork PR workflow settings for an organization | [View](../operations/actions-get-private-repo-fork-pr-workflows-settings-organization.md) |
| PUT | `/orgs/{org}/actions/permissions/fork-pr-workflows-private-repos` | Set private repo fork PR workflow settings for an organization | [View](../operations/actions-set-private-repo-fork-pr-workflows-settings-organization.md) |
| GET | `/orgs/{org}/actions/permissions/repositories` | List selected repositories enabled for GitHub Actions in an organization | [View](../operations/actions-list-selected-repositories-enabled-github-actions-organization.md) |
| PUT | `/orgs/{org}/actions/permissions/repositories` | Set selected repositories enabled for GitHub Actions in an organization | [View](../operations/actions-set-selected-repositories-enabled-github-actions-organization.md) |
| PUT | `/orgs/{org}/actions/permissions/repositories/{repository_id}` | Enable a selected repository for GitHub Actions in an organization | [View](../operations/actions-enable-selected-repository-github-actions-organization.md) |
| DELETE | `/orgs/{org}/actions/permissions/repositories/{repository_id}` | Disable a selected repository for GitHub Actions in an organization | [View](../operations/actions-disable-selected-repository-github-actions-organization.md) |
| GET | `/orgs/{org}/actions/permissions/selected-actions` | Get allowed actions and reusable workflows for an organization | [View](../operations/actions-get-allowed-actions-organization.md) |
| PUT | `/orgs/{org}/actions/permissions/selected-actions` | Set allowed actions and reusable workflows for an organization | [View](../operations/actions-set-allowed-actions-organization.md) |
| GET | `/orgs/{org}/actions/permissions/self-hosted-runners` | Get self-hosted runners settings for an organization | [View](../operations/actions-get-self-hosted-runners-permissions-organization.md) |
| PUT | `/orgs/{org}/actions/permissions/self-hosted-runners` | Set self-hosted runners settings for an organization | [View](../operations/actions-set-self-hosted-runners-permissions-organization.md) |
| GET | `/orgs/{org}/actions/permissions/self-hosted-runners/repositories` | List repositories allowed to use self-hosted runners in an organization | [View](../operations/actions-list-selected-repositories-self-hosted-runners-organization.md) |
| PUT | `/orgs/{org}/actions/permissions/self-hosted-runners/repositories` | Set repositories allowed to use self-hosted runners in an organization | [View](../operations/actions-set-selected-repositories-self-hosted-runners-organization.md) |
| PUT | `/orgs/{org}/actions/permissions/self-hosted-runners/repositories/{repository_id}` | Add a repository to the list of repositories allowed to use self-hosted runners in an organization | [View](../operations/actions-enable-selected-repository-self-hosted-runners-organization.md) |
| DELETE | `/orgs/{org}/actions/permissions/self-hosted-runners/repositories/{repository_id}` | Remove a repository from the list of repositories allowed to use self-hosted runners in an organization | [View](../operations/actions-disable-selected-repository-self-hosted-runners-organization.md) |
| GET | `/orgs/{org}/actions/permissions/workflow` | Get default workflow permissions for an organization | [View](../operations/actions-get-github-actions-default-workflow-permissions-organization.md) |
| PUT | `/orgs/{org}/actions/permissions/workflow` | Set default workflow permissions for an organization | [View](../operations/actions-set-github-actions-default-workflow-permissions-organization.md) |
| GET | `/orgs/{org}/actions/runner-groups` | List self-hosted runner groups for an organization | [View](../operations/actions-list-self-hosted-runner-groups-for-org.md) |
| POST | `/orgs/{org}/actions/runner-groups` | Create a self-hosted runner group for an organization | [View](../operations/actions-create-self-hosted-runner-group-for-org.md) |
| GET | `/orgs/{org}/actions/runner-groups/{runner_group_id}` | Get a self-hosted runner group for an organization | [View](../operations/actions-get-self-hosted-runner-group-for-org.md) |
| DELETE | `/orgs/{org}/actions/runner-groups/{runner_group_id}` | Delete a self-hosted runner group from an organization | [View](../operations/actions-delete-self-hosted-runner-group-from-org.md) |
| PATCH | `/orgs/{org}/actions/runner-groups/{runner_group_id}` | Update a self-hosted runner group for an organization | [View](../operations/actions-update-self-hosted-runner-group-for-org.md) |
| GET | `/orgs/{org}/actions/runner-groups/{runner_group_id}/hosted-runners` | List GitHub-hosted runners in a group for an organization | [View](../operations/actions-list-github-hosted-runners-in-group-for-org.md) |
| GET | `/orgs/{org}/actions/runner-groups/{runner_group_id}/repositories` | List repository access to a self-hosted runner group in an organization | [View](../operations/actions-list-repo-access-to-self-hosted-runner-group-in-org.md) |
| PUT | `/orgs/{org}/actions/runner-groups/{runner_group_id}/repositories` | Set repository access for a self-hosted runner group in an organization | [View](../operations/actions-set-repo-access-to-self-hosted-runner-group-in-org.md) |
| PUT | `/orgs/{org}/actions/runner-groups/{runner_group_id}/repositories/{repository_id}` | Add repository access to a self-hosted runner group in an organization | [View](../operations/actions-add-repo-access-to-self-hosted-runner-group-in-org.md) |
| DELETE | `/orgs/{org}/actions/runner-groups/{runner_group_id}/repositories/{repository_id}` | Remove repository access to a self-hosted runner group in an organization | [View](../operations/actions-remove-repo-access-to-self-hosted-runner-group-in-org.md) |
| GET | `/orgs/{org}/actions/runner-groups/{runner_group_id}/runners` | List self-hosted runners in a group for an organization | [View](../operations/actions-list-self-hosted-runners-in-group-for-org.md) |
| PUT | `/orgs/{org}/actions/runner-groups/{runner_group_id}/runners` | Set self-hosted runners in a group for an organization | [View](../operations/actions-set-self-hosted-runners-in-group-for-org.md) |
| PUT | `/orgs/{org}/actions/runner-groups/{runner_group_id}/runners/{runner_id}` | Add a self-hosted runner to a group for an organization | [View](../operations/actions-add-self-hosted-runner-to-group-for-org.md) |
| DELETE | `/orgs/{org}/actions/runner-groups/{runner_group_id}/runners/{runner_id}` | Remove a self-hosted runner from a group for an organization | [View](../operations/actions-remove-self-hosted-runner-from-group-for-org.md) |
| GET | `/orgs/{org}/actions/runners` | List self-hosted runners for an organization | [View](../operations/actions-list-self-hosted-runners-for-org.md) |
| GET | `/orgs/{org}/actions/runners/downloads` | List runner applications for an organization | [View](../operations/actions-list-runner-applications-for-org.md) |
| POST | `/orgs/{org}/actions/runners/generate-jitconfig` | Create configuration for a just-in-time runner for an organization | [View](../operations/actions-generate-runner-jitconfig-for-org.md) |
| POST | `/orgs/{org}/actions/runners/registration-token` | Create a registration token for an organization | [View](../operations/actions-create-registration-token-for-org.md) |
| POST | `/orgs/{org}/actions/runners/remove-token` | Create a remove token for an organization | [View](../operations/actions-create-remove-token-for-org.md) |
| GET | `/orgs/{org}/actions/runners/{runner_id}` | Get a self-hosted runner for an organization | [View](../operations/actions-get-self-hosted-runner-for-org.md) |
| DELETE | `/orgs/{org}/actions/runners/{runner_id}` | Delete a self-hosted runner from an organization | [View](../operations/actions-delete-self-hosted-runner-from-org.md) |
| GET | `/orgs/{org}/actions/runners/{runner_id}/labels` | List labels for a self-hosted runner for an organization | [View](../operations/actions-list-labels-for-self-hosted-runner-for-org.md) |
| PUT | `/orgs/{org}/actions/runners/{runner_id}/labels` | Set custom labels for a self-hosted runner for an organization | [View](../operations/actions-set-custom-labels-for-self-hosted-runner-for-org.md) |
| POST | `/orgs/{org}/actions/runners/{runner_id}/labels` | Add custom labels to a self-hosted runner for an organization | [View](../operations/actions-add-custom-labels-to-self-hosted-runner-for-org.md) |
| DELETE | `/orgs/{org}/actions/runners/{runner_id}/labels` | Remove all custom labels from a self-hosted runner for an organization | [View](../operations/actions-remove-all-custom-labels-from-self-hosted-runner-for-org.md) |
| DELETE | `/orgs/{org}/actions/runners/{runner_id}/labels/{name}` | Remove a custom label from a self-hosted runner for an organization | [View](../operations/actions-remove-custom-label-from-self-hosted-runner-for-org.md) |
| GET | `/orgs/{org}/actions/secrets` | List organization secrets | [View](../operations/actions-list-org-secrets.md) |
| GET | `/orgs/{org}/actions/secrets/public-key` | Get an organization public key | [View](../operations/actions-get-org-public-key.md) |
| GET | `/orgs/{org}/actions/secrets/{secret_name}` | Get an organization secret | [View](../operations/actions-get-org-secret.md) |
| PUT | `/orgs/{org}/actions/secrets/{secret_name}` | Create or update an organization secret | [View](../operations/actions-create-or-update-org-secret.md) |
| DELETE | `/orgs/{org}/actions/secrets/{secret_name}` | Delete an organization secret | [View](../operations/actions-delete-org-secret.md) |
| GET | `/orgs/{org}/actions/secrets/{secret_name}/repositories` | List selected repositories for an organization secret | [View](../operations/actions-list-selected-repos-for-org-secret.md) |
| PUT | `/orgs/{org}/actions/secrets/{secret_name}/repositories` | Set selected repositories for an organization secret | [View](../operations/actions-set-selected-repos-for-org-secret.md) |
| PUT | `/orgs/{org}/actions/secrets/{secret_name}/repositories/{repository_id}` | Add selected repository to an organization secret | [View](../operations/actions-add-selected-repo-to-org-secret.md) |
| DELETE | `/orgs/{org}/actions/secrets/{secret_name}/repositories/{repository_id}` | Remove selected repository from an organization secret | [View](../operations/actions-remove-selected-repo-from-org-secret.md) |
| GET | `/orgs/{org}/actions/variables` | List organization variables | [View](../operations/actions-list-org-variables.md) |
| POST | `/orgs/{org}/actions/variables` | Create an organization variable | [View](../operations/actions-create-org-variable.md) |
| GET | `/orgs/{org}/actions/variables/{name}` | Get an organization variable | [View](../operations/actions-get-org-variable.md) |
| DELETE | `/orgs/{org}/actions/variables/{name}` | Delete an organization variable | [View](../operations/actions-delete-org-variable.md) |
| PATCH | `/orgs/{org}/actions/variables/{name}` | Update an organization variable | [View](../operations/actions-update-org-variable.md) |
| GET | `/orgs/{org}/actions/variables/{name}/repositories` | List selected repositories for an organization variable | [View](../operations/actions-list-selected-repos-for-org-variable.md) |
| PUT | `/orgs/{org}/actions/variables/{name}/repositories` | Set selected repositories for an organization variable | [View](../operations/actions-set-selected-repos-for-org-variable.md) |
| PUT | `/orgs/{org}/actions/variables/{name}/repositories/{repository_id}` | Add selected repository to an organization variable | [View](../operations/actions-add-selected-repo-to-org-variable.md) |
| DELETE | `/orgs/{org}/actions/variables/{name}/repositories/{repository_id}` | Remove selected repository from an organization variable | [View](../operations/actions-remove-selected-repo-from-org-variable.md) |
| GET | `/repos/{owner}/{repo}/actions/artifacts` | List artifacts for a repository | [View](../operations/actions-list-artifacts-for-repo.md) |
| GET | `/repos/{owner}/{repo}/actions/artifacts/{artifact_id}` | Get an artifact | [View](../operations/actions-get-artifact.md) |
| DELETE | `/repos/{owner}/{repo}/actions/artifacts/{artifact_id}` | Delete an artifact | [View](../operations/actions-delete-artifact.md) |
| GET | `/repos/{owner}/{repo}/actions/artifacts/{artifact_id}/{archive_format}` | Download an artifact | [View](../operations/actions-download-artifact.md) |
| GET | `/repos/{owner}/{repo}/actions/cache/retention-limit` | Get GitHub Actions cache retention limit for a repository | [View](../operations/actions-get-actions-cache-retention-limit-for-repository.md) |
| PUT | `/repos/{owner}/{repo}/actions/cache/retention-limit` | Set GitHub Actions cache retention limit for a repository | [View](../operations/actions-set-actions-cache-retention-limit-for-repository.md) |
| GET | `/repos/{owner}/{repo}/actions/cache/storage-limit` | Get GitHub Actions cache storage limit for a repository | [View](../operations/actions-get-actions-cache-storage-limit-for-repository.md) |
| PUT | `/repos/{owner}/{repo}/actions/cache/storage-limit` | Set GitHub Actions cache storage limit for a repository | [View](../operations/actions-set-actions-cache-storage-limit-for-repository.md) |
| GET | `/repos/{owner}/{repo}/actions/cache/usage` | Get GitHub Actions cache usage for a repository | [View](../operations/actions-get-actions-cache-usage.md) |
| GET | `/repos/{owner}/{repo}/actions/caches` | List GitHub Actions caches for a repository | [View](../operations/actions-get-actions-cache-list.md) |
| DELETE | `/repos/{owner}/{repo}/actions/caches` | Delete GitHub Actions caches for a repository (using a cache key) | [View](../operations/actions-delete-actions-cache-by-key.md) |
| DELETE | `/repos/{owner}/{repo}/actions/caches/{cache_id}` | Delete a GitHub Actions cache for a repository (using a cache ID) | [View](../operations/actions-delete-actions-cache-by-id.md) |
| GET | `/repos/{owner}/{repo}/actions/jobs/{job_id}` | Get a job for a workflow run | [View](../operations/actions-get-job-for-workflow-run.md) |
| GET | `/repos/{owner}/{repo}/actions/jobs/{job_id}/logs` | Download job logs for a workflow run | [View](../operations/actions-download-job-logs-for-workflow-run.md) |
| POST | `/repos/{owner}/{repo}/actions/jobs/{job_id}/rerun` | Re-run a job from a workflow run | [View](../operations/actions-re-run-job-for-workflow-run.md) |
| GET | `/repos/{owner}/{repo}/actions/oidc/customization/sub` | Get the customization template for an OIDC subject claim for a repository | [View](../operations/actions-get-custom-oidc-sub-claim-for-repo.md) |
| PUT | `/repos/{owner}/{repo}/actions/oidc/customization/sub` | Set the customization template for an OIDC subject claim for a repository | [View](../operations/actions-set-custom-oidc-sub-claim-for-repo.md) |
| GET | `/repos/{owner}/{repo}/actions/organization-secrets` | List repository organization secrets | [View](../operations/actions-list-repo-organization-secrets.md) |
| GET | `/repos/{owner}/{repo}/actions/organization-variables` | List repository organization variables | [View](../operations/actions-list-repo-organization-variables.md) |
| GET | `/repos/{owner}/{repo}/actions/permissions` | Get GitHub Actions permissions for a repository | [View](../operations/actions-get-github-actions-permissions-repository.md) |
| PUT | `/repos/{owner}/{repo}/actions/permissions` | Set GitHub Actions permissions for a repository | [View](../operations/actions-set-github-actions-permissions-repository.md) |
| GET | `/repos/{owner}/{repo}/actions/permissions/access` | Get the level of access for workflows outside of the repository | [View](../operations/actions-get-workflow-access-to-repository.md) |
| PUT | `/repos/{owner}/{repo}/actions/permissions/access` | Set the level of access for workflows outside of the repository | [View](../operations/actions-set-workflow-access-to-repository.md) |
| GET | `/repos/{owner}/{repo}/actions/permissions/artifact-and-log-retention` | Get artifact and log retention settings for a repository | [View](../operations/actions-get-artifact-and-log-retention-settings-repository.md) |
| PUT | `/repos/{owner}/{repo}/actions/permissions/artifact-and-log-retention` | Set artifact and log retention settings for a repository | [View](../operations/actions-set-artifact-and-log-retention-settings-repository.md) |
| GET | `/repos/{owner}/{repo}/actions/permissions/fork-pr-contributor-approval` | Get fork PR contributor approval permissions for a repository | [View](../operations/actions-get-fork-pr-contributor-approval-permissions-repository.md) |
| PUT | `/repos/{owner}/{repo}/actions/permissions/fork-pr-contributor-approval` | Set fork PR contributor approval permissions for a repository | [View](../operations/actions-set-fork-pr-contributor-approval-permissions-repository.md) |
| GET | `/repos/{owner}/{repo}/actions/permissions/fork-pr-workflows-private-repos` | Get private repo fork PR workflow settings for a repository | [View](../operations/actions-get-private-repo-fork-pr-workflows-settings-repository.md) |
| PUT | `/repos/{owner}/{repo}/actions/permissions/fork-pr-workflows-private-repos` | Set private repo fork PR workflow settings for a repository | [View](../operations/actions-set-private-repo-fork-pr-workflows-settings-repository.md) |
| GET | `/repos/{owner}/{repo}/actions/permissions/selected-actions` | Get allowed actions and reusable workflows for a repository | [View](../operations/actions-get-allowed-actions-repository.md) |
| PUT | `/repos/{owner}/{repo}/actions/permissions/selected-actions` | Set allowed actions and reusable workflows for a repository | [View](../operations/actions-set-allowed-actions-repository.md) |
| GET | `/repos/{owner}/{repo}/actions/permissions/workflow` | Get default workflow permissions for a repository | [View](../operations/actions-get-github-actions-default-workflow-permissions-repository.md) |
| PUT | `/repos/{owner}/{repo}/actions/permissions/workflow` | Set default workflow permissions for a repository | [View](../operations/actions-set-github-actions-default-workflow-permissions-repository.md) |
| GET | `/repos/{owner}/{repo}/actions/runners` | List self-hosted runners for a repository | [View](../operations/actions-list-self-hosted-runners-for-repo.md) |
| GET | `/repos/{owner}/{repo}/actions/runners/downloads` | List runner applications for a repository | [View](../operations/actions-list-runner-applications-for-repo.md) |
| POST | `/repos/{owner}/{repo}/actions/runners/generate-jitconfig` | Create configuration for a just-in-time runner for a repository | [View](../operations/actions-generate-runner-jitconfig-for-repo.md) |
| POST | `/repos/{owner}/{repo}/actions/runners/registration-token` | Create a registration token for a repository | [View](../operations/actions-create-registration-token-for-repo.md) |
| POST | `/repos/{owner}/{repo}/actions/runners/remove-token` | Create a remove token for a repository | [View](../operations/actions-create-remove-token-for-repo.md) |
| GET | `/repos/{owner}/{repo}/actions/runners/{runner_id}` | Get a self-hosted runner for a repository | [View](../operations/actions-get-self-hosted-runner-for-repo.md) |
| DELETE | `/repos/{owner}/{repo}/actions/runners/{runner_id}` | Delete a self-hosted runner from a repository | [View](../operations/actions-delete-self-hosted-runner-from-repo.md) |
| GET | `/repos/{owner}/{repo}/actions/runners/{runner_id}/labels` | List labels for a self-hosted runner for a repository | [View](../operations/actions-list-labels-for-self-hosted-runner-for-repo.md) |
| PUT | `/repos/{owner}/{repo}/actions/runners/{runner_id}/labels` | Set custom labels for a self-hosted runner for a repository | [View](../operations/actions-set-custom-labels-for-self-hosted-runner-for-repo.md) |
| POST | `/repos/{owner}/{repo}/actions/runners/{runner_id}/labels` | Add custom labels to a self-hosted runner for a repository | [View](../operations/actions-add-custom-labels-to-self-hosted-runner-for-repo.md) |
| DELETE | `/repos/{owner}/{repo}/actions/runners/{runner_id}/labels` | Remove all custom labels from a self-hosted runner for a repository | [View](../operations/actions-remove-all-custom-labels-from-self-hosted-runner-for-repo.md) |
| DELETE | `/repos/{owner}/{repo}/actions/runners/{runner_id}/labels/{name}` | Remove a custom label from a self-hosted runner for a repository | [View](../operations/actions-remove-custom-label-from-self-hosted-runner-for-repo.md) |
| GET | `/repos/{owner}/{repo}/actions/runs` | List workflow runs for a repository | [View](../operations/actions-list-workflow-runs-for-repo.md) |
| GET | `/repos/{owner}/{repo}/actions/runs/{run_id}` | Get a workflow run | [View](../operations/actions-get-workflow-run.md) |
| DELETE | `/repos/{owner}/{repo}/actions/runs/{run_id}` | Delete a workflow run | [View](../operations/actions-delete-workflow-run.md) |
| GET | `/repos/{owner}/{repo}/actions/runs/{run_id}/approvals` | Get the review history for a workflow run | [View](../operations/actions-get-reviews-for-run.md) |
| POST | `/repos/{owner}/{repo}/actions/runs/{run_id}/approve` | Approve a workflow run for a fork pull request | [View](../operations/actions-approve-workflow-run.md) |
| GET | `/repos/{owner}/{repo}/actions/runs/{run_id}/artifacts` | List workflow run artifacts | [View](../operations/actions-list-workflow-run-artifacts.md) |
| GET | `/repos/{owner}/{repo}/actions/runs/{run_id}/attempts/{attempt_number}` | Get a workflow run attempt | [View](../operations/actions-get-workflow-run-attempt.md) |
| GET | `/repos/{owner}/{repo}/actions/runs/{run_id}/attempts/{attempt_number}/jobs` | List jobs for a workflow run attempt | [View](../operations/actions-list-jobs-for-workflow-run-attempt.md) |
| GET | `/repos/{owner}/{repo}/actions/runs/{run_id}/attempts/{attempt_number}/logs` | Download workflow run attempt logs | [View](../operations/actions-download-workflow-run-attempt-logs.md) |
| POST | `/repos/{owner}/{repo}/actions/runs/{run_id}/cancel` | Cancel a workflow run | [View](../operations/actions-cancel-workflow-run.md) |
| POST | `/repos/{owner}/{repo}/actions/runs/{run_id}/deployment_protection_rule` | Review custom deployment protection rules for a workflow run | [View](../operations/actions-review-custom-gates-for-run.md) |
| POST | `/repos/{owner}/{repo}/actions/runs/{run_id}/force-cancel` | Force cancel a workflow run | [View](../operations/actions-force-cancel-workflow-run.md) |
| GET | `/repos/{owner}/{repo}/actions/runs/{run_id}/jobs` | List jobs for a workflow run | [View](../operations/actions-list-jobs-for-workflow-run.md) |
| GET | `/repos/{owner}/{repo}/actions/runs/{run_id}/logs` | Download workflow run logs | [View](../operations/actions-download-workflow-run-logs.md) |
| DELETE | `/repos/{owner}/{repo}/actions/runs/{run_id}/logs` | Delete workflow run logs | [View](../operations/actions-delete-workflow-run-logs.md) |
| GET | `/repos/{owner}/{repo}/actions/runs/{run_id}/pending_deployments` | Get pending deployments for a workflow run | [View](../operations/actions-get-pending-deployments-for-run.md) |
| POST | `/repos/{owner}/{repo}/actions/runs/{run_id}/pending_deployments` | Review pending deployments for a workflow run | [View](../operations/actions-review-pending-deployments-for-run.md) |
| POST | `/repos/{owner}/{repo}/actions/runs/{run_id}/rerun` | Re-run a workflow | [View](../operations/actions-re-run-workflow.md) |
| POST | `/repos/{owner}/{repo}/actions/runs/{run_id}/rerun-failed-jobs` | Re-run failed jobs from a workflow run | [View](../operations/actions-re-run-workflow-failed-jobs.md) |
| GET | `/repos/{owner}/{repo}/actions/runs/{run_id}/timing` | Get workflow run usage | [View](../operations/actions-get-workflow-run-usage.md) |
| GET | `/repos/{owner}/{repo}/actions/secrets` | List repository secrets | [View](../operations/actions-list-repo-secrets.md) |
| GET | `/repos/{owner}/{repo}/actions/secrets/public-key` | Get a repository public key | [View](../operations/actions-get-repo-public-key.md) |
| GET | `/repos/{owner}/{repo}/actions/secrets/{secret_name}` | Get a repository secret | [View](../operations/actions-get-repo-secret.md) |
| PUT | `/repos/{owner}/{repo}/actions/secrets/{secret_name}` | Create or update a repository secret | [View](../operations/actions-create-or-update-repo-secret.md) |
| DELETE | `/repos/{owner}/{repo}/actions/secrets/{secret_name}` | Delete a repository secret | [View](../operations/actions-delete-repo-secret.md) |
| GET | `/repos/{owner}/{repo}/actions/variables` | List repository variables | [View](../operations/actions-list-repo-variables.md) |
| POST | `/repos/{owner}/{repo}/actions/variables` | Create a repository variable | [View](../operations/actions-create-repo-variable.md) |
| GET | `/repos/{owner}/{repo}/actions/variables/{name}` | Get a repository variable | [View](../operations/actions-get-repo-variable.md) |
| DELETE | `/repos/{owner}/{repo}/actions/variables/{name}` | Delete a repository variable | [View](../operations/actions-delete-repo-variable.md) |
| PATCH | `/repos/{owner}/{repo}/actions/variables/{name}` | Update a repository variable | [View](../operations/actions-update-repo-variable.md) |
| GET | `/repos/{owner}/{repo}/actions/workflows` | List repository workflows | [View](../operations/actions-list-repo-workflows.md) |
| GET | `/repos/{owner}/{repo}/actions/workflows/{workflow_id}` | Get a workflow | [View](../operations/actions-get-workflow.md) |
| PUT | `/repos/{owner}/{repo}/actions/workflows/{workflow_id}/disable` | Disable a workflow | [View](../operations/actions-disable-workflow.md) |
| POST | `/repos/{owner}/{repo}/actions/workflows/{workflow_id}/dispatches` | Create a workflow dispatch event | [View](../operations/actions-create-workflow-dispatch.md) |
| PUT | `/repos/{owner}/{repo}/actions/workflows/{workflow_id}/enable` | Enable a workflow | [View](../operations/actions-enable-workflow.md) |
| GET | `/repos/{owner}/{repo}/actions/workflows/{workflow_id}/runs` | List workflow runs for a workflow | [View](../operations/actions-list-workflow-runs.md) |
| GET | `/repos/{owner}/{repo}/actions/workflows/{workflow_id}/timing` | Get workflow usage | [View](../operations/actions-get-workflow-usage.md) |
| GET | `/repos/{owner}/{repo}/environments/{environment_name}/secrets` | List environment secrets | [View](../operations/actions-list-environment-secrets.md) |
| GET | `/repos/{owner}/{repo}/environments/{environment_name}/secrets/public-key` | Get an environment public key | [View](../operations/actions-get-environment-public-key.md) |
| GET | `/repos/{owner}/{repo}/environments/{environment_name}/secrets/{secret_name}` | Get an environment secret | [View](../operations/actions-get-environment-secret.md) |
| PUT | `/repos/{owner}/{repo}/environments/{environment_name}/secrets/{secret_name}` | Create or update an environment secret | [View](../operations/actions-create-or-update-environment-secret.md) |
| DELETE | `/repos/{owner}/{repo}/environments/{environment_name}/secrets/{secret_name}` | Delete an environment secret | [View](../operations/actions-delete-environment-secret.md) |
| GET | `/repos/{owner}/{repo}/environments/{environment_name}/variables` | List environment variables | [View](../operations/actions-list-environment-variables.md) |
| POST | `/repos/{owner}/{repo}/environments/{environment_name}/variables` | Create an environment variable | [View](../operations/actions-create-environment-variable.md) |
| GET | `/repos/{owner}/{repo}/environments/{environment_name}/variables/{name}` | Get an environment variable | [View](../operations/actions-get-environment-variable.md) |
| DELETE | `/repos/{owner}/{repo}/environments/{environment_name}/variables/{name}` | Delete an environment variable | [View](../operations/actions-delete-environment-variable.md) |
| PATCH | `/repos/{owner}/{repo}/environments/{environment_name}/variables/{name}` | Update an environment variable | [View](../operations/actions-update-environment-variable.md) |
