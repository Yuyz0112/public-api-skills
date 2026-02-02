# project

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/project` |  | [View](../operations/getAllProjects.md) |
| POST | `/project` |  | [View](../operations/createProject.md) |
| GET | `/project/type` |  | [View](../operations/getAllProjectTypes.md) |
| GET | `/project/type/{projectTypeKey}` |  | [View](../operations/getProjectTypeByKey.md) |
| GET | `/project/type/{projectTypeKey}/accessible` |  | [View](../operations/getAccessibleProjectTypeByKey.md) |
| GET | `/project/{projectIdOrKey}` |  | [View](../operations/getProject.md) |
| PUT | `/project/{projectIdOrKey}` |  | [View](../operations/updateProject.md) |
| DELETE | `/project/{projectIdOrKey}` |  | [View](../operations/deleteProject.md) |
| PUT | `/project/{projectIdOrKey}/archive` |  | [View](../operations/archiveProject.md) |
| PUT | `/project/{projectIdOrKey}/avatar` |  | [View](../operations/updateProjectAvatar.md) |
| POST | `/project/{projectIdOrKey}/avatar` |  | [View](../operations/createAvatarFromTemporary.md) |
| POST | `/project/{projectIdOrKey}/avatar/temporary` |  | [View](../operations/storeTemporaryAvatarUsingMultiPart.md) |
| DELETE | `/project/{projectIdOrKey}/avatar/{id}` |  | [View](../operations/deleteAvatar.md) |
| GET | `/project/{projectIdOrKey}/avatars` |  | [View](../operations/getAllAvatars.md) |
| GET | `/project/{projectIdOrKey}/components` |  | [View](../operations/getProjectComponents.md) |
| GET | `/project/{projectIdOrKey}/properties` |  | [View](../operations/getPropertiesKeys.md) |
| GET | `/project/{projectIdOrKey}/properties/{propertyKey}` |  | [View](../operations/getProperty.md) |
| PUT | `/project/{projectIdOrKey}/properties/{propertyKey}` |  | [View](../operations/setProperty.md) |
| DELETE | `/project/{projectIdOrKey}/properties/{propertyKey}` |  | [View](../operations/deleteProperty.md) |
| PUT | `/project/{projectIdOrKey}/restore` |  | [View](../operations/restoreProject.md) |
| GET | `/project/{projectIdOrKey}/role` |  | [View](../operations/getProjectRoles.md) |
| GET | `/project/{projectIdOrKey}/role/{id}` |  | [View](../operations/getProjectRole.md) |
| PUT | `/project/{projectIdOrKey}/role/{id}` |  | [View](../operations/setActors.md) |
| POST | `/project/{projectIdOrKey}/role/{id}` |  | [View](../operations/addActorUsers.md) |
| DELETE | `/project/{projectIdOrKey}/role/{id}` |  | [View](../operations/deleteActor.md) |
| GET | `/project/{projectIdOrKey}/statuses` |  | [View](../operations/getAllStatuses.md) |
| PUT | `/project/{projectIdOrKey}/type/{newProjectTypeKey}` |  | [View](../operations/updateProjectType.md) |
| GET | `/project/{projectIdOrKey}/version` |  | [View](../operations/getProjectVersionsPaginated.md) |
| GET | `/project/{projectIdOrKey}/versions` |  | [View](../operations/getProjectVersions.md) |
| GET | `/project/{projectKeyOrId}/issuesecuritylevelscheme` |  | [View](../operations/getIssueSecurityScheme.md) |
| GET | `/project/{projectKeyOrId}/notificationscheme` |  | [View](../operations/getNotificationScheme.md) |
| GET | `/project/{projectKeyOrId}/permissionscheme` |  | [View](../operations/getAssignedPermissionScheme.md) |
| PUT | `/project/{projectKeyOrId}/permissionscheme` |  | [View](../operations/assignPermissionScheme.md) |
| GET | `/project/{projectKeyOrId}/priorityscheme` |  | [View](../operations/getAssignedPriorityScheme.md) |
| PUT | `/project/{projectKeyOrId}/priorityscheme` |  | [View](../operations/assignPriorityScheme.md) |
| DELETE | `/project/{projectKeyOrId}/priorityscheme/{schemeId}` |  | [View](../operations/unassignPriorityScheme.md) |
| GET | `/project/{projectKeyOrId}/securitylevel` |  | [View](../operations/getSecurityLevelsForProject.md) |
| GET | `/project/{projectKeyOrId}/workflowscheme` |  | [View](../operations/getWorkflowSchemeForProject.md) |
