# person_relationship

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `authorizer` | boolean | No | Whether the person is the authorizer of the account's representative. |
| `director` | boolean | No | Whether the person is a director of the account's legal entity. Directors are typically members of the governing board of the company, or responsible for ensuring the company meets its regulatory obligations. |
| `executive` | boolean | No | Whether the person has significant responsibility to control, manage, or direct the organization. |
| `legal_guardian` | boolean | No | Whether the person is the legal guardian of the account's representative. |
| `owner` | boolean | No | Whether the person is an owner of the account’s legal entity. |
| `percent_ownership` | number | No | The percent owned by the person of the account's legal entity. |
| `representative` | boolean | No | Whether the person is authorized as the primary representative of the account. This is the person nominated by the business to provide information about themselves, and general information about the account. There can only be one representative at any given time. At the time the account is created, this person should be set to the person responsible for opening the account. |
| `title` | string | No | The person's title (e.g., CEO, Support Engineer). |

