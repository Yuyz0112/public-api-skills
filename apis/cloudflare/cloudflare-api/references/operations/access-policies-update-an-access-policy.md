# PUT /accounts/{account_id}/access/apps/{app_id}/policies/{policy_id}

**Resource:** [Access application-scoped policies](../resources/Access-application-scoped-policies.md)
**Update an Access application policy**
**Operation ID:** `access-policies-update-an-access-policy`

Updates an Access policy specific to an application. To update a reusable policy, use the /accounts/{account_id}/policies/{uid} endpoint.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_uuid | Yes | The application ID. |
| `policy_id` | path | access_uuid | Yes | The policy ID. |
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_app_policy_request](../schemas/access/access-app-policy-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update an Access application policy response. |
| 4XX | Update an Access application policy response failure. |

**Success Response Schema:**

[access_app-policies_components-schemas-single_response](../schemas/access/access-app-policies-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
