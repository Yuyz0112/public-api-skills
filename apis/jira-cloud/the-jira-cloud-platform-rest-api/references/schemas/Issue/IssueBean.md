# IssueBean

Details about an issue.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `changelog` | any | No | Details of changelogs associated with the issue. |
| `editmeta` | any | No | The metadata for the fields on the issue that can be amended. |
| `expand` | string | No | Expand options that include additional issue details in the response. |
| `fields` | object | No |  |
| `fieldsToInclude` | [IncludedFields](IncludedFields.md) | No |  |
| `id` | string | No | The ID of the issue. |
| `key` | string | No | The key of the issue. |
| `names` | object | No | The ID and name of each field present on the issue. |
| `operations` | any | No | The operations that can be performed on the issue. |
| `properties` | object | No | Details of the issue properties identified in the request. |
| `renderedFields` | object | No | The rendered value of each field present on the issue. |
| `schema` | object | No | The schema describing each field present on the issue. |
| `self` | string (uri) | No | The URL of the issue details. |
| `transitions` | IssueTransition[] | No | The transitions that can be performed on the issue. |
| `versionedRepresentations` | object | No | The versions of each field on the issue. |

