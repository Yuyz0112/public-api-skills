# GET /zones/{zone_id}/cloud_connector/rules

**Resource:** [Zone Cloud Connector Rules GET](../resources/Zone-Cloud-Connector-Rules-GET.md)
**Rules**
**Operation ID:** `zone-cloud-connector-rules`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | cloud-connector_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Cloud Connector rules response |
| 4XX | Cloud Connector response failure |
| 5XX | Cloud Connector response failure |

## Security

- **api_email**
- **api_key**
