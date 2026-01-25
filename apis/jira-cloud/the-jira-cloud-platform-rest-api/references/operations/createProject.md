# POST /rest/api/3/project

**Resource:** [Projects](../resources/Projects.md)
**Create project**
**Operation ID:** `createProject`

Creates a project based on a project type template, as shown in the following table:

| Project Type Key | Project Template Key |  
|--|--|  
| `business` | `com.atlassian.jira-core-project-templates:jira-core-simplified-content-management`, `com.atlassian.jira-core-project-templates:jira-core-simplified-document-approval`, `com.atlassian.jira-core-project-templates:jira-core-simplified-lead-tracking`, `com.atlassian.jira-core-project-templates:jira-core-simplified-process-control`, `com.atlassian.jira-core-project-templates:jira-core-simplified-procurement`, `com.atlassian.jira-core-project-templates:jira-core-simplified-project-management`, `com.atlassian.jira-core-project-templates:jira-core-simplified-recruitment`, `com.atlassian.jira-core-project-templates:jira-core-simplified-task-tracking` |  
| `service_desk` | `com.atlassian.servicedesk:simplified-it-service-management`, `com.atlassian.servicedesk:simplified-external-service-desk`, `com.atlassian.servicedesk:simplified-hr-service-desk`, `com.atlassian.servicedesk:simplified-facilities-service-desk`, `com.atlassian.servicedesk:simplified-legal-service-desk`, `com.atlassian.servicedesk:simplified-analytics-service-desk`, `com.atlassian.servicedesk:simplified-marketing-service-desk`, `com.atlassian.servicedesk:simplified-design-service-desk`, `com.atlassian.servicedesk:simplified-sales-service-desk`, `com.atlassian.servicedesk:simplified-finance-service-desk`, `com.atlassian.servicedesk:company-managed-blank-service-project`, `com.atlassian.servicedesk:company-managed-general-service-project`, `com.atlassian.servicedesk:team-managed-general-service-project`, `com.atlassian.servicedesk:next-gen-it-service-desk`, `com.atlassian.servicedesk:next-gen-hr-service-desk`, `com.atlassian.servicedesk:next-gen-legal-service-desk`, `com.atlassian.servicedesk:next-gen-marketing-service-desk`, `com.atlassian.servicedesk:next-gen-facilities-service-desk`, `com.atlassian.servicedesk:next-gen-analytics-service-desk`, `com.atlassian.servicedesk:next-gen-finance-service-desk`, `com.atlassian.servicedesk:next-gen-design-service-desk`, `com.atlassian.servicedesk:next-gen-sales-service-desk` |  
| `software` | `com.pyxis.greenhopper.jira:gh-simplified-agility-kanban`, `com.pyxis.greenhopper.jira:gh-simplified-agility-scrum`, `com.pyxis.greenhopper.jira:gh-simplified-basic`, `com.pyxis.greenhopper.jira:gh-simplified-kanban-classic`, `com.pyxis.greenhopper.jira:gh-simplified-scrum-classic` |  
The project types are available according to the installed Jira features as follows:

 *  Jira Core, the default, enables `business` projects.
 *  Jira Service Management enables `service_desk` projects.
 *  Jira Software enables `software` projects.

To determine which features are installed, go to **Jira settings** > **Apps** > **Manage apps** and review the System Apps list. To add Jira Software or Jira Service Management into a JIRA instance, use **Jira settings** > **Apps** > **Finding new apps**. For more information, see [ Managing add-ons](https://confluence.atlassian.com/x/S31NLg).

**[Permissions](#permissions) required:** *Administer Jira* [global permission](https://confluence.atlassian.com/x/x4dKLg).

## Request Body

The JSON representation of the project being created.

**Required:** Yes

**Content Types:** `application/json`

**Schema:** [CreateProjectDetails](../schemas/Create/CreateProjectDetails.md)

## Responses

| Status | Description |
|--------|-------------|
| 201 | Returned if the project is created. |
| 400 | Returned if the request is not valid and the project could not be created. |
| 401 | Returned if the authentication credentials are incorrect or missing. |
| 403 | Returned if the user does not have permission to create projects. |

**Success Response Schema:**

[ProjectIdentifiers](../schemas/Project/ProjectIdentifiers.md)

## Security

- **basicAuth**
- **OAuth2**: manage:jira-configuration
