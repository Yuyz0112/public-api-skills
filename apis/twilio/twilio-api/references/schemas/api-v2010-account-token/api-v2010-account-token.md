# api.v2010.account.token

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the Token resource. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that the resource was last updated specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `ice_servers` | object[] | No | An array representing the ephemeral credentials and the STUN and TURN server URIs. |
| `password` | string | No | The temporary password that the username will use when authenticating with Twilio. |
| `ttl` | string | No | The duration in seconds for which the username and password are valid. |
| `username` | string | No | The temporary username that uniquely identifies a Token. |

## Nested Fields

### `ice_servers`

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `credential` | string | No |  |
| `username` | string | No |  |
| `url` | string | No |  |
| `urls` | string | No |  |

