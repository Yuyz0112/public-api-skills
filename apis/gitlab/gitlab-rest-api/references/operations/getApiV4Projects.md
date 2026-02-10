# GET /api/v4/projects

**Resource:** [Projects](../resources/Projects.md)
**Get a list of visible projects for authenticated user**
**Operation ID:** `getApiV4Projects`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `order_by` | query | enum: id, name, path... | No | Return projects ordered by field. storage_size, repository_size, wiki_size, packages_size are only available to admins. Similarity is available when searching and is limited to projects the user has access to. |
| `sort` | query | enum: asc, desc | No | Return projects sorted in ascending and descending order |
| `archived` | query | boolean | No | Limit by archived status |
| `visibility` | query | enum: private, internal, public | No | Limit by visibility |
| `search` | query | string | No | Return list of projects matching the search criteria |
| `search_namespaces` | query | boolean | No | Include ancestor namespaces when matching search criteria |
| `owned` | query | boolean | No | Limit by owned by authenticated user |
| `starred` | query | boolean | No | Limit by starred status |
| `imported` | query | boolean | No | Limit by imported by authenticated user |
| `membership` | query | boolean | No | Limit by projects that the current user is a member of |
| `with_issues_enabled` | query | boolean | No | Limit by enabled issues feature |
| `with_merge_requests_enabled` | query | boolean | No | Limit by enabled merge requests feature |
| `with_programming_language` | query | string | No | Limit to repositories which use the given programming language |
| `min_access_level` | query | enum: 10, 15, 20... | No | Limit by minimum access level of authenticated user |
| `id_after` | query | integer | No | Limit results to projects with IDs greater than the specified ID |
| `id_before` | query | integer | No | Limit results to projects with IDs less than the specified ID |
| `last_activity_after` | query | string (date-time) | No | Limit results to projects with last_activity after specified time. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `last_activity_before` | query | string (date-time) | No | Limit results to projects with last_activity before specified time. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `repository_storage` | query | string | No | Which storage shard the repository is on. Available only to admins |
| `topic` | query | any | No | Comma-separated list of topics. Limit results to projects having all topics |
| `topic_id` | query | integer | No | Limit results to projects with the assigned topic given by the topic ID |
| `updated_before` | query | string (date-time) | No | Return projects updated before the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `updated_after` | query | string (date-time) | No | Return projects updated after the specified datetime. Format: ISO 8601 YYYY-MM-DDTHH:MM:SSZ |
| `include_pending_delete` | query | boolean | No | Include projects in pending delete state. Can only be set by admins |
| `marked_for_deletion_on` | query | string (date) | No | Date when the project was marked for deletion |
| `active` | query | boolean | No | Limit by projects that are not archived and not marked for deletion |
| `wiki_checksum_failed` | query | boolean | No | Limit by projects where wiki checksum is failed |
| `repository_checksum_failed` | query | boolean | No | Limit by projects where repository checksum is failed |
| `include_hidden` | query | boolean | No | Include hidden projects. Can only be set by admins |
| `page` | query | integer | No | Current page number |
| `per_page` | query | integer | No | Number of items per page |
| `simple` | query | boolean | No | Return only the ID, URL, name, and path of each project |
| `statistics` | query | boolean | No | Include project statistics |
| `with_custom_attributes` | query | boolean | No | Include custom attributes in the response |
| `custom_attributes` | query | object | No | Filter with custom attributes |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 400 | Bad request |

**Success Response Schema:**

[APIEntitiesBasicProjectDetails](../schemas/APIEntitiesBasicProjectDetails/APIEntitiesBasicProjectDetails.md)

