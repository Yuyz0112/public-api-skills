# magic-visibility-pcaps_pcaps_ownership_response

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `destination_conf` | [magic-visibility-pcaps_pcaps_destination_conf](magic-visibility-pcaps-pcaps-destination-conf.md) | Yes |  |
| `filename` | [magic-visibility-pcaps_pcaps_ownership_challenge](magic-visibility-pcaps-pcaps-ownership-challenge.md) | Yes |  |
| `id` | string | Yes | The bucket ID associated with the packet captures API. |
| `status` | enum: pending, success, failed | Yes | The status of the ownership challenge. Can be pending, success or failed. |
| `submitted` | string | Yes | The RFC 3339 timestamp when the bucket was added to packet captures API. |
| `validated` | string | No | The RFC 3339 timestamp when the bucket was validated. |

