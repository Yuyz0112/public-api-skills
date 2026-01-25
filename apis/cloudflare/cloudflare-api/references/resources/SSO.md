# SSO

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/accounts/{account_id}/sso_connectors` | Get all SSO connectors | [View](../operations/get-all-sso-connectors.md) |
| POST | `/accounts/{account_id}/sso_connectors` | Initialize new SSO connector | [View](../operations/init-new-sso-connector.md) |
| GET | `/accounts/{account_id}/sso_connectors/{sso_connector_id}` | Get single SSO connector | [View](../operations/get-sso-connector.md) |
| DELETE | `/accounts/{account_id}/sso_connectors/{sso_connector_id}` | Delete SSO connector | [View](../operations/delete-sso-connector.md) |
| PATCH | `/accounts/{account_id}/sso_connectors/{sso_connector_id}` | Update SSO connector state | [View](../operations/update-sso-connector-state.md) |
| POST | `/accounts/{account_id}/sso_connectors/{sso_connector_id}/begin_verification` | Begin SSO connector verification | [View](../operations/begin-sso-connector-verification.md) |
