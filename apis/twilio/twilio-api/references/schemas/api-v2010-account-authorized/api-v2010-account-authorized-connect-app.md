# api.v2010.account.authorized_connect_app

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the AuthorizedConnectApp resource. |
| `connect_app_company_name` | string | No | The company name set for the Connect App. |
| `connect_app_description` | string | No | A detailed description of the Connect App. |
| `connect_app_friendly_name` | string | No | The name of the Connect App. |
| `connect_app_homepage_url` | string (uri) | No | The public URL for the Connect App. |
| `connect_app_sid` | string | No | The SID that we assigned to the Connect App. |
| `permissions` | authorized_connect_app_enum_permission[] | No | The set of permissions that you authorized for the Connect App.  Can be: `get-all` or `post-all`. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |

