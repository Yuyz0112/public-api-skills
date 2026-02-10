# GET /api/v4/projects/{id}/members

**Resource:** [Members](../resources/Members.md)
**Gets a list of group or project members viewable by the authenticated user.**
**Operation ID:** `getApiV4ProjectsIdMembers`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The project ID |
| `query` | query | string | No | A query string to search for members |
| `user_ids` | query | any | No | Array of user ids to look up for membership |
| `skip_users` | query | any | No | Array of user ids to be skipped for membership |
| `show_seat_info` | query | boolean | No | Show seat information for members |
| `with_saml_identity` | query | boolean | No | List only members with linked SAML identity |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesMember](../schemas/APIEntitiesMember/APIEntitiesMember.md)

