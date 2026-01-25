# POST /accounts/{account_id}/intel/miscategorization

**Resource:** [Miscategorization](../resources/Miscategorization.md)
**Create Miscategorization**
**Operation ID:** `miscategorization-create-miscategorization`

Allows you to submit requests to change a domain’s category.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | intel_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [intel_miscategorization](../schemas/intel/intel-miscategorization.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Create Miscategorization response. |
| 4XX | Create Miscategorization response failure. |

**Success Response Schema:**

[intel_api-response-single](../schemas/intel/intel-api-response-single.md)

## Security

- **api_token**
- **api_email**
- **api_key**
