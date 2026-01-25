# GET /accounts/{account_id}/access/apps/{app_id}/policies/{policy_id}

**Resource:** [Access application-scoped policies](../resources/Access-application-scoped-policies.md)
**Get an Access application policy**
**Operation ID:** `access-policies-get-an-access-policy`

Fetches a single Access policy configured for an application. Returns both exclusively owned and reusable policies used by the application.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_uuid | Yes | The application ID. |
| `policy_id` | path | access_uuid | Yes | The policy ID. |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get an Access policy response. |
| 4XX | Get an Access policy response failure. |

**Success Response Schema:**

[access_app-policies_components-schemas-single_response](../schemas/access/access-app-policies-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
