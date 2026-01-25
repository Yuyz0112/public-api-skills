# POST /rest/api/3/expression/evaluate

**Resource:** [Jira expressions](../resources/Jira-expressions.md)
**Evaluate Jira expression using enhanced search API**
**Operation ID:** `evaluateJSISJiraExpression`

Evaluates a Jira expression and returns its value. The difference between this and `eval` is that this endpoint uses the enhanced search API when evaluating JQL queries. This API is eventually consistent, unlike the strongly consistent `eval` API. This allows for better performance and scalability. In addition, this API's response for JQL evaluation is based on a scrolling view (backed by a `nextPageToken`) instead of a paginated view (backed by `startAt` and `totalCount`).

This resource can be used to test Jira expressions that you plan to use elsewhere, or to fetch data in a flexible way. Consult the [Jira expressions documentation](https://developer.atlassian.com/cloud/jira/platform/jira-expressions/) for more details.

#### Context variables ####

The following context variables are available to Jira expressions evaluated by this resource. Their presence depends on various factors; usually you need to manually request them in the context object sent in the payload, but some of them are added automatically under certain conditions.

 *  `user` ([User](https://developer.atlassian.com/cloud/jira/platform/jira-expressions-type-reference#user)): The current user. Always available and equal to `null` if the request is anonymous.
 *  `app` ([App](https://developer.atlassian.com/cloud/jira/platform/jira-expressions-type-reference#app)): The [Connect app](https://developer.atlassian.com/cloud/jira/platform/index/#connect-apps) that made the request. Available only for authenticated requests made by Connect apps (read more here: [Authentication for Connect apps](https://developer.atlassian.com/cloud/jira/platform/security-for-connect-apps/)).
 *  `issue` ([Issue](https://developer.atlassian.com/cloud/jira/platform/jira-expressions-type-reference#issue)): The current issue. Available only when the issue is provided in the request context object.
 *  `issues` ([List](https://developer.atlassian.com/cloud/jira/platform/jira-expressions-type-reference#list) of [Issues](https://developer.atlassian.com/cloud/jira/platform/jira-expressions-type-reference#issue)): A collection of issues matching a JQL query. Available only when JQL is provided in the request context object.
 *  `project` ([Project](https://developer.atlassian.com/cloud/jira/platform/jira-expressions-type-reference#project)): The current project. Available only when the project is provided in the request context object.
 *  `sprint` ([Sprint](https://developer.atlassian.com/cloud/jira/platform/jira-expressions-type-reference#sprint)): The current sprint. Available only when the sprint is provided in the request context object.
 *  `board` ([Board](https://developer.atlassian.com/cloud/jira/platform/jira-expressions-type-reference#board)): The current board. Available only when the board is provided in the request context object.
 *  `serviceDesk` ([ServiceDesk](https://developer.atlassian.com/cloud/jira/platform/jira-expressions-type-reference#servicedesk)): The current service desk. Available only when the service desk is provided in the request context object.
 *  `customerRequest` ([CustomerRequest](https://developer.atlassian.com/cloud/jira/platform/jira-expressions-type-reference#customerrequest)): The current customer request. Available only when the customer request is provided in the request context object.

In addition, you can pass custom context variables along with their types. You can then access them from the Jira expression by key. You can use the following variables in a custom context:

 *  `user`: A [user](https://developer.atlassian.com/cloud/jira/platform/jira-expressions-type-reference#user) specified as an Atlassian account ID.
 *  `issue`: An [issue](https://developer.atlassian.com/cloud/jira/platform/jira-expressions-type-reference#issue) specified by ID or key. All the fields of the issue object are available in the Jira expression.
 *  `json`: A JSON object containing custom content.
 *  `list`: A JSON list of `user`, `issue`, or `json` variable types.

This operation can be accessed anonymously.

**[Permissions](#permissions) required**: None. However, an expression may return different results for different users depending on their permissions. For example, different users may see different comments on the same issue.  
Permission to access Jira Software is required to access Jira Software context variables (`board` and `sprint`) or fields (for example, `issue.sprint`).

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `expand` | query | string | No | Use [expand](#expansion) to include additional information in the response. This parameter accepts `meta.complexity` that returns information about the expression complexity. For example, the number of expensive operations used by the expression and how close the expression is to reaching the [complexity limit](https://developer.atlassian.com/cloud/jira/platform/jira-expressions/#restrictions). Useful when designing and debugging your expressions. |

## Request Body

The Jira expression and the evaluation context.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [JiraExpressionEvaluateRequestBean](../schemas/Jira/JiraExpressionEvaluateRequestBean.md)

## Responses

| Status | Description |
|--------|-------------|
| 200 | Returned if the evaluation results in a value. The result is a JSON primitive value, list, or object. |
| 400 | Returned if:

 *  the request is invalid, that is:
    
     *  invalid data is provided, such as a request including issue ID and key.
     *  the expression is invalid and can not be parsed.
 *  evaluation fails at runtime. This may happen for various reasons. For example, accessing a property on a null object (such as the expression `issue.id` where `issue` is `null`). In this case an error message is provided.
 *  If jql is unbounded or empty.
 *  If nextPageToken is invalid |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 404 | Returned if any object provided in the request context is not found or the user does not have permission to view it. |

**Success Response Schema:**

[JExpEvaluateJiraExpressionResultBean](../schemas/JExpEvaluateJiraExpressionResultBean/JExpEvaluateJiraExpressionResultBean.md)

## Security

- **basicAuth**
- **OAuth2**: read:jira-work, read:jira-user
