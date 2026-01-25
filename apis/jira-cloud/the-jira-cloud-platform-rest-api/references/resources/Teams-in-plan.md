# Teams in plan

This resource represents planning settings for plan-only and Atlassian teams in a plan. Use it to get, create, update and delete planning settings.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/rest/api/3/plans/plan/{planId}/team` | Get teams in plan paginated | [View](../operations/getTeams.md) |
| POST | `/rest/api/3/plans/plan/{planId}/team/atlassian` | Add Atlassian team to plan | [View](../operations/addAtlassianTeam.md) |
| GET | `/rest/api/3/plans/plan/{planId}/team/atlassian/{atlassianTeamId}` | Get Atlassian team in plan | [View](../operations/getAtlassianTeam.md) |
| PUT | `/rest/api/3/plans/plan/{planId}/team/atlassian/{atlassianTeamId}` | Update Atlassian team in plan | [View](../operations/updateAtlassianTeam.md) |
| DELETE | `/rest/api/3/plans/plan/{planId}/team/atlassian/{atlassianTeamId}` | Remove Atlassian team from plan | [View](../operations/removeAtlassianTeam.md) |
| POST | `/rest/api/3/plans/plan/{planId}/team/planonly` | Create plan-only team | [View](../operations/createPlanOnlyTeam.md) |
| GET | `/rest/api/3/plans/plan/{planId}/team/planonly/{planOnlyTeamId}` | Get plan-only team | [View](../operations/getPlanOnlyTeam.md) |
| PUT | `/rest/api/3/plans/plan/{planId}/team/planonly/{planOnlyTeamId}` | Update plan-only team | [View](../operations/updatePlanOnlyTeam.md) |
| DELETE | `/rest/api/3/plans/plan/{planId}/team/planonly/{planOnlyTeamId}` | Delete plan-only team | [View](../operations/deletePlanOnlyTeam.md) |
