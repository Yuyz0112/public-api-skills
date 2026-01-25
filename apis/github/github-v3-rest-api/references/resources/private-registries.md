# private-registries

Manage private registry configurations.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/orgs/{org}/private-registries` | List private registries for an organization | [View](../operations/private-registries-list-org-private-registries.md) |
| POST | `/orgs/{org}/private-registries` | Create a private registry for an organization | [View](../operations/private-registries-create-org-private-registry.md) |
| GET | `/orgs/{org}/private-registries/public-key` | Get private registries public key for an organization | [View](../operations/private-registries-get-org-public-key.md) |
| GET | `/orgs/{org}/private-registries/{secret_name}` | Get a private registry for an organization | [View](../operations/private-registries-get-org-private-registry.md) |
| DELETE | `/orgs/{org}/private-registries/{secret_name}` | Delete a private registry for an organization | [View](../operations/private-registries-delete-org-private-registry.md) |
| PATCH | `/orgs/{org}/private-registries/{secret_name}` | Update a private registry for an organization | [View](../operations/private-registries-update-org-private-registry.md) |
