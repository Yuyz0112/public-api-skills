# apps

Information for integrations and installations.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/app` | Get the authenticated app | [View](../operations/apps-get-authenticated.md) |
| POST | `/app-manifests/{code}/conversions` | Create a GitHub App from a manifest | [View](../operations/apps-create-from-manifest.md) |
| GET | `/app/hook/config` | Get a webhook configuration for an app | [View](../operations/apps-get-webhook-config-for-app.md) |
| PATCH | `/app/hook/config` | Update a webhook configuration for an app | [View](../operations/apps-update-webhook-config-for-app.md) |
| GET | `/app/hook/deliveries` | List deliveries for an app webhook | [View](../operations/apps-list-webhook-deliveries.md) |
| GET | `/app/hook/deliveries/{delivery_id}` | Get a delivery for an app webhook | [View](../operations/apps-get-webhook-delivery.md) |
| POST | `/app/hook/deliveries/{delivery_id}/attempts` | Redeliver a delivery for an app webhook | [View](../operations/apps-redeliver-webhook-delivery.md) |
| GET | `/app/installation-requests` | List installation requests for the authenticated app | [View](../operations/apps-list-installation-requests-for-authenticated-app.md) |
| GET | `/app/installations` | List installations for the authenticated app | [View](../operations/apps-list-installations.md) |
| GET | `/app/installations/{installation_id}` | Get an installation for the authenticated app | [View](../operations/apps-get-installation.md) |
| DELETE | `/app/installations/{installation_id}` | Delete an installation for the authenticated app | [View](../operations/apps-delete-installation.md) |
| POST | `/app/installations/{installation_id}/access_tokens` | Create an installation access token for an app | [View](../operations/apps-create-installation-access-token.md) |
| PUT | `/app/installations/{installation_id}/suspended` | Suspend an app installation | [View](../operations/apps-suspend-installation.md) |
| DELETE | `/app/installations/{installation_id}/suspended` | Unsuspend an app installation | [View](../operations/apps-unsuspend-installation.md) |
| DELETE | `/applications/{client_id}/grant` | Delete an app authorization | [View](../operations/apps-delete-authorization.md) |
| POST | `/applications/{client_id}/token` | Check a token | [View](../operations/apps-check-token.md) |
| DELETE | `/applications/{client_id}/token` | Delete an app token | [View](../operations/apps-delete-token.md) |
| PATCH | `/applications/{client_id}/token` | Reset a token | [View](../operations/apps-reset-token.md) |
| POST | `/applications/{client_id}/token/scoped` | Create a scoped access token | [View](../operations/apps-scope-token.md) |
| GET | `/apps/{app_slug}` | Get an app | [View](../operations/apps-get-by-slug.md) |
| GET | `/installation/repositories` | List repositories accessible to the app installation | [View](../operations/apps-list-repos-accessible-to-installation.md) |
| DELETE | `/installation/token` | Revoke an installation access token | [View](../operations/apps-revoke-installation-access-token.md) |
| GET | `/marketplace_listing/accounts/{account_id}` | Get a subscription plan for an account | [View](../operations/apps-get-subscription-plan-for-account.md) |
| GET | `/marketplace_listing/plans` | List plans | [View](../operations/apps-list-plans.md) |
| GET | `/marketplace_listing/plans/{plan_id}/accounts` | List accounts for a plan | [View](../operations/apps-list-accounts-for-plan.md) |
| GET | `/marketplace_listing/stubbed/accounts/{account_id}` | Get a subscription plan for an account (stubbed) | [View](../operations/apps-get-subscription-plan-for-account-stubbed.md) |
| GET | `/marketplace_listing/stubbed/plans` | List plans (stubbed) | [View](../operations/apps-list-plans-stubbed.md) |
| GET | `/marketplace_listing/stubbed/plans/{plan_id}/accounts` | List accounts for a plan (stubbed) | [View](../operations/apps-list-accounts-for-plan-stubbed.md) |
| GET | `/orgs/{org}/installation` | Get an organization installation for the authenticated app | [View](../operations/apps-get-org-installation.md) |
| GET | `/repos/{owner}/{repo}/installation` | Get a repository installation for the authenticated app | [View](../operations/apps-get-repo-installation.md) |
| GET | `/user/installations` | List app installations accessible to the user access token | [View](../operations/apps-list-installations-for-authenticated-user.md) |
| GET | `/user/installations/{installation_id}/repositories` | List repositories accessible to the user access token | [View](../operations/apps-list-installation-repos-for-authenticated-user.md) |
| PUT | `/user/installations/{installation_id}/repositories/{repository_id}` | Add a repository to an app installation | [View](../operations/apps-add-repo-to-installation-for-authenticated-user.md) |
| DELETE | `/user/installations/{installation_id}/repositories/{repository_id}` | Remove a repository from an app installation | [View](../operations/apps-remove-repo-from-installation-for-authenticated-user.md) |
| GET | `/user/marketplace_purchases` | List subscriptions for the authenticated user | [View](../operations/apps-list-subscriptions-for-authenticated-user.md) |
| GET | `/user/marketplace_purchases/stubbed` | List subscriptions for the authenticated user (stubbed) | [View](../operations/apps-list-subscriptions-for-authenticated-user-stubbed.md) |
| GET | `/users/{username}/installation` | Get a user installation for the authenticated app | [View](../operations/apps-get-user-installation.md) |
