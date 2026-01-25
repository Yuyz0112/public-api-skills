# DELETE /2010-04-01/Accounts/{AccountSid}/SigningKeys/{Sid}.json

**Resource:** [Api20100401SigningKey](../resources/Api20100401SigningKey.md)
**Operation ID:** `DeleteSigningKey`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `AccountSid` | path | string | Yes |  |
| `Sid` | path | string | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 204 | The resource was deleted successfully. |

## Security

- **accountSid_authToken**
