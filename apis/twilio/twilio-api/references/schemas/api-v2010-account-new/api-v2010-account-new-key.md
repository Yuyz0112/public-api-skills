# api.v2010.account.new_key

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `sid` | string | No | The unique string that that we created to identify the NewKey resource. You will use this as the basic-auth `user` when authenticating to the API. |
| `friendly_name` | string | No | The string that you assigned to describe the resource. |
| `date_created` | string (date-time-rfc-2822) | No | The date and time in GMT that the API Key was created specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `date_updated` | string (date-time-rfc-2822) | No | The date and time in GMT that the new API Key was last updated specified in [RFC 2822](https://www.ietf.org/rfc/rfc2822.txt) format. |
| `secret` | string | No | The secret your application uses to sign Access Tokens and to authenticate to the REST API (you will use this as the basic-auth `password`).  **Note that for security reasons, this field is ONLY returned when the API Key is first created.** |

