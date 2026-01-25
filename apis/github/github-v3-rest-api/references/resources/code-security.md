# code-security

Endpoints to manage Code security using the REST API.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/enterprises/{enterprise}/code-security/configurations` | Get code security configurations for an enterprise | [View](../operations/code-security-get-configurations-for-enterprise.md) |
| POST | `/enterprises/{enterprise}/code-security/configurations` | Create a code security configuration for an enterprise | [View](../operations/code-security-create-configuration-for-enterprise.md) |
| GET | `/enterprises/{enterprise}/code-security/configurations/defaults` | Get default code security configurations for an enterprise | [View](../operations/code-security-get-default-configurations-for-enterprise.md) |
| GET | `/enterprises/{enterprise}/code-security/configurations/{configuration_id}` | Retrieve a code security configuration of an enterprise | [View](../operations/code-security-get-single-configuration-for-enterprise.md) |
| DELETE | `/enterprises/{enterprise}/code-security/configurations/{configuration_id}` | Delete a code security configuration for an enterprise | [View](../operations/code-security-delete-configuration-for-enterprise.md) |
| PATCH | `/enterprises/{enterprise}/code-security/configurations/{configuration_id}` | Update a custom code security configuration for an enterprise | [View](../operations/code-security-update-enterprise-configuration.md) |
| POST | `/enterprises/{enterprise}/code-security/configurations/{configuration_id}/attach` | Attach an enterprise configuration to repositories | [View](../operations/code-security-attach-enterprise-configuration.md) |
| PUT | `/enterprises/{enterprise}/code-security/configurations/{configuration_id}/defaults` | Set a code security configuration as a default for an enterprise | [View](../operations/code-security-set-configuration-as-default-for-enterprise.md) |
| GET | `/enterprises/{enterprise}/code-security/configurations/{configuration_id}/repositories` | Get repositories associated with an enterprise code security configuration | [View](../operations/code-security-get-repositories-for-enterprise-configuration.md) |
| GET | `/orgs/{org}/code-security/configurations` | Get code security configurations for an organization | [View](../operations/code-security-get-configurations-for-org.md) |
| POST | `/orgs/{org}/code-security/configurations` | Create a code security configuration | [View](../operations/code-security-create-configuration.md) |
| GET | `/orgs/{org}/code-security/configurations/defaults` | Get default code security configurations | [View](../operations/code-security-get-default-configurations.md) |
| DELETE | `/orgs/{org}/code-security/configurations/detach` | Detach configurations from repositories | [View](../operations/code-security-detach-configuration.md) |
| GET | `/orgs/{org}/code-security/configurations/{configuration_id}` | Get a code security configuration | [View](../operations/code-security-get-configuration.md) |
| DELETE | `/orgs/{org}/code-security/configurations/{configuration_id}` | Delete a code security configuration | [View](../operations/code-security-delete-configuration.md) |
| PATCH | `/orgs/{org}/code-security/configurations/{configuration_id}` | Update a code security configuration | [View](../operations/code-security-update-configuration.md) |
| POST | `/orgs/{org}/code-security/configurations/{configuration_id}/attach` | Attach a configuration to repositories | [View](../operations/code-security-attach-configuration.md) |
| PUT | `/orgs/{org}/code-security/configurations/{configuration_id}/defaults` | Set a code security configuration as a default for an organization | [View](../operations/code-security-set-configuration-as-default.md) |
| GET | `/orgs/{org}/code-security/configurations/{configuration_id}/repositories` | Get repositories associated with a code security configuration | [View](../operations/code-security-get-repositories-for-configuration.md) |
| GET | `/repos/{owner}/{repo}/code-security-configuration` | Get the code security configuration associated with a repository | [View](../operations/code-security-get-configuration-for-repository.md) |
