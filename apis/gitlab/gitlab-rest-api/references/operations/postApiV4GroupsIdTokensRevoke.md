# POST /api/v4/groups/{id}/tokens/revoke

**Resource:** [Groups](../resources/Groups.md)
**Revoke a single token**
**Operation ID:** `postApiV4GroupsIdTokensRevoke`

Revoke a token, if it has access to the group or any of its subgroups
and projects. If the token is revoked, or was already revoked, its
details are returned in the response.

The following criteria must be met:

- The group must be a top-level group.
- You must have Owner permission in the group.
- The token type is one of:
  - Personal access token
  - Group access token
  - Project access token
  - Group deploy token
  - User feed token

This feature is gated by the :group_agnostic_token_revocation feature flag.


## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | string | Yes | The ID of a top-level group |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Created |

