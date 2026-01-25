# orgs

Interact with organizations.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/organizations` | List organizations | [View](../operations/orgs-list.md) |
| GET | `/orgs/{org}` | Get an organization | [View](../operations/orgs-get.md) |
| DELETE | `/orgs/{org}` | Delete an organization | [View](../operations/orgs-delete.md) |
| PATCH | `/orgs/{org}` | Update an organization | [View](../operations/orgs-update.md) |
| POST | `/orgs/{org}/artifacts/metadata/deployment-record` | Create an artifact deployment record | [View](../operations/orgs-create-artifact-deployment-record.md) |
| POST | `/orgs/{org}/artifacts/metadata/deployment-record/cluster/{cluster}` | Set cluster deployment records | [View](../operations/orgs-set-cluster-deployment-records.md) |
| POST | `/orgs/{org}/artifacts/metadata/storage-record` | Create artifact metadata storage record | [View](../operations/orgs-create-artifact-storage-record.md) |
| GET | `/orgs/{org}/artifacts/{subject_digest}/metadata/deployment-records` | List artifact deployment records | [View](../operations/orgs-list-artifact-deployment-records.md) |
| GET | `/orgs/{org}/artifacts/{subject_digest}/metadata/storage-records` | List artifact storage records | [View](../operations/orgs-list-artifact-storage-records.md) |
| POST | `/orgs/{org}/attestations/bulk-list` | List attestations by bulk subject digests | [View](../operations/orgs-list-attestations-bulk.md) |
| POST | `/orgs/{org}/attestations/delete-request` | Delete attestations in bulk | [View](../operations/orgs-delete-attestations-bulk.md) |
| DELETE | `/orgs/{org}/attestations/digest/{subject_digest}` | Delete attestations by subject digest | [View](../operations/orgs-delete-attestations-by-subject-digest.md) |
| GET | `/orgs/{org}/attestations/repositories` | List attestation repositories | [View](../operations/orgs-list-attestation-repositories.md) |
| DELETE | `/orgs/{org}/attestations/{attestation_id}` | Delete attestations by ID | [View](../operations/orgs-delete-attestations-by-id.md) |
| GET | `/orgs/{org}/attestations/{subject_digest}` | List attestations | [View](../operations/orgs-list-attestations.md) |
| GET | `/orgs/{org}/blocks` | List users blocked by an organization | [View](../operations/orgs-list-blocked-users.md) |
| GET | `/orgs/{org}/blocks/{username}` | Check if a user is blocked by an organization | [View](../operations/orgs-check-blocked-user.md) |
| PUT | `/orgs/{org}/blocks/{username}` | Block a user from an organization | [View](../operations/orgs-block-user.md) |
| DELETE | `/orgs/{org}/blocks/{username}` | Unblock a user from an organization | [View](../operations/orgs-unblock-user.md) |
| GET | `/orgs/{org}/failed_invitations` | List failed organization invitations | [View](../operations/orgs-list-failed-invitations.md) |
| GET | `/orgs/{org}/hooks` | List organization webhooks | [View](../operations/orgs-list-webhooks.md) |
| POST | `/orgs/{org}/hooks` | Create an organization webhook | [View](../operations/orgs-create-webhook.md) |
| GET | `/orgs/{org}/hooks/{hook_id}` | Get an organization webhook | [View](../operations/orgs-get-webhook.md) |
| DELETE | `/orgs/{org}/hooks/{hook_id}` | Delete an organization webhook | [View](../operations/orgs-delete-webhook.md) |
| PATCH | `/orgs/{org}/hooks/{hook_id}` | Update an organization webhook | [View](../operations/orgs-update-webhook.md) |
| GET | `/orgs/{org}/hooks/{hook_id}/config` | Get a webhook configuration for an organization | [View](../operations/orgs-get-webhook-config-for-org.md) |
| PATCH | `/orgs/{org}/hooks/{hook_id}/config` | Update a webhook configuration for an organization | [View](../operations/orgs-update-webhook-config-for-org.md) |
| GET | `/orgs/{org}/hooks/{hook_id}/deliveries` | List deliveries for an organization webhook | [View](../operations/orgs-list-webhook-deliveries.md) |
| GET | `/orgs/{org}/hooks/{hook_id}/deliveries/{delivery_id}` | Get a webhook delivery for an organization webhook | [View](../operations/orgs-get-webhook-delivery.md) |
| POST | `/orgs/{org}/hooks/{hook_id}/deliveries/{delivery_id}/attempts` | Redeliver a delivery for an organization webhook | [View](../operations/orgs-redeliver-webhook-delivery.md) |
| POST | `/orgs/{org}/hooks/{hook_id}/pings` | Ping an organization webhook | [View](../operations/orgs-ping-webhook.md) |
| GET | `/orgs/{org}/insights/api/route-stats/{actor_type}/{actor_id}` | Get route stats by actor | [View](../operations/api-insights-get-route-stats-by-actor.md) |
| GET | `/orgs/{org}/insights/api/subject-stats` | Get subject stats | [View](../operations/api-insights-get-subject-stats.md) |
| GET | `/orgs/{org}/insights/api/summary-stats` | Get summary stats | [View](../operations/api-insights-get-summary-stats.md) |
| GET | `/orgs/{org}/insights/api/summary-stats/users/{user_id}` | Get summary stats by user | [View](../operations/api-insights-get-summary-stats-by-user.md) |
| GET | `/orgs/{org}/insights/api/summary-stats/{actor_type}/{actor_id}` | Get summary stats by actor | [View](../operations/api-insights-get-summary-stats-by-actor.md) |
| GET | `/orgs/{org}/insights/api/time-stats` | Get time stats | [View](../operations/api-insights-get-time-stats.md) |
| GET | `/orgs/{org}/insights/api/time-stats/users/{user_id}` | Get time stats by user | [View](../operations/api-insights-get-time-stats-by-user.md) |
| GET | `/orgs/{org}/insights/api/time-stats/{actor_type}/{actor_id}` | Get time stats by actor | [View](../operations/api-insights-get-time-stats-by-actor.md) |
| GET | `/orgs/{org}/insights/api/user-stats/{user_id}` | Get user stats | [View](../operations/api-insights-get-user-stats.md) |
| GET | `/orgs/{org}/installations` | List app installations for an organization | [View](../operations/orgs-list-app-installations.md) |
| GET | `/orgs/{org}/invitations` | List pending organization invitations | [View](../operations/orgs-list-pending-invitations.md) |
| POST | `/orgs/{org}/invitations` | Create an organization invitation | [View](../operations/orgs-create-invitation.md) |
| DELETE | `/orgs/{org}/invitations/{invitation_id}` | Cancel an organization invitation | [View](../operations/orgs-cancel-invitation.md) |
| GET | `/orgs/{org}/invitations/{invitation_id}/teams` | List organization invitation teams | [View](../operations/orgs-list-invitation-teams.md) |
| GET | `/orgs/{org}/issue-types` | List issue types for an organization | [View](../operations/orgs-list-issue-types.md) |
| POST | `/orgs/{org}/issue-types` | Create issue type for an organization | [View](../operations/orgs-create-issue-type.md) |
| PUT | `/orgs/{org}/issue-types/{issue_type_id}` | Update issue type for an organization | [View](../operations/orgs-update-issue-type.md) |
| DELETE | `/orgs/{org}/issue-types/{issue_type_id}` | Delete issue type for an organization | [View](../operations/orgs-delete-issue-type.md) |
| GET | `/orgs/{org}/members` | List organization members | [View](../operations/orgs-list-members.md) |
| GET | `/orgs/{org}/members/{username}` | Check organization membership for a user | [View](../operations/orgs-check-membership-for-user.md) |
| DELETE | `/orgs/{org}/members/{username}` | Remove an organization member | [View](../operations/orgs-remove-member.md) |
| GET | `/orgs/{org}/memberships/{username}` | Get organization membership for a user | [View](../operations/orgs-get-membership-for-user.md) |
| PUT | `/orgs/{org}/memberships/{username}` | Set organization membership for a user | [View](../operations/orgs-set-membership-for-user.md) |
| DELETE | `/orgs/{org}/memberships/{username}` | Remove organization membership for a user | [View](../operations/orgs-remove-membership-for-user.md) |
| GET | `/orgs/{org}/organization-roles` | Get all organization roles for an organization | [View](../operations/orgs-list-org-roles.md) |
| DELETE | `/orgs/{org}/organization-roles/teams/{team_slug}` | Remove all organization roles for a team | [View](../operations/orgs-revoke-all-org-roles-team.md) |
| PUT | `/orgs/{org}/organization-roles/teams/{team_slug}/{role_id}` | Assign an organization role to a team | [View](../operations/orgs-assign-team-to-org-role.md) |
| DELETE | `/orgs/{org}/organization-roles/teams/{team_slug}/{role_id}` | Remove an organization role from a team | [View](../operations/orgs-revoke-org-role-team.md) |
| DELETE | `/orgs/{org}/organization-roles/users/{username}` | Remove all organization roles for a user | [View](../operations/orgs-revoke-all-org-roles-user.md) |
| PUT | `/orgs/{org}/organization-roles/users/{username}/{role_id}` | Assign an organization role to a user | [View](../operations/orgs-assign-user-to-org-role.md) |
| DELETE | `/orgs/{org}/organization-roles/users/{username}/{role_id}` | Remove an organization role from a user | [View](../operations/orgs-revoke-org-role-user.md) |
| GET | `/orgs/{org}/organization-roles/{role_id}` | Get an organization role | [View](../operations/orgs-get-org-role.md) |
| GET | `/orgs/{org}/organization-roles/{role_id}/teams` | List teams that are assigned to an organization role | [View](../operations/orgs-list-org-role-teams.md) |
| GET | `/orgs/{org}/organization-roles/{role_id}/users` | List users that are assigned to an organization role | [View](../operations/orgs-list-org-role-users.md) |
| GET | `/orgs/{org}/outside_collaborators` | List outside collaborators for an organization | [View](../operations/orgs-list-outside-collaborators.md) |
| PUT | `/orgs/{org}/outside_collaborators/{username}` | Convert an organization member to outside collaborator | [View](../operations/orgs-convert-member-to-outside-collaborator.md) |
| DELETE | `/orgs/{org}/outside_collaborators/{username}` | Remove outside collaborator from an organization | [View](../operations/orgs-remove-outside-collaborator.md) |
| GET | `/orgs/{org}/personal-access-token-requests` | List requests to access organization resources with fine-grained personal access tokens | [View](../operations/orgs-list-pat-grant-requests.md) |
| POST | `/orgs/{org}/personal-access-token-requests` | Review requests to access organization resources with fine-grained personal access tokens | [View](../operations/orgs-review-pat-grant-requests-in-bulk.md) |
| POST | `/orgs/{org}/personal-access-token-requests/{pat_request_id}` | Review a request to access organization resources with a fine-grained personal access token | [View](../operations/orgs-review-pat-grant-request.md) |
| GET | `/orgs/{org}/personal-access-token-requests/{pat_request_id}/repositories` | List repositories requested to be accessed by a fine-grained personal access token | [View](../operations/orgs-list-pat-grant-request-repositories.md) |
| GET | `/orgs/{org}/personal-access-tokens` | List fine-grained personal access tokens with access to organization resources | [View](../operations/orgs-list-pat-grants.md) |
| POST | `/orgs/{org}/personal-access-tokens` | Update the access to organization resources via fine-grained personal access tokens | [View](../operations/orgs-update-pat-accesses.md) |
| POST | `/orgs/{org}/personal-access-tokens/{pat_id}` | Update the access a fine-grained personal access token has to organization resources | [View](../operations/orgs-update-pat-access.md) |
| GET | `/orgs/{org}/personal-access-tokens/{pat_id}/repositories` | List repositories a fine-grained personal access token has access to | [View](../operations/orgs-list-pat-grant-repositories.md) |
| GET | `/orgs/{org}/properties/schema` | Get all custom properties for an organization | [View](../operations/orgs-custom-properties-for-repos-get-organization-definitions.md) |
| PATCH | `/orgs/{org}/properties/schema` | Create or update custom properties for an organization | [View](../operations/orgs-custom-properties-for-repos-create-or-update-organization-definitions.md) |
| GET | `/orgs/{org}/properties/schema/{custom_property_name}` | Get a custom property for an organization | [View](../operations/orgs-custom-properties-for-repos-get-organization-definition.md) |
| PUT | `/orgs/{org}/properties/schema/{custom_property_name}` | Create or update a custom property for an organization | [View](../operations/orgs-custom-properties-for-repos-create-or-update-organization-definition.md) |
| DELETE | `/orgs/{org}/properties/schema/{custom_property_name}` | Remove a custom property for an organization | [View](../operations/orgs-custom-properties-for-repos-delete-organization-definition.md) |
| GET | `/orgs/{org}/properties/values` | List custom property values for organization repositories | [View](../operations/orgs-custom-properties-for-repos-get-organization-values.md) |
| PATCH | `/orgs/{org}/properties/values` | Create or update custom property values for organization repositories | [View](../operations/orgs-custom-properties-for-repos-create-or-update-organization-values.md) |
| GET | `/orgs/{org}/public_members` | List public organization members | [View](../operations/orgs-list-public-members.md) |
| GET | `/orgs/{org}/public_members/{username}` | Check public organization membership for a user | [View](../operations/orgs-check-public-membership-for-user.md) |
| PUT | `/orgs/{org}/public_members/{username}` | Set public organization membership for the authenticated user | [View](../operations/orgs-set-public-membership-for-authenticated-user.md) |
| DELETE | `/orgs/{org}/public_members/{username}` | Remove public organization membership for the authenticated user | [View](../operations/orgs-remove-public-membership-for-authenticated-user.md) |
| GET | `/orgs/{org}/rulesets/{ruleset_id}/history` | Get organization ruleset history | [View](../operations/orgs-get-org-ruleset-history.md) |
| GET | `/orgs/{org}/rulesets/{ruleset_id}/history/{version_id}` | Get organization ruleset version | [View](../operations/orgs-get-org-ruleset-version.md) |
| GET | `/orgs/{org}/security-managers` | List security manager teams | [View](../operations/orgs-list-security-manager-teams.md) |
| PUT | `/orgs/{org}/security-managers/teams/{team_slug}` | Add a security manager team | [View](../operations/orgs-add-security-manager-team.md) |
| DELETE | `/orgs/{org}/security-managers/teams/{team_slug}` | Remove a security manager team | [View](../operations/orgs-remove-security-manager-team.md) |
| GET | `/orgs/{org}/settings/immutable-releases` | Get immutable releases settings for an organization | [View](../operations/orgs-get-immutable-releases-settings.md) |
| PUT | `/orgs/{org}/settings/immutable-releases` | Set immutable releases settings for an organization | [View](../operations/orgs-set-immutable-releases-settings.md) |
| GET | `/orgs/{org}/settings/immutable-releases/repositories` | List selected repositories for immutable releases enforcement | [View](../operations/orgs-get-immutable-releases-settings-repositories.md) |
| PUT | `/orgs/{org}/settings/immutable-releases/repositories` | Set selected repositories for immutable releases enforcement | [View](../operations/orgs-set-immutable-releases-settings-repositories.md) |
| PUT | `/orgs/{org}/settings/immutable-releases/repositories/{repository_id}` | Enable a selected repository for immutable releases in an organization | [View](../operations/orgs-enable-selected-repository-immutable-releases-organization.md) |
| DELETE | `/orgs/{org}/settings/immutable-releases/repositories/{repository_id}` | Disable a selected repository for immutable releases in an organization | [View](../operations/orgs-disable-selected-repository-immutable-releases-organization.md) |
| POST | `/orgs/{org}/{security_product}/{enablement}` | Enable or disable a security feature for an organization | [View](../operations/orgs-enable-or-disable-security-product-on-all-org-repos.md) |
| GET | `/user/memberships/orgs` | List organization memberships for the authenticated user | [View](../operations/orgs-list-memberships-for-authenticated-user.md) |
| GET | `/user/memberships/orgs/{org}` | Get an organization membership for the authenticated user | [View](../operations/orgs-get-membership-for-authenticated-user.md) |
| PATCH | `/user/memberships/orgs/{org}` | Update an organization membership for the authenticated user | [View](../operations/orgs-update-membership-for-authenticated-user.md) |
| GET | `/user/orgs` | List organizations for the authenticated user | [View](../operations/orgs-list-for-authenticated-user.md) |
| GET | `/users/{username}/orgs` | List organizations for a user | [View](../operations/orgs-list-for-user.md) |
