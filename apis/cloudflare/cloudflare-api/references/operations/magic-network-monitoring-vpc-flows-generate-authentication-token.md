# POST /accounts/{account_id}/mnm/vpc-flows/token

**Resource:** [Magic Network Monitoring VPC Flow logs](../resources/Magic-Network-Monitoring-VPC-Flow-logs.md)
**Generate authentication token for VPC flow logs export.**
**Operation ID:** `magic-network-monitoring-vpc-flows-generate-authentication-token`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | magic-visibility-mnm_account_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Generate authentication token for VPC flow logs export response. |
| 4XX | Generate authentication token for VPC flow logs export failure. |

**Success Response Schema:**

[magic-visibility-mnm_mnm_vpc_flows_single_response](../schemas/magic-visibility-mnm/magic-visibility-mnm-mnm-vpc-flows-single-response.md)

## Security

- **api_email**
- **api_key**
