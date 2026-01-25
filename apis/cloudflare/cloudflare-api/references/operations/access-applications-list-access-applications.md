# GET /accounts/{account_id}/access/apps

**Resource:** [Access applications](../resources/Access-applications.md)
**List Access applications**
**Operation ID:** `access-applications-list-access-applications`

Lists all Access applications in an account.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | access_identifier | Yes |  |
| `name` | query | string | No |  |
| `domain` | query | string | No |  |
| `aud` | query | string | No |  |
| `target_attributes` | query | string | No |  |
| `exact` | query | boolean | No |  |
| `search` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Access applications response |
| 4XX | List Access applications response failure |

**Success Response Schema:**

[access_apps_components-schemas-response_collection](../schemas/access/access-apps-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
