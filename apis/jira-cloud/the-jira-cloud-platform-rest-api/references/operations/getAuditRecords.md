# GET /rest/api/3/auditing/record

**Resource:** [Audit records](../resources/Audit-records.md)
**Get audit records**
**Operation ID:** `getAuditRecords`

Returns a list of audit records. The list can be filtered to include items:

 *  where each item in `filter` has at least one match in any of these fields:
    
     *  `summary`
     *  `category`
     *  `eventSource`
     *  `objectItem.name` If the object is a user, account ID is available to filter.
     *  `objectItem.parentName`
     *  `objectItem.typeName`
     *  `changedValues.changedFrom`
     *  `changedValues.changedTo`
     *  `remoteAddress`
    
    For example, if `filter` contains *man ed*, an audit record containing `summary": "User added to group"` and `"category": "group management"` is returned.
 *  created on or after a date and time.
 *  created or or before a date and time.

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `offset` | query | integer (int32) | No | The number of records to skip before returning the first result. |
| `limit` | query | integer (int32) | No | The maximum number of results to return. |
| `filter` | query | string | No | The strings to match with audit field content, space separated. |
| `from` | query | string | No | The date and time on or after which returned audit records must have been created. If `to` is provided `from` must be before `to` or no audit records are returned. |
| `to` | query | string | No | The date and time on or before which returned audit results must have been created. If `from` is provided `to` must be after `from` or no audit records are returned. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if:

 *  the user does not have the required permissions.
 *  all Jira products are on free plans. Audit logs are available when at least one Jira product is on a paid plan. |

**Success Response Schema:**

[AuditRecords](../schemas/Audit/AuditRecords.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
