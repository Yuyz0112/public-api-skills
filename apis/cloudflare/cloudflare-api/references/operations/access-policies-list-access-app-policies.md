# GET /accounts/{account_id}/access/apps/{app_id}/policies

**Resource:** [Access application-scoped policies](../resources/Access-application-scoped-policies.md)
**List Access application policies**
**Operation ID:** `access-policies-list-access-app-policies`

Lists Access policies configured for an application. Returns both exclusively scoped and reusable policies used by the application.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_uuid | Yes | The application ID. |
| `account_id` | path | access_identifier | Yes |  |
| `per_page` | query | integer | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List Access application policies response |
| 4XX | List Access application policies response failure |

**Success Response Schema:**

[access_app-policies_components-schemas-response_collection](../schemas/access/access-app-policies-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
