# POST /zones/{zone_id}/api_gateway/expression-template/fallthrough

**Resource:** [API Shield WAF Expression Templates](../resources/API-Shield-WAF-Expression-Templates.md)
**Generate fallthrough WAF expression template from a set of API hosts**
**Operation ID:** `api-shield-expression-templates-fallthrough`

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [api-shield_request_expression_templates_fallthrough](../schemas/api-shield/api-shield-request-expression-templates-fallthrough.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Generate fallthrough WAF expression template response |
| 4XX | Generate fallthrough WAF expression template failure |

## Security

- **api_email**
- **api_key**
- **api_token**
