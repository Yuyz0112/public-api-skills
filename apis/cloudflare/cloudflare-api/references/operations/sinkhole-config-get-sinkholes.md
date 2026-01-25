# GET /accounts/{account_id}/intel/sinkholes

**Resource:** [Sinkhole Config](../resources/Sinkhole-Config.md)
**List sinkholes owned by this account**
**Operation ID:** `sinkhole-config-get-sinkholes`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | intel-sinkholes_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

**Success Response Schema:**

[intel-sinkholes_get_sinkholes_response](../schemas/intel-sinkholes/intel-sinkholes-get-sinkholes-response.md)

## Security

- **api_email**
- **api_key**
