# POST /rest/api/3/priorityscheme/mappings

**Resource:** [Priority schemes](../resources/Priority-schemes.md)
**Suggested priorities for mappings**
**Operation ID:** `suggestedPrioritiesForMappings`

Returns a [paginated](#pagination) list of priorities that would require mapping, given a change in priorities or projects associated with a priority scheme.

**[Permissions](#permissions) required:** Permission to access Jira.

## Request Body

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [SuggestedMappingsRequestBean](../schemas/Suggested/SuggestedMappingsRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | Returned if the request isn't valid. |
| 401 | Returned if the authentication credentials are incorrect. |

**Success Response Schema:**

[PageBeanPriorityWithSequence](../schemas/Page/PageBeanPriorityWithSequence.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
