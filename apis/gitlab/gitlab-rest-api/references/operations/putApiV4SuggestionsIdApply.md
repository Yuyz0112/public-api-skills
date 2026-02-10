# PUT /api/v4/suggestions/{id}/apply

**Resource:** [Suggestions](../resources/Suggestions.md)
**Apply suggestion patch in the Merge Request it was created**
**Operation ID:** `putApiV4SuggestionsIdApply`

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | integer | Yes | The ID of the suggestion |

## Request Body

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |

**Success Response Schema:**

[APIEntitiesSuggestion](../schemas/APIEntitiesSuggestion/APIEntitiesSuggestion.md)

