# GET /accounts/{account_id}/cloudforce-one/events/countries

**Resource:** [Country](../resources/Country.md)
**Retrieves countries information for all countries**
**Operation ID:** `get_CountryRead`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | string | Yes | Account ID. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returns the long and short country code for every country. |
| 400 | Bad Request. |

## Security

- **api_token**
