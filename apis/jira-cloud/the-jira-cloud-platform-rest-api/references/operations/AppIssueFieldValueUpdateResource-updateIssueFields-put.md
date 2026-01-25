# PUT /rest/atlassian-connect/1/migration/field

**Resource:** [App migration](../resources/App-migration.md)
**Bulk update custom field value**
**Operation ID:** `AppIssueFieldValueUpdateResource.updateIssueFields_put`

Updates the value of a custom field added by Connect apps on one or more issues.
The values of up to 200 custom fields can be updated.

**[Permissions](#permissions) required:** Only Connect apps can make this request

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `Atlassian-Transfer-Id` | header | string (uuid) | Yes | The ID of the transfer. |

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [ConnectCustomFieldValues](../schemas/Connect/ConnectCustomFieldValues.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request is invalid. |
| 403 | Returned if:
* the transfer ID is not found.
* the authorisation credentials are incorrect or missing. |

