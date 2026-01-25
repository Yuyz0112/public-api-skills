# PUT /zones/{zone_id}/cloud_connector/rules

**Resource:** [Zone Cloud Connector Rules PUT](../resources/Zone-Cloud-Connector-Rules-PUT.md)
**Put Rules**
**Operation ID:** `zone-cloud-conenctor-rules-put`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cloud-connector_identifier | Yes |  |

## Request Body

**Content Types:** `application/json`

**Schema:** Array of [cloud-connector_rule](../schemas/cloud-connector/cloud-connector-rule.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Cloud Connector rules response |
| 4XX | Cloud Connector response failure |
| 5XX | Cloud Connector response failure |

## Security

- **api_email**
- **api_key**
