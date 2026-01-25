# GET /accounts/{account_id}/realtime/kit/{app_id}/sessions/peer-report/{peer_id}

**Resource:** [Sessions](../resources/Sessions.md)
**Fetch details of peer**
**Operation ID:** `GetParticipantDataFromPeerId`

Returns details of the given peer ID along with call statistics for the given session ID.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `account_id` | path | realtimekit_account_identifier | Yes |  |
| `app_id` | path | realtimekit_app_id | Yes |  |
| `filters` | query | enum: device_info, ip_information, precall_network_information... | No | Comma separated list of filters to apply. Note that there must be no spaces between the filters. |
| `peer_id` | path | string | Yes | ID of the peer |

## Responses

| Status | Description |
|--------|-------------|
| 200 | (reference) |

## Security

- **api_token**
