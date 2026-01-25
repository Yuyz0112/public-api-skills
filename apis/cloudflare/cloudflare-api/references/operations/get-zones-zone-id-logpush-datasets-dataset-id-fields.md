# GET /zones/{zone_id}/logpush/datasets/{dataset_id}/fields

**Resource:** [Logpush jobs for a zone](../resources/Logpush-jobs-for-a-zone.md)
**List fields**
**Operation ID:** `get-zones-zone_id-logpush-datasets-dataset_id-fields`

Lists all fields available for a dataset. The response result is. an object with key-value pairs, where keys are field names, and values are descriptions.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `dataset_id` | path | logpush_dataset | Yes |  |
| `zone_id` | path | logpush_identifier | Yes |  |

## Responses

| Status | Description |
|--------|-------------|
| 200 | List fields response. |
| 4XX | List fields response failure. |

**Success Response Schema:**

[logpush_logpush_field_response_collection](../schemas/logpush/logpush-logpush-field-response-collection.md)

## Security

- **api_email**
- **api_key**
- **api_token**
