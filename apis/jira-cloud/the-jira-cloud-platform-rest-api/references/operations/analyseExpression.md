# POST /rest/api/3/expression/analyse

**Resource:** [Jira expressions](../resources/Jira-expressions.md)
**Analyse Jira expression**
**Operation ID:** `analyseExpression`

Analyses and validates Jira expressions.

As an experimental feature, this operation can also attempt to type-check the expressions.

Learn more about Jira expressions in the [documentation](https://developer.atlassian.com/cloud/jira/platform/jira-expressions/).

**[Permissions](#permissions) required**: None.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `check` | query | enum: syntax, type, complexity | No | The check to perform:

 *  `syntax` Each expression's syntax is checked to ensure the expression can be parsed. Also, syntactic limits are validated. For example, the expression's length.
 *  `type` EXPERIMENTAL. Each expression is type checked and the final type of the expression inferred. Any type errors that would result in the expression failure at runtime are reported. For example, accessing properties that don't exist or passing the wrong number of arguments to functions. Also performs the syntax check.
 *  `complexity` EXPERIMENTAL. Determines the formulae for how many [expensive operations](https://developer.atlassian.com/cloud/jira/platform/jira-expressions/#expensive-operations) each expression may execute. |

## Request Body

The Jira expressions to analyse.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [JiraExpressionForAnalysis](../schemas/Jira/JiraExpressionForAnalysis.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the request is successful. |
| 400 | 400 response |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | 404 response |

**Success Response Schema:**

[JiraExpressionsAnalysis](../schemas/Jira/JiraExpressionsAnalysis.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work, read:jira-user
