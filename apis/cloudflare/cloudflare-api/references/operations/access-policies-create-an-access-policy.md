# POST /accounts/{account_id}/access/apps/{app_id}/policies

**Resource:** [Access application-scoped policies](../resources/Access-application-scoped-policies.md)
**Create an Access application policy**
**Operation ID:** `access-policies-create-an-access-policy`

Creates a policy applying exclusive to a single application that defines the users or groups who can reach it. We recommend creating a reusable policy instead and subsequently referencing its ID in the application's 'policies' array.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `app_id` | path | access_uuid | Yes | The application ID. |
| `account_id` | path | access_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [access_app_policy_request](../schemas/access/access-app-policy-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Create an Access application policy response. |
| 4XX | Create an Access application policy response failure. |

**Success Response Schema:**

[access_app-policies_components-schemas-single_response](../schemas/access/access-app-policies-components-schemas-single-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
