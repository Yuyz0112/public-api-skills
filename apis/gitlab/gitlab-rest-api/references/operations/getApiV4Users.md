# GET /api/v4/users

**Resource:** [Users](../resources/Users.md)
**Get the list of users**
**Operation ID:** `getApiV4Users`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `username` | query | string | No | Get a single user with a specific username |
| `extern_uid` | query | string | No | Get a single user with a specific external authentication provider UID |
| `public_email` | query | string | No | Get a single user with a specific public email |
| `provider` | query | string | No | The external provider |
| `search` | query | string | No | Search for a username |
| `active` | query | boolean | No | Filters only active users |
| `humans` | query | boolean | No | Filters only human users |
| `external` | query | boolean | No | Filters only external users |
| `blocked` | query | boolean | No | Filters only blocked users |
| `created_after` | query | string (date-time) | No | Return users created after the specified time |
| `created_before` | query | string (date-time) | No | Return users created before the specified time |
| `without_projects` | query | boolean | No | Filters only users without projects |
| `without_project_bots` | query | boolean | No | Filters users without project bots |
| `admins` | query | boolean | No | Filters only admin users |
| `two_factor` | query | string | No | Filter users by Two-factor authentication. |
| `exclude_active` | query | boolean | No | Filters only non active users |
| `exclude_external` | query | boolean | No | Filters only non external users |
| `exclude_humans` | query | boolean | No | Filters only non human users |
| `exclude_internal` | query | boolean | No | Filters only non internal users |
| `order_by` | query | enum: id, name, username... | No | Return users ordered by a field |
| `sort` | query | enum: asc, desc | No | Return users sorted in ascending and descending order |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `with_custom_attributes` | query | boolean | No | Include custom attributes in the response |
| `custom_attributes` | query | object | No | Filter with custom attributes |
| `skip_ldap` | query | boolean | No | Skip LDAP users |
| `auditors` | query | boolean | No | Filters only auditor users |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesUserBasic](../schemas/APIEntitiesUserBasic/APIEntitiesUserBasic.md)

