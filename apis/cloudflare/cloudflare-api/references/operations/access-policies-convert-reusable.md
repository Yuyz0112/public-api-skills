# PUT /accounts/{account_id}/access/apps/{app_id}/policies/{policy_id}/make_reusable

**Resource:** [Access application-scoped policies](../resources/Access-application-scoped-policies.md)
**Convert an Access application policy to a reusable policy**
**Operation ID:** `access-policies-convert-reusable`

Converts an application-scoped policy to a reusable policy. The policy will no longer be exclusively scoped to the application. Further updates to the policy should go through the /accounts/{account_id}/policies/{uid} endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_uuid | Yes | The application ID. |
| `policy_id` | path | access_uuid | Yes | The policy ID. |
| `account_id` | path | access_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Convert an Access application policy to a reusable policy |
| 4XX | Convert an Access application policy to a reusable policy failure. |

**Success Response Schema:**

[access_app-policies_components-schemas-response_collection](../schemas/access/access-app-policies-components-schemas-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
