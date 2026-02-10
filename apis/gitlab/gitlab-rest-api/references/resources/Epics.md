# Epics

Operations related to epics.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/api/v4/groups/{id}/related_epic_links` | Get related epics within the group and hierarchy | [View](../operations/getApiV4GroupsIdRelatedEpicLinks.md) |
| GET | `/api/v4/groups/{id}/epics/{epic_iid}/related_epics` | Get related epics | [View](../operations/getApiV4GroupsIdEpicsEpicIidRelatedEpics.md) |
| POST | `/api/v4/groups/{id}/epics/{epic_iid}/related_epics` | Relate epics | [View](../operations/postApiV4GroupsIdEpicsEpicIidRelatedEpics.md) |
| DELETE | `/api/v4/groups/{id}/epics/{epic_iid}/related_epics/{related_epic_link_id}` | Remove epics relation | [View](../operations/deleteApiV4GroupsIdEpicsEpicIidRelatedEpicsRelatedEpicLinkId.md) |
| GET | `/api/v4/groups/{id}/epic_boards` | Get all group epic boards | [View](../operations/getApiV4GroupsIdEpicBoards.md) |
| GET | `/api/v4/groups/{id}/epic_boards/{board_id}` | Find a group epic board | [View](../operations/getApiV4GroupsIdEpicBoardsBoardId.md) |
| GET | `/api/v4/groups/{id}/epic_boards/{board_id}/lists` | Get the lists of a group epic board | [View](../operations/getApiV4GroupsIdEpicBoardsBoardIdLists.md) |
| GET | `/api/v4/groups/{id}/epic_boards/{board_id}/lists/{list_id}` | Get a list of a group epic board | [View](../operations/getApiV4GroupsIdEpicBoardsBoardIdListsListId.md) |
| GET | `/api/v4/groups/{id}/epics` | Get epics for the group | [View](../operations/getApiV4GroupsIdEpics.md) |
| GET | `/api/v4/groups/{id}/-/epics` | Get epics for the group | [View](../operations/getApiV4GroupsIdDashEpics.md) |
| GET | `/api/v4/groups/{id}/epics/{epic_iid}` | Get details of an epic | [View](../operations/getApiV4GroupsIdEpicsEpicIid.md) |
| GET | `/api/v4/groups/{id}/-/epics/{epic_iid}` | Get details of an epic | [View](../operations/getApiV4GroupsIdDashEpicsEpicIid.md) |
| POST | `/api/v4/groups/{id}/(-/)epics` | Create a new epic | [View](../operations/postApiV4GroupsId-epics.md) |
| PUT | `/api/v4/groups/{id}/(-/)epics/{epic_iid}` | Update an epic | [View](../operations/putApiV4GroupsId-epicsEpicIid.md) |
| DELETE | `/api/v4/groups/{id}/(-/)epics/{epic_iid}` | Destroy an epic | [View](../operations/deleteApiV4GroupsId-epicsEpicIid.md) |
| GET | `/api/v4/groups/{id}/(-/)epics/{epic_iid}/epics` | Get related epics | [View](../operations/getApiV4GroupsId-epicsEpicIidEpics.md) |
| POST | `/api/v4/groups/{id}/(-/)epics/{epic_iid}/epics` | Create and relate epic to a parent | [View](../operations/postApiV4GroupsId-epicsEpicIidEpics.md) |
| PUT | `/api/v4/groups/{id}/(-/)epics/{epic_iid}/epics/{child_epic_id}` | Reorder child epics | [View](../operations/putApiV4GroupsId-epicsEpicIidEpicsChildEpicId.md) |
| POST | `/api/v4/groups/{id}/(-/)epics/{epic_iid}/epics/{child_epic_id}` | Relate epics | [View](../operations/postApiV4GroupsId-epicsEpicIidEpicsChildEpicId.md) |
| DELETE | `/api/v4/groups/{id}/(-/)epics/{epic_iid}/epics/{child_epic_id}` | Remove epics relation | [View](../operations/deleteApiV4GroupsId-epicsEpicIidEpicsChildEpicId.md) |
| PUT | `/api/v4/groups/{id}/(-/)epics/{epic_iid}/issues/{epic_issue_id}` | Update epic-issue association | [View](../operations/putApiV4GroupsId-epicsEpicIidIssuesEpicIssueId.md) |
| DELETE | `/api/v4/groups/{id}/(-/)epics/{epic_iid}/issues/{epic_issue_id}` | Remove an issue from the epic | [View](../operations/deleteApiV4GroupsId-epicsEpicIidIssuesEpicIssueId.md) |
| GET | `/api/v4/groups/{id}/epics/{epic_iid}/issues` | List issues for an epic | [View](../operations/getApiV4GroupsIdEpicsEpicIidIssues.md) |
| GET | `/api/v4/groups/{id}/-/epics/{epic_iid}/issues` | List issues for an epic | [View](../operations/getApiV4GroupsIdDashEpicsEpicIidIssues.md) |
| POST | `/api/v4/groups/{id}/(-/)epics/{epic_iid}/issues/{issue_id}` | Assign an issue to the epic | [View](../operations/postApiV4GroupsId-epicsEpicIidIssuesIssueId.md) |
| POST | `/api/v4/groups/{id}/epics/{epic_iid}/todo` | Create a to-do item for the current user on an epic | [View](../operations/postApiV4GroupsIdEpicsEpicIidTodo.md) |
