# api.v2010.account.connect_app

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `account_sid` | string | No | The SID of the [Account](https://www.twilio.com/docs/iam/api/account) that created the ConnectApp resource. |
| `authorize_redirect_url` | string (uri) | No | The URL we redirect the user to after we authenticate the user and obtain authorization to access the Connect App. |
| `company_name` | string | No | The company name set for the Connect App. |
| `deauthorize_callback_method` | enum: GET, POST | No | The HTTP method we use to call `deauthorize_callback_url`. |
| `deauthorize_callback_url` | string (uri) | No | The URL we call using the `deauthorize_callback_method` to de-authorize the Connect App. |
| `description` | string | No | The description of the Connect App. |
| `friendly_name` | string | No | The string that you assigned to describe the resource. |
| `homepage_url` | string (uri) | No | The public URL where users can obtain more information about this Connect App. |
| `permissions` | connect_app_enum_permission[] | No | The set of permissions that your ConnectApp requests. |
| `sid` | string | No | The unique string that that we created to identify the ConnectApp resource. |
| `uri` | string | No | The URI of the resource, relative to `https://api.twilio.com`. |

