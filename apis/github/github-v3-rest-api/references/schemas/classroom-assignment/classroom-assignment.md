# classroom-assignment

A GitHub Classroom assignment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | Unique identifier of the repository. |
| `public_repo` | boolean | Yes | Whether an accepted assignment creates a public repository. |
| `title` | string | Yes | Assignment title. |
| `type` | enum: individual, group | Yes | Whether it's a group assignment or individual assignment. |
| `invite_link` | string | Yes | The link that a student can use to accept the assignment. |
| `invitations_enabled` | boolean | Yes | Whether the invitation link is enabled. Visiting an enabled invitation link will accept the assignment. |
| `slug` | string | Yes | Sluggified name of the assignment. |
| `students_are_repo_admins` | boolean | Yes | Whether students are admins on created repository when a student accepts the assignment. |
| `feedback_pull_requests_enabled` | boolean | Yes | Whether feedback pull request will be created when a student accepts the assignment. |
| `max_teams` | integer | Yes | The maximum allowable teams for the assignment. |
| `max_members` | integer | Yes | The maximum allowable members per team. |
| `editor` | string | Yes | The selected editor for the assignment. |
| `accepted` | integer | Yes | The number of students that have accepted the assignment. |
| `submitted` | integer | Yes | The number of students that have submitted the assignment. |
| `passing` | integer | Yes | The number of students that have passed the assignment. |
| `language` | string | Yes | The programming language used in the assignment. |
| `deadline` | string (date-time) | Yes | The time at which the assignment is due. |
| `starter_code_repository` | [simple-classroom-repository](simple-classroom-repository.md) | Yes |  |
| `classroom` | [classroom](classroom.md) | Yes |  |

