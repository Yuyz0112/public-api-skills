# PUT /permissionscheme/{schemeId}

**Resource:** [permissionscheme](../resources/permissionscheme.md)
**Operation ID:** `updatePermissionScheme`

Updates a permission scheme.
 <p>
 If the permissions list is present then it will be set in the permission scheme, which basically means it will overwrite any permission grants that
 existed in the permission scheme. Sending an empty list will remove all permission grants from the permission scheme.
 </p>
 <p>
 To update just the name and description, do not send permissions list at all.
 </p>
 <p>
 To add or remove a single permission grant instead of updating the whole list at once use the <b>{schemeId}/permission/</b> resource.
 </p>

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful Response |

