# GET /zones/{zone_id}/dcv_delegation/uuid

**Resource:** [DCV Delegation](../resources/DCV-Delegation.md)
**Retrieve the DCV Delegation unique identifier.**
**Operation ID:** `dcv-delegation-uuid-get`

Retrieve the account and zone specific unique identifier used as part of the CNAME target for DCV Delegation.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | tls-certificates-and-hostnames_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Retrieve the DCV Delegation unique identifier response. |
| 4XX | Retrieve the DCV Delegation unique identifier response failure. |

**Success Response Schema:**

[tls-certificates-and-hostnames_dcv_delegation_response](../schemas/tls-certificates-and-hostnames/tls-certificates-and-hostnames-dcv-delegation-response.md)

## Security

- **api_email**
- **api_key**
- **api_token**
