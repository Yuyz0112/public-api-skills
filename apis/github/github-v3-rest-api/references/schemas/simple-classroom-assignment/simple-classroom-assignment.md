# simple-classroom-assignment

A GitHub Classroom assignment

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `id` | integer | Yes | Unique identifier of the repository. |
| `public_repo` | boolean | Yes | Whether an accepted assignment creates a public repository. |
| `title` | string | Yes | Assignment title. |
| `type` | enum: individual, group | Yes | Whether it's a Group Assignment or Individual Assignment. |
| `invite_link` | string | Yes | The link that a student can use to accept the assignment. |
| `invitations_enabled` | boolean | Yes | Whether the invitation link is enabled. Visiting an enabled invitation link will accept the assignment. |
| `slug` | string | Yes | Sluggified name of the assignment. |
| `students_are_repo_admins` | boolean | Yes | Whether students are admins on created repository on accepted assignment. |
| `feedback_pull_requests_enabled` | boolean | Yes | Whether feedback pull request will be created on assignment acceptance. |
| `max_teams` | integer | No | The maximum allowable teams for the assignment. |
| `max_members` | integer | No | The maximum allowable members per team. |
| `editor` | string | Yes | The selected editor for the assignment. |
| `accepted` | integer | Yes | The number of students that have accepted the assignment. |
| `submitted` | integer | Yes | The number of students that have submitted the assignment. |
| `passing` | integer | Yes | The number of students that have passed the assignment. |
| `language` | string | Yes | The programming language used in the assignment. |
| `deadline` | string (date-time) | Yes | The time at which the assignment is due. |
| `classroom` | [simple-classroom](simple-classroom.md) | Yes |  |

