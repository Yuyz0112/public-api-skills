# Api20100401ConferenceRecording

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/2010-04-01/Accounts/{AccountSid}/Conferences/{ConferenceSid}/Recordings.json` | Retrieve a list of recordings belonging to the call used to make the request | [View](../operations/ListConferenceRecording.md) |
| GET | `/2010-04-01/Accounts/{AccountSid}/Conferences/{ConferenceSid}/Recordings/{Sid}.json` | Fetch an instance of a recording for a call | [View](../operations/FetchConferenceRecording.md) |
| POST | `/2010-04-01/Accounts/{AccountSid}/Conferences/{ConferenceSid}/Recordings/{Sid}.json` | Changes the status of the recording to paused, stopped, or in-progress. Note: To use `Twilio.CURRENT`, pass it as recording sid. | [View](../operations/UpdateConferenceRecording.md) |
| DELETE | `/2010-04-01/Accounts/{AccountSid}/Conferences/{ConferenceSid}/Recordings/{Sid}.json` | Delete a recording from your account | [View](../operations/DeleteConferenceRecording.md) |
