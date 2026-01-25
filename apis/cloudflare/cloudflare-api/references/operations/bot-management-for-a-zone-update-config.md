# PUT /zones/{zone_id}/bot_management

**Resource:** [Bot Settings](../resources/Bot-Settings.md)
**Update Zone Bot Management Config**
**Operation ID:** `bot-management-for-a-zone-update-config`

Updates the Bot Management configuration for a zone.

This API is used to update:
- **Bot Fight Mode**
- **Super Bot Fight Mode**
- **Bot Management for Enterprise**

See [Bot Plans](https://developers.cloudflare.com/bots/plans/) for more information on the different plans 
\
If you recently upgraded or downgraded your plan, refer to the following examples to clean up old configurations. 
Copy and paste the example body to remove old zone configurations based on your current plan.
#### Clean up configuration for Bot Fight Mode plan
```json
{
  "sbfm_likely_automated": "allow", 
  "sbfm_definitely_automated": "allow", 
  "sbfm_verified_bots": "allow", 
  "sbfm_static_resource_protection": false, 
  "optimize_wordpress": false, 
  "suppress_session_score": false
}
```
#### Clean up configuration for SBFM Pro plan
```json
{
  "sbfm_likely_automated": "allow", 
  "fight_mode": false 
}
```
#### Clean up configuration for SBFM Biz plan
```json
{
  "fight_mode": false
}
```
#### Clean up configuration for BM Enterprise Subscription plan
It is strongly recommended that you ensure you have [custom rules](https://developers.cloudflare.com/waf/custom-rules/) in place to protect your zone before disabling the SBFM rules. Without these protections, your zone is vulnerable to attacks.
```json
{
  "sbfm_likely_automated": "allow", 
  "sbfm_definitely_automated": "allow", 
  "sbfm_verified_bots": "allow", 
  "sbfm_static_resource_protection": false, 
  "optimize_wordpress": false, 
  "fight_mode": false
}
```


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `zone_id` | path | bot-management_identifier | Yes |  |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [bot-management_config_single](../schemas/bot-management/bot-management-config-single.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Update Bot Management response |
| 4XX | Update Bot Management response failure |

**Success Response Schema:**

[bot-management_bot_management_response_body](../schemas/bot-management/bot-management-bot-management-response-body.md)

## Security

- **api_token**
- **api_email**
- **api_key**
