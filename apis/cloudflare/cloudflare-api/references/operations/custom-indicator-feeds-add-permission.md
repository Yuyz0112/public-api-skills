# PUT /accounts/{account_id}/intel/indicator-feeds/permissions/add

**Resource:** [Custom Indicator Feeds](../resources/Custom-Indicator-Feeds.md)
**Grant permission to indicator feed**
**Operation ID:** `custom-indicator-feeds-add-permission`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | custom-indicator-feeds_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [custom-indicator-feeds_permissions_request](../schemas/custom-indicator-feeds/custom-indicator-feeds-permissions-request.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Get indicator feed metadata |
| 4XX | Get indicator feeds response failure |

**Success Response Schema:**

[custom-indicator-feeds_permissions_response](../schemas/custom-indicator-feeds/custom-indicator-feeds-permissions-response.md)

## Security

- **api_email**
- **api_key**
