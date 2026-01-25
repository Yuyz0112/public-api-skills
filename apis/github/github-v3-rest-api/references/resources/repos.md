# repos

Interact with GitHub Repos.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/orgs/{org}/repos` | List organization repositories | [View](../operations/repos-list-for-org.md) |
| POST | `/orgs/{org}/repos` | Create an organization repository | [View](../operations/repos-create-in-org.md) |
| GET | `/orgs/{org}/rulesets` | Get all organization repository rulesets | [View](../operations/repos-get-org-rulesets.md) |
| POST | `/orgs/{org}/rulesets` | Create an organization repository ruleset | [View](../operations/repos-create-org-ruleset.md) |
| GET | `/orgs/{org}/rulesets/rule-suites` | List organization rule suites | [View](../operations/repos-get-org-rule-suites.md) |
| GET | `/orgs/{org}/rulesets/rule-suites/{rule_suite_id}` | Get an organization rule suite | [View](../operations/repos-get-org-rule-suite.md) |
| GET | `/orgs/{org}/rulesets/{ruleset_id}` | Get an organization repository ruleset | [View](../operations/repos-get-org-ruleset.md) |
| PUT | `/orgs/{org}/rulesets/{ruleset_id}` | Update an organization repository ruleset | [View](../operations/repos-update-org-ruleset.md) |
| DELETE | `/orgs/{org}/rulesets/{ruleset_id}` | Delete an organization repository ruleset | [View](../operations/repos-delete-org-ruleset.md) |
| GET | `/repos/{owner}/{repo}` | Get a repository | [View](../operations/repos-get.md) |
| DELETE | `/repos/{owner}/{repo}` | Delete a repository | [View](../operations/repos-delete.md) |
| PATCH | `/repos/{owner}/{repo}` | Update a repository | [View](../operations/repos-update.md) |
| GET | `/repos/{owner}/{repo}/activity` | List repository activities | [View](../operations/repos-list-activities.md) |
| POST | `/repos/{owner}/{repo}/attestations` | Create an attestation | [View](../operations/repos-create-attestation.md) |
| GET | `/repos/{owner}/{repo}/attestations/{subject_digest}` | List attestations | [View](../operations/repos-list-attestations.md) |
| GET | `/repos/{owner}/{repo}/autolinks` | Get all autolinks of a repository | [View](../operations/repos-list-autolinks.md) |
| POST | `/repos/{owner}/{repo}/autolinks` | Create an autolink reference for a repository | [View](../operations/repos-create-autolink.md) |
| GET | `/repos/{owner}/{repo}/autolinks/{autolink_id}` | Get an autolink reference of a repository | [View](../operations/repos-get-autolink.md) |
| DELETE | `/repos/{owner}/{repo}/autolinks/{autolink_id}` | Delete an autolink reference from a repository | [View](../operations/repos-delete-autolink.md) |
| GET | `/repos/{owner}/{repo}/automated-security-fixes` | Check if Dependabot security updates are enabled for a repository | [View](../operations/repos-check-automated-security-fixes.md) |
| PUT | `/repos/{owner}/{repo}/automated-security-fixes` | Enable Dependabot security updates | [View](../operations/repos-enable-automated-security-fixes.md) |
| DELETE | `/repos/{owner}/{repo}/automated-security-fixes` | Disable Dependabot security updates | [View](../operations/repos-disable-automated-security-fixes.md) |
| GET | `/repos/{owner}/{repo}/branches` | List branches | [View](../operations/repos-list-branches.md) |
| GET | `/repos/{owner}/{repo}/branches/{branch}` | Get a branch | [View](../operations/repos-get-branch.md) |
| GET | `/repos/{owner}/{repo}/branches/{branch}/protection` | Get branch protection | [View](../operations/repos-get-branch-protection.md) |
| PUT | `/repos/{owner}/{repo}/branches/{branch}/protection` | Update branch protection | [View](../operations/repos-update-branch-protection.md) |
| DELETE | `/repos/{owner}/{repo}/branches/{branch}/protection` | Delete branch protection | [View](../operations/repos-delete-branch-protection.md) |
| GET | `/repos/{owner}/{repo}/branches/{branch}/protection/enforce_admins` | Get admin branch protection | [View](../operations/repos-get-admin-branch-protection.md) |
| POST | `/repos/{owner}/{repo}/branches/{branch}/protection/enforce_admins` | Set admin branch protection | [View](../operations/repos-set-admin-branch-protection.md) |
| DELETE | `/repos/{owner}/{repo}/branches/{branch}/protection/enforce_admins` | Delete admin branch protection | [View](../operations/repos-delete-admin-branch-protection.md) |
| GET | `/repos/{owner}/{repo}/branches/{branch}/protection/required_pull_request_reviews` | Get pull request review protection | [View](../operations/repos-get-pull-request-review-protection.md) |
| DELETE | `/repos/{owner}/{repo}/branches/{branch}/protection/required_pull_request_reviews` | Delete pull request review protection | [View](../operations/repos-delete-pull-request-review-protection.md) |
| PATCH | `/repos/{owner}/{repo}/branches/{branch}/protection/required_pull_request_reviews` | Update pull request review protection | [View](../operations/repos-update-pull-request-review-protection.md) |
| GET | `/repos/{owner}/{repo}/branches/{branch}/protection/required_signatures` | Get commit signature protection | [View](../operations/repos-get-commit-signature-protection.md) |
| POST | `/repos/{owner}/{repo}/branches/{branch}/protection/required_signatures` | Create commit signature protection | [View](../operations/repos-create-commit-signature-protection.md) |
| DELETE | `/repos/{owner}/{repo}/branches/{branch}/protection/required_signatures` | Delete commit signature protection | [View](../operations/repos-delete-commit-signature-protection.md) |
| GET | `/repos/{owner}/{repo}/branches/{branch}/protection/required_status_checks` | Get status checks protection | [View](../operations/repos-get-status-checks-protection.md) |
| DELETE | `/repos/{owner}/{repo}/branches/{branch}/protection/required_status_checks` | Remove status check protection | [View](../operations/repos-remove-status-check-protection.md) |
| PATCH | `/repos/{owner}/{repo}/branches/{branch}/protection/required_status_checks` | Update status check protection | [View](../operations/repos-update-status-check-protection.md) |
| GET | `/repos/{owner}/{repo}/branches/{branch}/protection/required_status_checks/contexts` | Get all status check contexts | [View](../operations/repos-get-all-status-check-contexts.md) |
| PUT | `/repos/{owner}/{repo}/branches/{branch}/protection/required_status_checks/contexts` | Set status check contexts | [View](../operations/repos-set-status-check-contexts.md) |
| POST | `/repos/{owner}/{repo}/branches/{branch}/protection/required_status_checks/contexts` | Add status check contexts | [View](../operations/repos-add-status-check-contexts.md) |
| DELETE | `/repos/{owner}/{repo}/branches/{branch}/protection/required_status_checks/contexts` | Remove status check contexts | [View](../operations/repos-remove-status-check-contexts.md) |
| GET | `/repos/{owner}/{repo}/branches/{branch}/protection/restrictions` | Get access restrictions | [View](../operations/repos-get-access-restrictions.md) |
| DELETE | `/repos/{owner}/{repo}/branches/{branch}/protection/restrictions` | Delete access restrictions | [View](../operations/repos-delete-access-restrictions.md) |
| GET | `/repos/{owner}/{repo}/branches/{branch}/protection/restrictions/apps` | Get apps with access to the protected branch | [View](../operations/repos-get-apps-with-access-to-protected-branch.md) |
| PUT | `/repos/{owner}/{repo}/branches/{branch}/protection/restrictions/apps` | Set app access restrictions | [View](../operations/repos-set-app-access-restrictions.md) |
| POST | `/repos/{owner}/{repo}/branches/{branch}/protection/restrictions/apps` | Add app access restrictions | [View](../operations/repos-add-app-access-restrictions.md) |
| DELETE | `/repos/{owner}/{repo}/branches/{branch}/protection/restrictions/apps` | Remove app access restrictions | [View](../operations/repos-remove-app-access-restrictions.md) |
| GET | `/repos/{owner}/{repo}/branches/{branch}/protection/restrictions/teams` | Get teams with access to the protected branch | [View](../operations/repos-get-teams-with-access-to-protected-branch.md) |
| PUT | `/repos/{owner}/{repo}/branches/{branch}/protection/restrictions/teams` | Set team access restrictions | [View](../operations/repos-set-team-access-restrictions.md) |
| POST | `/repos/{owner}/{repo}/branches/{branch}/protection/restrictions/teams` | Add team access restrictions | [View](../operations/repos-add-team-access-restrictions.md) |
| DELETE | `/repos/{owner}/{repo}/branches/{branch}/protection/restrictions/teams` | Remove team access restrictions | [View](../operations/repos-remove-team-access-restrictions.md) |
| GET | `/repos/{owner}/{repo}/branches/{branch}/protection/restrictions/users` | Get users with access to the protected branch | [View](../operations/repos-get-users-with-access-to-protected-branch.md) |
| PUT | `/repos/{owner}/{repo}/branches/{branch}/protection/restrictions/users` | Set user access restrictions | [View](../operations/repos-set-user-access-restrictions.md) |
| POST | `/repos/{owner}/{repo}/branches/{branch}/protection/restrictions/users` | Add user access restrictions | [View](../operations/repos-add-user-access-restrictions.md) |
| DELETE | `/repos/{owner}/{repo}/branches/{branch}/protection/restrictions/users` | Remove user access restrictions | [View](../operations/repos-remove-user-access-restrictions.md) |
| POST | `/repos/{owner}/{repo}/branches/{branch}/rename` | Rename a branch | [View](../operations/repos-rename-branch.md) |
| GET | `/repos/{owner}/{repo}/codeowners/errors` | List CODEOWNERS errors | [View](../operations/repos-codeowners-errors.md) |
| GET | `/repos/{owner}/{repo}/collaborators` | List repository collaborators | [View](../operations/repos-list-collaborators.md) |
| GET | `/repos/{owner}/{repo}/collaborators/{username}` | Check if a user is a repository collaborator | [View](../operations/repos-check-collaborator.md) |
| PUT | `/repos/{owner}/{repo}/collaborators/{username}` | Add a repository collaborator | [View](../operations/repos-add-collaborator.md) |
| DELETE | `/repos/{owner}/{repo}/collaborators/{username}` | Remove a repository collaborator | [View](../operations/repos-remove-collaborator.md) |
| GET | `/repos/{owner}/{repo}/collaborators/{username}/permission` | Get repository permissions for a user | [View](../operations/repos-get-collaborator-permission-level.md) |
| GET | `/repos/{owner}/{repo}/comments` | List commit comments for a repository | [View](../operations/repos-list-commit-comments-for-repo.md) |
| GET | `/repos/{owner}/{repo}/comments/{comment_id}` | Get a commit comment | [View](../operations/repos-get-commit-comment.md) |
| DELETE | `/repos/{owner}/{repo}/comments/{comment_id}` | Delete a commit comment | [View](../operations/repos-delete-commit-comment.md) |
| PATCH | `/repos/{owner}/{repo}/comments/{comment_id}` | Update a commit comment | [View](../operations/repos-update-commit-comment.md) |
| GET | `/repos/{owner}/{repo}/commits` | List commits | [View](../operations/repos-list-commits.md) |
| GET | `/repos/{owner}/{repo}/commits/{commit_sha}/branches-where-head` | List branches for HEAD commit | [View](../operations/repos-list-branches-for-head-commit.md) |
| GET | `/repos/{owner}/{repo}/commits/{commit_sha}/comments` | List commit comments | [View](../operations/repos-list-comments-for-commit.md) |
| POST | `/repos/{owner}/{repo}/commits/{commit_sha}/comments` | Create a commit comment | [View](../operations/repos-create-commit-comment.md) |
| GET | `/repos/{owner}/{repo}/commits/{commit_sha}/pulls` | List pull requests associated with a commit | [View](../operations/repos-list-pull-requests-associated-with-commit.md) |
| GET | `/repos/{owner}/{repo}/commits/{ref}` | Get a commit | [View](../operations/repos-get-commit.md) |
| GET | `/repos/{owner}/{repo}/commits/{ref}/status` | Get the combined status for a specific reference | [View](../operations/repos-get-combined-status-for-ref.md) |
| GET | `/repos/{owner}/{repo}/commits/{ref}/statuses` | List commit statuses for a reference | [View](../operations/repos-list-commit-statuses-for-ref.md) |
| GET | `/repos/{owner}/{repo}/community/profile` | Get community profile metrics | [View](../operations/repos-get-community-profile-metrics.md) |
| GET | `/repos/{owner}/{repo}/compare/{basehead}` | Compare two commits | [View](../operations/repos-compare-commits.md) |
| GET | `/repos/{owner}/{repo}/contents/{path}` | Get repository content | [View](../operations/repos-get-content.md) |
| PUT | `/repos/{owner}/{repo}/contents/{path}` | Create or update file contents | [View](../operations/repos-create-or-update-file-contents.md) |
| DELETE | `/repos/{owner}/{repo}/contents/{path}` | Delete a file | [View](../operations/repos-delete-file.md) |
| GET | `/repos/{owner}/{repo}/contributors` | List repository contributors | [View](../operations/repos-list-contributors.md) |
| GET | `/repos/{owner}/{repo}/deployments` | List deployments | [View](../operations/repos-list-deployments.md) |
| POST | `/repos/{owner}/{repo}/deployments` | Create a deployment | [View](../operations/repos-create-deployment.md) |
| GET | `/repos/{owner}/{repo}/deployments/{deployment_id}` | Get a deployment | [View](../operations/repos-get-deployment.md) |
| DELETE | `/repos/{owner}/{repo}/deployments/{deployment_id}` | Delete a deployment | [View](../operations/repos-delete-deployment.md) |
| GET | `/repos/{owner}/{repo}/deployments/{deployment_id}/statuses` | List deployment statuses | [View](../operations/repos-list-deployment-statuses.md) |
| POST | `/repos/{owner}/{repo}/deployments/{deployment_id}/statuses` | Create a deployment status | [View](../operations/repos-create-deployment-status.md) |
| GET | `/repos/{owner}/{repo}/deployments/{deployment_id}/statuses/{status_id}` | Get a deployment status | [View](../operations/repos-get-deployment-status.md) |
| POST | `/repos/{owner}/{repo}/dispatches` | Create a repository dispatch event | [View](../operations/repos-create-dispatch-event.md) |
| GET | `/repos/{owner}/{repo}/environments` | List environments | [View](../operations/repos-get-all-environments.md) |
| GET | `/repos/{owner}/{repo}/environments/{environment_name}` | Get an environment | [View](../operations/repos-get-environment.md) |
| PUT | `/repos/{owner}/{repo}/environments/{environment_name}` | Create or update an environment | [View](../operations/repos-create-or-update-environment.md) |
| DELETE | `/repos/{owner}/{repo}/environments/{environment_name}` | Delete an environment | [View](../operations/repos-delete-an-environment.md) |
| GET | `/repos/{owner}/{repo}/environments/{environment_name}/deployment-branch-policies` | List deployment branch policies | [View](../operations/repos-list-deployment-branch-policies.md) |
| POST | `/repos/{owner}/{repo}/environments/{environment_name}/deployment-branch-policies` | Create a deployment branch policy | [View](../operations/repos-create-deployment-branch-policy.md) |
| GET | `/repos/{owner}/{repo}/environments/{environment_name}/deployment-branch-policies/{branch_policy_id}` | Get a deployment branch policy | [View](../operations/repos-get-deployment-branch-policy.md) |
| PUT | `/repos/{owner}/{repo}/environments/{environment_name}/deployment-branch-policies/{branch_policy_id}` | Update a deployment branch policy | [View](../operations/repos-update-deployment-branch-policy.md) |
| DELETE | `/repos/{owner}/{repo}/environments/{environment_name}/deployment-branch-policies/{branch_policy_id}` | Delete a deployment branch policy | [View](../operations/repos-delete-deployment-branch-policy.md) |
| GET | `/repos/{owner}/{repo}/environments/{environment_name}/deployment_protection_rules` | Get all deployment protection rules for an environment | [View](../operations/repos-get-all-deployment-protection-rules.md) |
| POST | `/repos/{owner}/{repo}/environments/{environment_name}/deployment_protection_rules` | Create a custom deployment protection rule on an environment | [View](../operations/repos-create-deployment-protection-rule.md) |
| GET | `/repos/{owner}/{repo}/environments/{environment_name}/deployment_protection_rules/apps` | List custom deployment rule integrations available for an environment | [View](../operations/repos-list-custom-deployment-rule-integrations.md) |
| GET | `/repos/{owner}/{repo}/environments/{environment_name}/deployment_protection_rules/{protection_rule_id}` | Get a custom deployment protection rule | [View](../operations/repos-get-custom-deployment-protection-rule.md) |
| DELETE | `/repos/{owner}/{repo}/environments/{environment_name}/deployment_protection_rules/{protection_rule_id}` | Disable a custom protection rule for an environment | [View](../operations/repos-disable-deployment-protection-rule.md) |
| GET | `/repos/{owner}/{repo}/forks` | List forks | [View](../operations/repos-list-forks.md) |
| POST | `/repos/{owner}/{repo}/forks` | Create a fork | [View](../operations/repos-create-fork.md) |
| GET | `/repos/{owner}/{repo}/hooks` | List repository webhooks | [View](../operations/repos-list-webhooks.md) |
| POST | `/repos/{owner}/{repo}/hooks` | Create a repository webhook | [View](../operations/repos-create-webhook.md) |
| GET | `/repos/{owner}/{repo}/hooks/{hook_id}` | Get a repository webhook | [View](../operations/repos-get-webhook.md) |
| DELETE | `/repos/{owner}/{repo}/hooks/{hook_id}` | Delete a repository webhook | [View](../operations/repos-delete-webhook.md) |
| PATCH | `/repos/{owner}/{repo}/hooks/{hook_id}` | Update a repository webhook | [View](../operations/repos-update-webhook.md) |
| GET | `/repos/{owner}/{repo}/hooks/{hook_id}/config` | Get a webhook configuration for a repository | [View](../operations/repos-get-webhook-config-for-repo.md) |
| PATCH | `/repos/{owner}/{repo}/hooks/{hook_id}/config` | Update a webhook configuration for a repository | [View](../operations/repos-update-webhook-config-for-repo.md) |
| GET | `/repos/{owner}/{repo}/hooks/{hook_id}/deliveries` | List deliveries for a repository webhook | [View](../operations/repos-list-webhook-deliveries.md) |
| GET | `/repos/{owner}/{repo}/hooks/{hook_id}/deliveries/{delivery_id}` | Get a delivery for a repository webhook | [View](../operations/repos-get-webhook-delivery.md) |
| POST | `/repos/{owner}/{repo}/hooks/{hook_id}/deliveries/{delivery_id}/attempts` | Redeliver a delivery for a repository webhook | [View](../operations/repos-redeliver-webhook-delivery.md) |
| POST | `/repos/{owner}/{repo}/hooks/{hook_id}/pings` | Ping a repository webhook | [View](../operations/repos-ping-webhook.md) |
| POST | `/repos/{owner}/{repo}/hooks/{hook_id}/tests` | Test the push repository webhook | [View](../operations/repos-test-push-webhook.md) |
| GET | `/repos/{owner}/{repo}/immutable-releases` | Check if immutable releases are enabled for a repository | [View](../operations/repos-check-immutable-releases.md) |
| PUT | `/repos/{owner}/{repo}/immutable-releases` | Enable immutable releases | [View](../operations/repos-enable-immutable-releases.md) |
| DELETE | `/repos/{owner}/{repo}/immutable-releases` | Disable immutable releases | [View](../operations/repos-disable-immutable-releases.md) |
| GET | `/repos/{owner}/{repo}/invitations` | List repository invitations | [View](../operations/repos-list-invitations.md) |
| DELETE | `/repos/{owner}/{repo}/invitations/{invitation_id}` | Delete a repository invitation | [View](../operations/repos-delete-invitation.md) |
| PATCH | `/repos/{owner}/{repo}/invitations/{invitation_id}` | Update a repository invitation | [View](../operations/repos-update-invitation.md) |
| GET | `/repos/{owner}/{repo}/keys` | List deploy keys | [View](../operations/repos-list-deploy-keys.md) |
| POST | `/repos/{owner}/{repo}/keys` | Create a deploy key | [View](../operations/repos-create-deploy-key.md) |
| GET | `/repos/{owner}/{repo}/keys/{key_id}` | Get a deploy key | [View](../operations/repos-get-deploy-key.md) |
| DELETE | `/repos/{owner}/{repo}/keys/{key_id}` | Delete a deploy key | [View](../operations/repos-delete-deploy-key.md) |
| GET | `/repos/{owner}/{repo}/languages` | List repository languages | [View](../operations/repos-list-languages.md) |
| POST | `/repos/{owner}/{repo}/merge-upstream` | Sync a fork branch with the upstream repository | [View](../operations/repos-merge-upstream.md) |
| POST | `/repos/{owner}/{repo}/merges` | Merge a branch | [View](../operations/repos-merge.md) |
| GET | `/repos/{owner}/{repo}/pages` | Get a GitHub Pages site | [View](../operations/repos-get-pages.md) |
| PUT | `/repos/{owner}/{repo}/pages` | Update information about a GitHub Pages site | [View](../operations/repos-update-information-about-pages-site.md) |
| POST | `/repos/{owner}/{repo}/pages` | Create a GitHub Pages site | [View](../operations/repos-create-pages-site.md) |
| DELETE | `/repos/{owner}/{repo}/pages` | Delete a GitHub Pages site | [View](../operations/repos-delete-pages-site.md) |
| GET | `/repos/{owner}/{repo}/pages/builds` | List GitHub Pages builds | [View](../operations/repos-list-pages-builds.md) |
| POST | `/repos/{owner}/{repo}/pages/builds` | Request a GitHub Pages build | [View](../operations/repos-request-pages-build.md) |
| GET | `/repos/{owner}/{repo}/pages/builds/latest` | Get latest Pages build | [View](../operations/repos-get-latest-pages-build.md) |
| GET | `/repos/{owner}/{repo}/pages/builds/{build_id}` | Get GitHub Pages build | [View](../operations/repos-get-pages-build.md) |
| POST | `/repos/{owner}/{repo}/pages/deployments` | Create a GitHub Pages deployment | [View](../operations/repos-create-pages-deployment.md) |
| GET | `/repos/{owner}/{repo}/pages/deployments/{pages_deployment_id}` | Get the status of a GitHub Pages deployment | [View](../operations/repos-get-pages-deployment.md) |
| POST | `/repos/{owner}/{repo}/pages/deployments/{pages_deployment_id}/cancel` | Cancel a GitHub Pages deployment | [View](../operations/repos-cancel-pages-deployment.md) |
| GET | `/repos/{owner}/{repo}/pages/health` | Get a DNS health check for GitHub Pages | [View](../operations/repos-get-pages-health-check.md) |
| GET | `/repos/{owner}/{repo}/private-vulnerability-reporting` | Check if private vulnerability reporting is enabled for a repository | [View](../operations/repos-check-private-vulnerability-reporting.md) |
| PUT | `/repos/{owner}/{repo}/private-vulnerability-reporting` | Enable private vulnerability reporting for a repository | [View](../operations/repos-enable-private-vulnerability-reporting.md) |
| DELETE | `/repos/{owner}/{repo}/private-vulnerability-reporting` | Disable private vulnerability reporting for a repository | [View](../operations/repos-disable-private-vulnerability-reporting.md) |
| GET | `/repos/{owner}/{repo}/properties/values` | Get all custom property values for a repository | [View](../operations/repos-custom-properties-for-repos-get-repository-values.md) |
| PATCH | `/repos/{owner}/{repo}/properties/values` | Create or update custom property values for a repository | [View](../operations/repos-custom-properties-for-repos-create-or-update-repository-values.md) |
| GET | `/repos/{owner}/{repo}/readme` | Get a repository README | [View](../operations/repos-get-readme.md) |
| GET | `/repos/{owner}/{repo}/readme/{dir}` | Get a repository README for a directory | [View](../operations/repos-get-readme-in-directory.md) |
| GET | `/repos/{owner}/{repo}/releases` | List releases | [View](../operations/repos-list-releases.md) |
| POST | `/repos/{owner}/{repo}/releases` | Create a release | [View](../operations/repos-create-release.md) |
| GET | `/repos/{owner}/{repo}/releases/assets/{asset_id}` | Get a release asset | [View](../operations/repos-get-release-asset.md) |
| DELETE | `/repos/{owner}/{repo}/releases/assets/{asset_id}` | Delete a release asset | [View](../operations/repos-delete-release-asset.md) |
| PATCH | `/repos/{owner}/{repo}/releases/assets/{asset_id}` | Update a release asset | [View](../operations/repos-update-release-asset.md) |
| POST | `/repos/{owner}/{repo}/releases/generate-notes` | Generate release notes content for a release | [View](../operations/repos-generate-release-notes.md) |
| GET | `/repos/{owner}/{repo}/releases/latest` | Get the latest release | [View](../operations/repos-get-latest-release.md) |
| GET | `/repos/{owner}/{repo}/releases/tags/{tag}` | Get a release by tag name | [View](../operations/repos-get-release-by-tag.md) |
| GET | `/repos/{owner}/{repo}/releases/{release_id}` | Get a release | [View](../operations/repos-get-release.md) |
| DELETE | `/repos/{owner}/{repo}/releases/{release_id}` | Delete a release | [View](../operations/repos-delete-release.md) |
| PATCH | `/repos/{owner}/{repo}/releases/{release_id}` | Update a release | [View](../operations/repos-update-release.md) |
| GET | `/repos/{owner}/{repo}/releases/{release_id}/assets` | List release assets | [View](../operations/repos-list-release-assets.md) |
| POST | `/repos/{owner}/{repo}/releases/{release_id}/assets` | Upload a release asset | [View](../operations/repos-upload-release-asset.md) |
| GET | `/repos/{owner}/{repo}/rules/branches/{branch}` | Get rules for a branch | [View](../operations/repos-get-branch-rules.md) |
| GET | `/repos/{owner}/{repo}/rulesets` | Get all repository rulesets | [View](../operations/repos-get-repo-rulesets.md) |
| POST | `/repos/{owner}/{repo}/rulesets` | Create a repository ruleset | [View](../operations/repos-create-repo-ruleset.md) |
| GET | `/repos/{owner}/{repo}/rulesets/rule-suites` | List repository rule suites | [View](../operations/repos-get-repo-rule-suites.md) |
| GET | `/repos/{owner}/{repo}/rulesets/rule-suites/{rule_suite_id}` | Get a repository rule suite | [View](../operations/repos-get-repo-rule-suite.md) |
| GET | `/repos/{owner}/{repo}/rulesets/{ruleset_id}` | Get a repository ruleset | [View](../operations/repos-get-repo-ruleset.md) |
| PUT | `/repos/{owner}/{repo}/rulesets/{ruleset_id}` | Update a repository ruleset | [View](../operations/repos-update-repo-ruleset.md) |
| DELETE | `/repos/{owner}/{repo}/rulesets/{ruleset_id}` | Delete a repository ruleset | [View](../operations/repos-delete-repo-ruleset.md) |
| GET | `/repos/{owner}/{repo}/rulesets/{ruleset_id}/history` | Get repository ruleset history | [View](../operations/repos-get-repo-ruleset-history.md) |
| GET | `/repos/{owner}/{repo}/rulesets/{ruleset_id}/history/{version_id}` | Get repository ruleset version | [View](../operations/repos-get-repo-ruleset-version.md) |
| GET | `/repos/{owner}/{repo}/stats/code_frequency` | Get the weekly commit activity | [View](../operations/repos-get-code-frequency-stats.md) |
| GET | `/repos/{owner}/{repo}/stats/commit_activity` | Get the last year of commit activity | [View](../operations/repos-get-commit-activity-stats.md) |
| GET | `/repos/{owner}/{repo}/stats/contributors` | Get all contributor commit activity | [View](../operations/repos-get-contributors-stats.md) |
| GET | `/repos/{owner}/{repo}/stats/participation` | Get the weekly commit count | [View](../operations/repos-get-participation-stats.md) |
| GET | `/repos/{owner}/{repo}/stats/punch_card` | Get the hourly commit count for each day | [View](../operations/repos-get-punch-card-stats.md) |
| POST | `/repos/{owner}/{repo}/statuses/{sha}` | Create a commit status | [View](../operations/repos-create-commit-status.md) |
| GET | `/repos/{owner}/{repo}/tags` | List repository tags | [View](../operations/repos-list-tags.md) |
| GET | `/repos/{owner}/{repo}/tags/protection` | Closing down - List tag protection states for a repository | [View](../operations/repos-list-tag-protection.md) |
| POST | `/repos/{owner}/{repo}/tags/protection` | Closing down - Create a tag protection state for a repository | [View](../operations/repos-create-tag-protection.md) |
| DELETE | `/repos/{owner}/{repo}/tags/protection/{tag_protection_id}` | Closing down - Delete a tag protection state for a repository | [View](../operations/repos-delete-tag-protection.md) |
| GET | `/repos/{owner}/{repo}/tarball/{ref}` | Download a repository archive (tar) | [View](../operations/repos-download-tarball-archive.md) |
| GET | `/repos/{owner}/{repo}/teams` | List repository teams | [View](../operations/repos-list-teams.md) |
| GET | `/repos/{owner}/{repo}/topics` | Get all repository topics | [View](../operations/repos-get-all-topics.md) |
| PUT | `/repos/{owner}/{repo}/topics` | Replace all repository topics | [View](../operations/repos-replace-all-topics.md) |
| GET | `/repos/{owner}/{repo}/traffic/clones` | Get repository clones | [View](../operations/repos-get-clones.md) |
| GET | `/repos/{owner}/{repo}/traffic/popular/paths` | Get top referral paths | [View](../operations/repos-get-top-paths.md) |
| GET | `/repos/{owner}/{repo}/traffic/popular/referrers` | Get top referral sources | [View](../operations/repos-get-top-referrers.md) |
| GET | `/repos/{owner}/{repo}/traffic/views` | Get page views | [View](../operations/repos-get-views.md) |
| POST | `/repos/{owner}/{repo}/transfer` | Transfer a repository | [View](../operations/repos-transfer.md) |
| GET | `/repos/{owner}/{repo}/vulnerability-alerts` | Check if vulnerability alerts are enabled for a repository | [View](../operations/repos-check-vulnerability-alerts.md) |
| PUT | `/repos/{owner}/{repo}/vulnerability-alerts` | Enable vulnerability alerts | [View](../operations/repos-enable-vulnerability-alerts.md) |
| DELETE | `/repos/{owner}/{repo}/vulnerability-alerts` | Disable vulnerability alerts | [View](../operations/repos-disable-vulnerability-alerts.md) |
| GET | `/repos/{owner}/{repo}/zipball/{ref}` | Download a repository archive (zip) | [View](../operations/repos-download-zipball-archive.md) |
| POST | `/repos/{template_owner}/{template_repo}/generate` | Create a repository using a template | [View](../operations/repos-create-using-template.md) |
| GET | `/repositories` | List public repositories | [View](../operations/repos-list-public.md) |
| GET | `/user/repos` | List repositories for the authenticated user | [View](../operations/repos-list-for-authenticated-user.md) |
| POST | `/user/repos` | Create a repository for the authenticated user | [View](../operations/repos-create-for-authenticated-user.md) |
| GET | `/user/repository_invitations` | List repository invitations for the authenticated user | [View](../operations/repos-list-invitations-for-authenticated-user.md) |
| DELETE | `/user/repository_invitations/{invitation_id}` | Decline a repository invitation | [View](../operations/repos-decline-invitation-for-authenticated-user.md) |
| PATCH | `/user/repository_invitations/{invitation_id}` | Accept a repository invitation | [View](../operations/repos-accept-invitation-for-authenticated-user.md) |
| GET | `/users/{username}/repos` | List repositories for a user | [View](../operations/repos-list-for-user.md) |
