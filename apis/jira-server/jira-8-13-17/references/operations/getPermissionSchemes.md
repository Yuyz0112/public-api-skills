# GET /permissionscheme

**Resource:** [permissionscheme](../resources/permissionscheme.md)
**Operation ID:** `getPermissionSchemes`

Returns a list of all permission schemes.
 <p>
 By default only shortened beans are returned. If you want to include permissions of all the schemes,
 then specify the <b>permissions</b> expand parameter. Permissions will be included also if you specify
 any other expand parameter.
 </p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

