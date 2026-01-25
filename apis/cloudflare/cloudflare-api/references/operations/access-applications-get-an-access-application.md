# GET /accounts/{account_id}/access/apps/{app_id}

**Resource:** [Access applications](../resources/Access-applications.md)
**Get an Access application**
**Operation ID:** `access-applications-get-an-access-application`

Fetches information about an Access application.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_app_id | Yes |  |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get an Access application response |
| 4XX | Get an Access application response failure |

**Success Response Schema:**

[access_apps_components-schemas-single_response](../schemas/access/access-apps-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
