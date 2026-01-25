# hosted-compute

Manage hosted compute networking resources.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/orgs/{org}/settings/network-configurations` | List hosted compute network configurations for an organization | [View](../operations/hosted-compute-list-network-configurations-for-org.md) |
| POST | `/orgs/{org}/settings/network-configurations` | Create a hosted compute network configuration for an organization | [View](../operations/hosted-compute-create-network-configuration-for-org.md) |
| GET | `/orgs/{org}/settings/network-configurations/{network_configuration_id}` | Get a hosted compute network configuration for an organization | [View](../operations/hosted-compute-get-network-configuration-for-org.md) |
| DELETE | `/orgs/{org}/settings/network-configurations/{network_configuration_id}` | Delete a hosted compute network configuration from an organization | [View](../operations/hosted-compute-delete-network-configuration-from-org.md) |
| PATCH | `/orgs/{org}/settings/network-configurations/{network_configuration_id}` | Update a hosted compute network configuration for an organization | [View](../operations/hosted-compute-update-network-configuration-for-org.md) |
| GET | `/orgs/{org}/settings/network-settings/{network_settings_id}` | Get a hosted compute network settings resource for an organization | [View](../operations/hosted-compute-get-network-settings-for-org.md) |
