# PollResponse

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `question` | [PollMediaResponse](PollMediaResponse.md) | Yes |  |
| `answers` | PollAnswerResponse[] | Yes |  |
| `expiry` | string (date-time) | Yes |  |
| `allow_multiselect` | boolean | Yes |  |
| `layout_type` | [PollLayoutTypes](PollLayoutTypes.md) | Yes |  |
| `results` | [PollResultsResponse](PollResultsResponse.md) | Yes |  |

